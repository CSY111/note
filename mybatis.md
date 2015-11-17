# Mybatis
## 1. 什么是 mybatis ？
- mybatis 是持久层框架，它支持定制 sql ， 存储过程和高级映射。它可以使用 **xml 文件**或者**注解**来配置和映射**基本数据类型**，**Map 接口**和 **POJO 对象**。
  
  
## 2. 几个核心对象的作用域和生命周期
### 2.1 SqlSessionFactoryBuilder
- 它的使命就是仅仅创建 SqlSessionFactory ， 之后可以马上扔掉。  
- 因此，SqlSessionFactoryBuilder 的实例的作用域最好是 **Method Scope** (i.e. 方法的局部变量)。

### 2.2 SqlSessionFactory
- SqlSessionFactory 一旦被创建了，就应该存在于应用执行的整个周期。  
- 所以，它的作用域最好是 **Application Scope**。  
- 比如，可以通过**单实例模式**来实现。 
- Mubatis 有一个工具类 **Resource** ，它用来加载资源，创建 SqlSessionFactory 的示例如下：
```java
String resource = "yourpath/mybatis-config.xml";
InputStream inputStream = Resource.getResourceAsStream(resource);
SqlSessionFactory session = new         SqlSessionFactoryBuilder().build(inputStream);
```

### 2.3 SqlSession  
- SqlSession 是线程不安全的，每一个线程应该拥有自己的一个 SqlSession 实例。
- 因此， SqlSession 的作用域最好是 **Request Scope** ，或者 ** Method Scope** 。  
- 永远不要把 SqlSession 的实例作为静态字段或者类的实例变量。
- 一定记得关闭 session 。
- 下面是它的示意用法：
```java
SqlSession session = sqlSessionFactory.openSession(); 
try { 
  // do work 
} finally { 
  session.close(); 
}
```

### 2.4 Mapper Instances
* Mapper 是用来绑定 Statement 的接口。  
* Mapper 的实例是通过 SqlSession 获取的。  
* 从技术上来说，Mapper 和 SqlSession 可以是一样的作用域，但是在 Request Scope 管理太多的资源是不合适的。  
* 因此， Mapper 的作用域最好是 **Method Scope** 。  
* 另外，跟 SqlSession 不同，Mapper 不需要显式关闭。  
* 下面是它的示意用法：
```java
SqlSession session = sqlSessionFactory.openSession(); 
try { 
  BlogMapper mapper = session.getMapper(BlogMapper.class); 
  // do work 
} finally { 
  session.close(); 
} 
```

