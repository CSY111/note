<!DOCTYPE html>
<!-- saved from url=(0063)http://mybatis.org/mybatis-3/zh/configuration.html#typeHandlers -->
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="zh" lang="zh"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="author" content="Clinton Begin">
    <meta name="author" content="Nan Lei">
    <meta name="author" content="Dongxu Wang">
    <meta name="Date-Revision-yyyymmdd" content="20150924">
    <meta http-equiv="Content-Language" content="zh">
    <title>mybatis – MyBatis 3 | 配置</title>
    <link rel="stylesheet" href="./mybatis – MyBatis 3 _ 配置_files/apache-maven-fluido-1.4.min.css">
    <link rel="stylesheet" href="./mybatis – MyBatis 3 _ 配置_files/site.css">
    <link rel="stylesheet" href="./mybatis – MyBatis 3 _ 配置_files/print.css" media="print">

      
    <script type="text/javascript" src="./mybatis – MyBatis 3 _ 配置_files/apache-maven-fluido-1.4.min.js"></script>

    
                  </head>
        <body class="topBarDisabled">
          
        
    
        <div class="container-fluid">
          <div id="banner">
        <div class="pull-left">
                                <div id="bannerLeft">
                <h2>mybatis</h2>
                </div>
                      </div>
        <div class="pull-right">                                <a href="http://mybatis.org/" id="bannerRight" title="MyBatis logo">
                                                                                        <img src="./mybatis – MyBatis 3 _ 配置_files/mybatis-logo.png" alt="MyBatis logo">
                </a>
      </div>
        <div class="clear"><hr></div>
      </div>

      <div id="breadcrumbs">
        <ul class="breadcrumb">
                
                    
                  <li id="publishDate">最近更新: 24 九月 2015
                      <span class="divider">|</span>
                   </li>
                  <li id="projectVersion">版本: 3.4.0-SNAPSHOT
                      </li>
                      
                
                    
      
                            </ul>
      </div>

            
      <div class="row-fluid">
        <div id="leftColumn" class="span2">
          <div class="well sidebar-nav">
                
                    
                <ul class="nav nav-list">
                    <li class="nav-header">参考文档</li>
                              
      <li>
  
                          <a href="http://mybatis.org/mybatis-3/zh/index.html" title="简介">
          <span class="none"></span>
        简介</a>
            </li>
                
      <li>
  
                          <a href="http://mybatis.org/mybatis-3/zh/getting-started.html" title="入门">
          <span class="none"></span>
        入门</a>
            </li>
                                                                                                                                                                                                                      
      <li class="active">
  
            <a href="http://mybatis.org/mybatis-3/zh/configuration.html#"><span class="icon-chevron-down"></span>XML配置</a>
                  <ul class="nav nav-list">
                    
      <li>
  
                          <a href="http://mybatis.org/mybatis-3/zh/configuration.html#properties" title="属性(properties)">
          <span class="none"></span>
        属性(properties)</a>
            </li>
                    
      <li>
  
                          <a href="http://mybatis.org/mybatis-3/zh/configuration.html#settings" title="设置(settings)">
          <span class="none"></span>
        设置(settings)</a>
            </li>
                    
      <li>
  
                          <a href="http://mybatis.org/mybatis-3/zh/configuration.html#typeAliases" title="类型别名(typeAliases)">
          <span class="none"></span>
        类型别名(typeAliases)</a>
            </li>
                    
      <li>
  
                          <a href="./mybatis – MyBatis 3 _ 配置_files/mybatis – MyBatis 3 _ 配置.md" title="类型处理(typeHandlers)">
          <span class="none"></span>
        类型处理(typeHandlers)</a>
            </li>
                    
      <li>
  
                          <a href="http://mybatis.org/mybatis-3/zh/configuration.html#objectFactory" title="对象工厂(objectFactory)">
          <span class="none"></span>
        对象工厂(objectFactory)</a>
            </li>
                    
      <li>
  
                          <a href="http://mybatis.org/mybatis-3/zh/configuration.html#plugins" title="插件(plugins)">
          <span class="none"></span>
        插件(plugins)</a>
            </li>
                    
      <li>
  
                          <a href="http://mybatis.org/mybatis-3/zh/configuration.html#environments" title="环境配置(environments)">
          <span class="none"></span>
        环境配置(environments)</a>
            </li>
                    
      <li>
  
                          <a href="http://mybatis.org/mybatis-3/zh/configuration.html#databaseIdProvider" title="数据库厂商标识(databaseIdProvider)">
          <span class="none"></span>
        数据库厂商标识(databaseIdProvider)</a>
            </li>
                    
      <li>
  
                          <a href="http://mybatis.org/mybatis-3/zh/configuration.html#mappers" title="映射器(mappers)">
          <span class="none"></span>
        映射器(mappers)</a>
            </li>
              </ul>
        </li>
                                                                                                                                                            
      <li>
  
                          <a href="http://mybatis.org/mybatis-3/zh/sqlmap-xml.html" title="XML映射文件">
          <span class="icon-chevron-right"></span>
        XML映射文件</a>
                  </li>
                
      <li>
  
                          <a href="http://mybatis.org/mybatis-3/zh/dynamic-sql.html" title="动态SQL">
          <span class="none"></span>
        动态SQL</a>
            </li>
                                                                                    
      <li>
  
                          <a href="http://mybatis.org/mybatis-3/zh/java-api.html" title="Java API">
          <span class="icon-chevron-right"></span>
        Java API</a>
                  </li>
                
      <li>
  
                          <a href="http://mybatis.org/mybatis-3/zh/statement-builders.html" title="SQL语句构建器">
          <span class="none"></span>
        SQL语句构建器</a>
            </li>
                
      <li>
  
                          <a href="http://mybatis.org/mybatis-3/zh/log   ging.html" title="日志">
          <span class="none"></span>
        日志</a>
            </li>
                              <li class="nav-header">项目文档</li>
                                                                                                                                                                                                                                                                                      
      <li>
  
                          <a href="http://mybatis.org/mybatis-3/zh/project-info.html" title="项目信息">
          <span class="icon-chevron-right"></span>
        项目信息</a>
                  </li>
                                                                                                                                                                                                                                                                                          
      <li>
  
                          <a href="http://mybatis.org/mybatis-3/zh/project-reports.html" title="项目报表">
          <span class="icon-chevron-right"></span>
        项目报表</a>
                  </li>
            </ul>
                
                    
                
          <hr>

           <div id="poweredBy">
                            <div class="clear"></div>
                            <div class="clear"></div>
                            <div class="clear"></div>
                            <div class="clear"></div>
                             <a href="http://maven.apache.org/" title="构建依靠 Maven" class="poweredBy">
        <img class="builtBy" alt="构建依靠 Maven" src="./mybatis – MyBatis 3 _ 配置_files/maven-feather.png">
      </a>
                  </div>
          </div>
        </div>
        
                
        <div id="bodyColumn" class="span10">
                                  
            <!-- Copyright 2010-2012 the original author or authors.

  Licensed under the Apache License, Version 2.0 (the "License");
  you may not use this file except in compliance with the License.
  You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

  Unless required by applicable law or agreed to in writing, software
  distributed under the License is distributed on an "AS IS" BASIS,
  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
  See the License for the specific language governing permissions and
  limitations under the License. --><!-- version: $Id$ -->

  
    <div class="section">
<h2><a name="XML_"></a>XML 映射配置文件</h2>
      
<p>MyBatis 的配置文件包含了影响 MyBatis 行为甚深的设置（settings）和属性（properties）信息。文档的顶层结构如下：</p>

      
<ul>
        
<li>
          configuration 配置
          
<ul>
            
<li><a href="http://mybatis.org/mybatis-3/zh/configuration.html#properties">properties 属性</a></li>
            
<li><a href="http://mybatis.org/mybatis-3/zh/configuration.html#settings">settings 设置</a></li>
            
<li><a href="http://mybatis.org/mybatis-3/zh/configuration.html#typeAliases">typeAliases 类型命名</a></li>
            
<li><a href="./mybatis – MyBatis 3 _ 配置_files/mybatis – MyBatis 3 _ 配置.md">typeHandlers 类型处理器</a></li>
            
<li><a href="http://mybatis.org/mybatis-3/zh/configuration.html#objectFactory">objectFactory 对象工厂</a></li>
            
<li><a href="http://mybatis.org/mybatis-3/zh/configuration.html#plugins">plugins 插件</a></li>
            
<li><a href="http://mybatis.org/mybatis-3/zh/configuration.html#environments">environments 环境</a>
              
<ul>
                
<li>
                  environment 环境变量
                  
<ul>
                    
<li>transactionManager 事务管理器</li>
                    
<li>dataSource 数据源</li>
                  </ul>
                </li>
              </ul>
            </li>
            
<li><a href="http://mybatis.org/mybatis-3/zh/configuration.html#databaseIdProvider">databaseIdProvider 数据库厂商标识</a></li>
            
<li><a href="http://mybatis.org/mybatis-3/zh/configuration.html#mappers">mappers 映射器</a></li>
          </ul>
        </li>
      </ul>
      <a name="properties"></a>
<div class="section" id="properties">
<h3><a name="properties"></a>properties</h3>
        
<p>这些属性都是可外部配置且可动态替换的，既可以在典型的 Java 属性文件中配置，亦可通过 properties 元素的子元素来传递。例如：</p>
        
<div class="source"><pre class="prettyprint"><span class="tag">&lt;properties</span><span class="pln"> </span><span class="atn">resource</span><span class="pun">=</span><span class="atv">"org/mybatis/example/config.properties"</span><span class="tag">&gt;</span><span class="pln">
  </span><span class="tag">&lt;property</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"username"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"dev_user"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;property</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"password"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"F2Fa3!33TYyg"</span><span class="tag">/&gt;</span><span class="pln">
</span><span class="tag">&lt;/properties&gt;</span></pre></div>
        
<p>其中的属性就可以在整个配置文件中使用来替换需要动态配置的属性值。比如:
        </p>
        
<div class="source"><pre class="prettyprint"><span class="tag">&lt;dataSource</span><span class="pln"> </span><span class="atn">type</span><span class="pun">=</span><span class="atv">"POOLED"</span><span class="tag">&gt;</span><span class="pln">
  </span><span class="tag">&lt;property</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"driver"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"${driver}"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;property</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"url"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"${url}"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;property</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"username"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"${username}"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;property</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"password"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"${password}"</span><span class="tag">/&gt;</span><span class="pln">
</span><span class="tag">&lt;/dataSource&gt;</span></pre></div>
        
<p>这个例子中的 username 和 password 将会由 properties 元素中设置的相应值来替换。
          driver 和 url 属性将会由 config.properties 文件中对应的值来替换。这样就为配置提供了诸多灵活选择。</p>
        
<p>属性也可以被传递到 SqlSessionBuilder.build()方法中。例如：</p>
        
<div class="source"><pre class="prettyprint"><span class="typ">SqlSessionFactory</span><span class="pln"> factory </span><span class="pun">=</span><span class="pln"> sqlSessionFactoryBuilder</span><span class="pun">.</span><span class="pln">build</span><span class="pun">(</span><span class="pln">reader</span><span class="pun">,</span><span class="pln"> props</span><span class="pun">);</span><span class="pln">

</span><span class="com">// ... or ...</span><span class="pln">

</span><span class="typ">SqlSessionFactory</span><span class="pln"> factory </span><span class="pun">=</span><span class="pln"> sqlSessionFactoryBuilder</span><span class="pun">.</span><span class="pln">build</span><span class="pun">(</span><span class="pln">reader</span><span class="pun">,</span><span class="pln"> environment</span><span class="pun">,</span><span class="pln"> props</span><span class="pun">);</span></pre></div>
        
<p>如果属性在不只一个地方进行了配置，那么 MyBatis 将按照下面的顺序来加载：</p>
        
<ul>
          
<li>在 properties 元素体内指定的属性首先被读取。
          </li>
          
<li>然后根据 properties 元素中的 resource 属性读取类路径下属性文件或根据 url 属性指定的路径读取属性文件，并覆盖已读取的同名属性。
          </li>
          
<li>最后读取作为方法参数传递的属性，并覆盖已读取的同名属性。
          </li>
        </ul>
        
<p>因此，通过方法参数传递的属性具有最高优先级，resource/url 属性中指定的配置文件次之，最低优先级的是 properties 属性中指定的属性。</p>
      </div>
      <a name="settings"></a>
<div class="section" id="settings">
<h3><a name="settings"></a>settings</h3>
        
<p>这是 MyBatis 中极为重要的调整设置，它们会改变 MyBatis 的运行时行为。下表描述了设置中各项的意图、默认值等。</p>

        
<table border="0" class="table table-striped">
          <thead>
            
<tr class="a">
              
<th>设置参数</th>
              
<th>描述</th>
              
<th>有效值</th>
              
<th>默认值</th>
            </tr>
          </thead>
          <tbody>
            
<tr class="b">
              
<td>
                cacheEnabled
              </td>
              
<td>
                该配置影响的所有映射器中配置的缓存的全局开关。
              </td>
              
<td>
                true | false
              </td>
              
<td>
                true
              </td>
            </tr>
            
<tr class="a">
              
<td>
                lazyLoadingEnabled
              </td>
              
<td>
                延迟加载的全局开关。当开启时，所有关联对象都会延迟加载。
                特定关联关系中可通过设置<tt>fetchType</tt>属性来覆盖该项的开关状态。
              </td>
              
<td>
                true | false
              </td>
              
<td>
                false
              </td>
            </tr>
            
<tr class="b">
              
<td>
                aggressiveLazyLoading
              </td>
              
<td>
                当启用时，对任意延迟属性的调用会使带有延迟加载属性的对象完整加载；反之，每种属性将会按需加载。
              </td>
              
<td>
                true | false
              </td>
              
<td>
                true
              </td>
            </tr>
            
<tr class="a">
              
<td>
                multipleResultSetsEnabled
              </td>
              
<td>
                是否允许单一语句返回多结果集（需要兼容驱动）。
              </td>
              
<td>
                true | false
              </td>
              
<td>
                true
              </td>
            </tr>
            
<tr class="b">
              
<td>
                useColumnLabel
              </td>
              
<td>
                使用列标签代替列名。不同的驱动在这方面会有不同的表现，
                具体可参考相关驱动文档或通过测试这两种不同的模式来观察所用驱动的结果。
              </td>
              
<td>
                true | false
              </td>
              
<td>
                true
              </td>
            </tr>
            
<tr class="a">
              
<td>
                useGeneratedKeys
              </td>
              
<td>
                允许 JDBC 支持自动生成主键，需要驱动兼容。
                如果设置为 true 则这个设置强制使用自动生成主键，尽管一些驱动不能兼容但仍可正常工作（比如 Derby）。
              </td>
              
<td>
                true | false
              </td>
              
<td>
                False
              </td>
            </tr>
            
<tr class="b">
              
<td>
                autoMappingBehavior
              </td>
              
<td>
                指定 MyBatis 应如何自动映射列到字段或属性。
                NONE 表示取消自动映射；PARTIAL 只会自动映射没有定义嵌套结果集映射的结果集。
                FULL 会自动映射任意复杂的结果集（无论是否嵌套）。
              </td>
              
<td>
                NONE, PARTIAL, FULL
              </td>
              
<td>
                PARTIAL
              </td>
            </tr>
            
<tr class="a">
              
<td>
                defaultExecutorType
              </td>
              
<td>
                配置默认的执行器。SIMPLE 就是普通的执行器；REUSE 执行器会重用预处理语句（prepared statements）；
                BATCH 执行器将重用语句并执行批量更新。
              </td>
              
<td>
                SIMPLE
                REUSE
                BATCH
              </td>
              
<td>
                SIMPLE
              </td>
            </tr>
            
<tr class="b">
              
<td>
                defaultStatementTimeout
              </td>
              
<td>
                设置超时时间，它决定驱动等待数据库响应的秒数。
              </td>
              
<td>
                Any positive integer
              </td>
              
<td>
                Not Set (null)
              </td>
            </tr>
            
<tr class="a">
              
<td>
                defaultFetchSize
              </td>
              
<td>
                Sets the driver a hint as to control fetching size for return results.
                This parameter value can be override by a query setting.
              </td>
              
<td>
                Any positive integer
              </td>
              
<td>
                Not Set (null)
              </td>
            </tr>
            
<tr class="b">
              
<td>
                safeRowBoundsEnabled
              </td>
              
<td>
                允许在嵌套语句中使用分页（RowBounds）。
              </td>
              
<td>
                true | false
              </td>
              
<td>
                False
              </td>
            </tr>
            
<tr class="a">
              
<td>
                mapUnderscoreToCamelCase
              </td>
              
<td>
                是否开启自动驼峰命名规则（camel case）映射，即从经典数据库列名 A_COLUMN 到经典 Java 属性名 aColumn 的类似映射。
              </td>
              
<td>
                true | false
              </td>
              
<td>
                False
              </td>
            </tr>
            
<tr class="b">
              
<td>
                localCacheScope
              </td>
              
<td>
                MyBatis 利用本地缓存机制（Local Cache）防止循环引用（circular references）和加速重复嵌套查询。
                默认值为 SESSION，这种情况下会缓存一个会话中执行的所有查询。
                若设置值为 STATEMENT，本地会话仅用在语句执行上，对相同 SqlSession 的不同调用将不会共享数据。
              </td>
              
<td>
                SESSION | STATEMENT
              </td>
              
<td>
                SESSION
              </td>
            </tr>
            
<tr class="a">
              
<td>
                jdbcTypeForNull
              </td>
              
<td>
                当没有为参数提供特定的 JDBC 类型时，为空值指定 JDBC 类型。
                某些驱动需要指定列的 JDBC 类型，多数情况直接用一般类型即可，比如 NULL、VARCHAR 或 OTHER。
              </td>
              
<td>
                JdbcType enumeration. Most common are: NULL, VARCHAR and OTHER
              </td>
              
<td>
                OTHER
              </td>
            </tr>
            
<tr class="b">
              
<td>
                lazyLoadTriggerMethods
              </td>
              
<td>
                指定哪个对象的方法触发一次延迟加载。
              </td>
              
<td>
                A method name list separated by commas
              </td>
              
<td>
                equals,clone,hashCode,toString
              </td>
            </tr>
            
<tr class="a">
              
<td>
                defaultScriptingLanguage
              </td>
              
<td>
                指定动态 SQL 生成的默认语言。
              </td>
              
<td>
                A type alias or fully qualified class name.
              </td>
              
<td>
                org.apache.ibatis.scripting.xmltags.XMLDynamicLanguageDriver
              </td>
            </tr>
            
<tr class="b">
              
<td>
                callSettersOnNulls
              </td>
              
<td>
                指定当结果集中值为 null 的时候是否调用映射对象的 setter（map 对象时为 put）方法，这对于有 Map.keySet() 依赖或 null 值初始化的时候是有用的。注意基本类型（int、boolean等）是不能设置成 null 的。
              </td>
              
<td>
                true | false
              </td>
              
<td>
                false
              </td>
            </tr>
            
<tr class="a">
              
<td>
                logPrefix
              </td>
              
<td>
                指定 MyBatis 增加到日志名称的前缀。
              </td>
              
<td>
                Any String
              </td>
              
<td>
                Not set
              </td>
            </tr>
            
<tr class="b">
              
<td>
                logImpl
              </td>
              
<td>
                指定 MyBatis 所用日志的具体实现，未指定时将自动查找。
              </td>
              
<td>
                SLF4J | LOG4J | LOG4J2 | JDK_LOGGING | COMMONS_LOGGING | STDOUT_LOGGING | NO_LOGGING
              </td>
              
<td>
                Not set
              </td>
            </tr>
            
<tr class="a">
              
<td>
                proxyFactory
              </td>
              
<td>
                指定 Mybatis 创建具有延迟加载能力的对象所用到的代理工具。
              </td>
              
<td>
                CGLIB | JAVASSIST
              </td>
              
<td>
                JAVASSIST (MyBatis 3.3 or above)
              </td>
            </tr>
            
<tr class="b">
              
<td>
                vfsImpl
              </td>
              
<td>
                Specifies VFS implementations
              </td>
              
<td>
                Fully qualified class names of custom VFS implementation separated by commas.
              </td>
              
<td>
                Not set
              </td>
            </tr>
          </tbody>
        </table>
        
<p>
          一个配置完整的 settings 元素的示例如下：
        </p>
        
<div class="source"><pre class="prettyprint"><span class="tag">&lt;settings&gt;</span><span class="pln">
  </span><span class="tag">&lt;setting</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"cacheEnabled"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"true"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;setting</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"lazyLoadingEnabled"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"true"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;setting</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"multipleResultSetsEnabled"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"true"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;setting</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"useColumnLabel"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"true"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;setting</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"useGeneratedKeys"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"false"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;setting</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"autoMappingBehavior"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"PARTIAL"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;setting</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"defaultExecutorType"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"SIMPLE"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;setting</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"defaultStatementTimeout"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"25"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;setting</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"defaultFetchSize"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"100"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;setting</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"safeRowBoundsEnabled"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"false"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;setting</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"mapUnderscoreToCamelCase"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"false"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;setting</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"localCacheScope"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"SESSION"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;setting</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"jdbcTypeForNull"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"OTHER"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;setting</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"lazyLoadTriggerMethods"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"equals,clone,hashCode,toString"</span><span class="tag">/&gt;</span><span class="pln">
</span><span class="tag">&lt;/settings&gt;</span></pre></div>

      </div>
      <a name="typeAliases"></a>
<div class="section" id="typeAliases">
<h3><a name="typeAliases"></a>typeAliases</h3>
        
<p>类型别名是为 Java 类型设置一个短的名字。它只和 XML 配置有关，存在的意义仅在于用来减少类完全限定名的冗余。例如:</p>
        
<div class="source"><pre class="prettyprint"><span class="tag">&lt;typeAliases&gt;</span><span class="pln">
  </span><span class="tag">&lt;typeAlias</span><span class="pln"> </span><span class="atn">alias</span><span class="pun">=</span><span class="atv">"Author"</span><span class="pln"> </span><span class="atn">type</span><span class="pun">=</span><span class="atv">"domain.blog.Author"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;typeAlias</span><span class="pln"> </span><span class="atn">alias</span><span class="pun">=</span><span class="atv">"Blog"</span><span class="pln"> </span><span class="atn">type</span><span class="pun">=</span><span class="atv">"domain.blog.Blog"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;typeAlias</span><span class="pln"> </span><span class="atn">alias</span><span class="pun">=</span><span class="atv">"Comment"</span><span class="pln"> </span><span class="atn">type</span><span class="pun">=</span><span class="atv">"domain.blog.Comment"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;typeAlias</span><span class="pln"> </span><span class="atn">alias</span><span class="pun">=</span><span class="atv">"Post"</span><span class="pln"> </span><span class="atn">type</span><span class="pun">=</span><span class="atv">"domain.blog.Post"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;typeAlias</span><span class="pln"> </span><span class="atn">alias</span><span class="pun">=</span><span class="atv">"Section"</span><span class="pln"> </span><span class="atn">type</span><span class="pun">=</span><span class="atv">"domain.blog.Section"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;typeAlias</span><span class="pln"> </span><span class="atn">alias</span><span class="pun">=</span><span class="atv">"Tag"</span><span class="pln"> </span><span class="atn">type</span><span class="pun">=</span><span class="atv">"domain.blog.Tag"</span><span class="tag">/&gt;</span><span class="pln">
</span><span class="tag">&lt;/typeAliases&gt;</span></pre></div>
        
<p>当这样配置时，<tt>Blog</tt>可以用在任何使用<tt>domain.blog.Blog</tt>的地方。</p>
        
<p>也可以指定一个包名，MyBatis 会在包名下面搜索需要的 Java Bean，比如:
        </p>
        
<div class="source"><pre class="prettyprint"><span class="tag">&lt;typeAliases&gt;</span><span class="pln">
  </span><span class="tag">&lt;package</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"domain.blog"</span><span class="tag">/&gt;</span><span class="pln">
</span><span class="tag">&lt;/typeAliases&gt;</span></pre></div>
        
<p>每一个在包 <tt>domain.blog</tt> 中的 Java Bean，在没有注解的情况下，会使用 Bean 的首字母小写的非限定类名来作为它的别名。
          比如 <tt>domain.blog.Author</tt> 的别名为 <tt>author</tt>；若有注解，则别名为其注解值。看下面的例子：</p>
        
<div class="source"><pre class="prettyprint"><span class="lit">@Alias</span><span class="pun">(</span><span class="str">"author"</span><span class="pun">)</span><span class="pln">
</span><span class="kwd">public</span><span class="pln"> </span><span class="kwd">class</span><span class="pln"> </span><span class="typ">Author</span><span class="pln"> </span><span class="pun">{</span><span class="pln">
    </span><span class="pun">...</span><span class="pln">
</span><span class="pun">}</span></pre></div>
        
<p>已经为许多常见的 Java 类型内建了相应的类型别名。它们都是大小写不敏感的，需要注意的是由基本类型名称重复导致的特殊处理。</p>
        
<table border="0" class="table table-striped">
          <thead>
            
<tr class="a">
              
<th>
                别名
              </th>
              
<th>
                映射的类型
              </th>
            </tr>
          </thead>
          <tbody>
            
<tr class="b">
              
<td>
                _byte
              </td>
              
<td>
                byte
              </td>
            </tr>
            
<tr class="a">
              
<td>
                _long
              </td>
              
<td>
                long
              </td>
            </tr>
            
<tr class="b">
              
<td>
                _short
              </td>
              
<td>
                short
              </td>
            </tr>
            
<tr class="a">
              
<td>
                _int
              </td>
              
<td>
                int
              </td>
            </tr>
            
<tr class="b">
              
<td>
                _integer
              </td>
              
<td>
                int
              </td>
            </tr>
            
<tr class="a">
              
<td>
                _double
              </td>
              
<td>
                double
              </td>
            </tr>
            
<tr class="b">
              
<td>
                _float
              </td>
              
<td>
                float
              </td>
            </tr>
            
<tr class="a">
              
<td>
                _boolean
              </td>
              
<td>
                boolean
              </td>
            </tr>
            
<tr class="b">
              
<td>
                string
              </td>
              
<td>
                String
              </td>
            </tr>
            
<tr class="a">
              
<td>
                byte
              </td>
              
<td>
                Byte
              </td>
            </tr>
            
<tr class="b">
              
<td>
                long
              </td>
              
<td>
                Long
              </td>
            </tr>
            
<tr class="a">
              
<td>
                short
              </td>
              
<td>
                Short
              </td>
            </tr>
            
<tr class="b">
              
<td>
                int
              </td>
              
<td>
                Integer
              </td>
            </tr>
            
<tr class="a">
              
<td>
                integer
              </td>
              
<td>
                Integer
              </td>
            </tr>
            
<tr class="b">
              
<td>
                double
              </td>
              
<td>
                Double
              </td>
            </tr>
            
<tr class="a">
              
<td>
                float
              </td>
              
<td>
                Float
              </td>
            </tr>
            
<tr class="b">
              
<td>
                boolean
              </td>
              
<td>
                Boolean
              </td>
            </tr>
            
<tr class="a">
              
<td>
                date
              </td>
              
<td>
                Date
              </td>
            </tr>
            
<tr class="b">
              
<td>
                decimal
              </td>
              
<td>
                BigDecimal
              </td>
            </tr>
            
<tr class="a">
              
<td>
                bigdecimal
              </td>
              
<td>
                BigDecimal
              </td>
            </tr>
            
<tr class="b">
              
<td>
                object
              </td>
              
<td>
                Object
              </td>
            </tr>
            
<tr class="a">
              
<td>
                map
              </td>
              
<td>
                Map
              </td>
            </tr>
            
<tr class="b">
              
<td>
                hashmap
              </td>
              
<td>
                HashMap
              </td>
            </tr>
            
<tr class="a">
              
<td>
                list
              </td>
              
<td>
                List
              </td>
            </tr>
            
<tr class="b">
              
<td>
                arraylist
              </td>
              
<td>
                ArrayList
              </td>
            </tr>
            
<tr class="a">
              
<td>
                collection
              </td>
              
<td>
                Collection
              </td>
            </tr>
            
<tr class="b">
              
<td>
                iterator
              </td>
              
<td>
                Iterator
              </td>
            </tr>
          </tbody>
        </table>
      </div>
      <a name="typeHandlers"></a>
<div class="section" id="typeHandlers">
<h3><a name="typeHandlers"></a>typeHandlers</h3>
        
<p>无论是 MyBatis 在预处理语句（PreparedStatement）中设置一个参数时，还是从结果集中取出一个值时，
          都会用类型处理器将获取的值以合适的方式转换成 Java 类型。下表描述了一些默认的类型处理器。</p>
        
<table border="0" class="table table-striped">
          <thead>
            
<tr class="a">
              
<th>
                类型处理器
              </th>
              
<th>
                Java 类型
              </th>
              
<th>
                JDBC 类型
              </th>
            </tr>
          </thead>
          <tbody>
            
<tr class="b">
              
<td>
                <tt>BooleanTypeHandler</tt>
              </td>
              
<td>
                <tt>java.lang.Boolean</tt>, <tt>boolean</tt>
              </td>
              
<td>
                数据库兼容的 <tt>BOOLEAN</tt>
              </td>
            </tr>
            
<tr class="a">
              
<td>
                <tt>ByteTypeHandler</tt>
              </td>
              
<td>
                <tt>java.lang.Byte</tt>, <tt>byte</tt>
              </td>
              
<td>
                数据库兼容的 <tt>NUMERIC</tt> 或 <tt>BYTE</tt>
              </td>
            </tr>
            
<tr class="b">
              
<td>
                <tt>ShortTypeHandler</tt>
              </td>
              
<td>
                <tt>java.lang.Short</tt>, <tt>short</tt>
              </td>
              
<td>
                数据库兼容的 <tt>NUMERIC</tt> 或 <tt>SHORT INTEGER</tt>
              </td>
            </tr>
            
<tr class="a">
              
<td>
                <tt>IntegerTypeHandler</tt>
              </td>
              
<td>
                <tt>java.lang.Integer</tt>, <tt>int</tt>
              </td>
              
<td>
                数据库兼容的 <tt>NUMERIC</tt> 或 <tt>INTEGER</tt>
              </td>
            </tr>
            
<tr class="b">
              
<td>
                <tt>LongTypeHandler</tt>
              </td>
              
<td>
                <tt>java.lang.Long</tt>, <tt>long</tt>
              </td>
              
<td>
                数据库兼容的 <tt>NUMERIC</tt> 或 <tt>LONG INTEGER</tt>
              </td>
            </tr>
            
<tr class="a">
              
<td>
                <tt>FloatTypeHandler</tt>
              </td>
              
<td>
                <tt>java.lang.Float</tt>, <tt>float</tt>
              </td>
              
<td>
                数据库兼容的 <tt>NUMERIC</tt> 或 <tt>FLOAT</tt>
              </td>
            </tr>
            
<tr class="b">
              
<td>
                <tt>DoubleTypeHandler</tt>
              </td>
              
<td>
                <tt>java.lang.Double</tt>, <tt>double</tt>
              </td>
              
<td>
                数据库兼容的 <tt>NUMERIC</tt> 或 <tt>DOUBLE</tt>
              </td>
            </tr>
            
<tr class="a">
              
<td>
                <tt>BigDecimalTypeHandler</tt>
              </td>
              
<td>
                <tt>java.math.BigDecimal</tt>
              </td>
              
<td>
                数据库兼容的 <tt>NUMERIC</tt> 或 <tt>DECIMAL</tt>
              </td>
            </tr>
            
<tr class="b">
              
<td>
                <tt>StringTypeHandler</tt>
              </td>
              
<td>
                <tt>java.lang.String</tt>
              </td>
              
<td>
                <tt>CHAR</tt>, <tt>VARCHAR</tt>
              </td>
            </tr>
            
<tr class="a">
              
<td>
                <tt>ClobTypeHandler</tt>
              </td>
              
<td>
                <tt>java.lang.String</tt>
              </td>
              
<td>
                <tt>CLOB</tt>, <tt>LONGVARCHAR</tt>
              </td>
            </tr>
            
<tr class="b">
              
<td>
                <tt>NStringTypeHandler</tt>
              </td>
              
<td>
                <tt>java.lang.String</tt>
              </td>
              
<td>
                <tt>NVARCHAR</tt>, <tt>NCHAR</tt>
              </td>
            </tr>
            
<tr class="a">
              
<td>
                <tt>NClobTypeHandler</tt>
              </td>
              
<td>
                <tt>java.lang.String</tt>
              </td>
              
<td>
                <tt>NCLOB</tt>
              </td>
            </tr>
            
<tr class="b">
              
<td>
                <tt>ByteArrayTypeHandler</tt>
              </td>
              
<td>
                <tt>byte[]</tt>
              </td>
              
<td>
                数据库兼容的字节流类型
              </td>
            </tr>
            
<tr class="a">
              
<td>
                <tt>BlobTypeHandler</tt>
              </td>
              
<td>
                <tt>byte[]</tt>
              </td>
              
<td>
                <tt>BLOB</tt>, <tt>LONGVARBINARY</tt>
              </td>
            </tr>
            
<tr class="b">
              
<td>
                <tt>DateTypeHandler</tt>
              </td>
              
<td>
                <tt>java.util.Date</tt>
              </td>
              
<td>
                <tt>TIMESTAMP</tt>
              </td>
            </tr>
            
<tr class="a">
              
<td>
                <tt>DateOnlyTypeHandler</tt>
              </td>
              
<td>
                <tt>java.util.Date</tt>
              </td>
              
<td>
                <tt>DATE</tt>
              </td>
            </tr>
            
<tr class="b">
              
<td>
                <tt>TimeOnlyTypeHandler</tt>
              </td>
              
<td>
                <tt>java.util.Date</tt>
              </td>
              
<td>
                <tt>TIME</tt>
              </td>
            </tr>
            
<tr class="a">
              
<td>
                <tt>SqlTimestampTypeHandler</tt>
              </td>
              
<td>
                <tt>java.sql.Timestamp</tt>
              </td>
              
<td>
                <tt>TIMESTAMP</tt>
              </td>
            </tr>
            
<tr class="b">
              
<td>
                <tt>SqlDateTypeHandler</tt>
              </td>
              
<td>
                <tt>java.sql.Date</tt>
              </td>
              
<td>
                <tt>DATE</tt>
              </td>
            </tr>
            
<tr class="a">
              
<td>
                <tt>SqlTimeTypeHandler</tt>
              </td>
              
<td>
                <tt>java.sql.Time</tt>
              </td>
              
<td>
                <tt>TIME</tt>
              </td>
            </tr>
            
<tr class="b">
              
<td>
                <tt>ObjectTypeHandler</tt>
              </td>
              
<td>
                Any
              </td>
              
<td>
                <tt>OTHER</tt> 或未指定类型
              </td>
            </tr>
            
<tr class="a">
              
<td>
                <tt>EnumTypeHandler</tt>
              </td>
              
<td>
                Enumeration Type
              </td>
              
<td>
                VARCHAR-任何兼容的字符串类型，存储枚举的名称（而不是索引）
              </td>
            </tr>
            
<tr class="b">
              
<td>
                <tt>EnumOrdinalTypeHandler</tt>
              </td>
              
<td>
                Enumeration Type
              </td>
              
<td>
                任何兼容的 <tt>NUMERIC</tt> 或 <tt>DOUBLE</tt> 类型，存储枚举的索引（而不是名称）。
              </td>
            </tr>
          </tbody>
        </table>
        
<p>
          你可以重写类型处理器或创建你自己的类型处理器来处理不支持的或非标准的类型。
          具体做法为：实现 <tt>org.apache.ibatis.type.TypeHandler</tt> 接口，
          或继承一个很便利的类 <tt>org.apache.ibatis.type.BaseTypeHandler</tt>，
          然后可以选择性地将它映射到一个 JDBC 类型。比如：
        </p>
        
<div class="source"><pre class="prettyprint"><span class="com">// ExampleTypeHandler.java</span><span class="pln">
</span><span class="lit">@MappedJdbcTypes</span><span class="pun">(</span><span class="typ">JdbcType</span><span class="pun">.</span><span class="pln">VARCHAR</span><span class="pun">)</span><span class="pln">
</span><span class="kwd">public</span><span class="pln"> </span><span class="kwd">class</span><span class="pln"> </span><span class="typ">ExampleTypeHandler</span><span class="pln"> </span><span class="kwd">extends</span><span class="pln"> </span><span class="typ">BaseTypeHandler</span><span class="pun">&lt;</span><span class="typ">String</span><span class="pun">&gt;</span><span class="pln"> </span><span class="pun">{</span><span class="pln">

  </span><span class="lit">@Override</span><span class="pln">
  </span><span class="kwd">public</span><span class="pln"> </span><span class="kwd">void</span><span class="pln"> setNonNullParameter</span><span class="pun">(</span><span class="typ">PreparedStatement</span><span class="pln"> ps</span><span class="pun">,</span><span class="pln"> </span><span class="kwd">int</span><span class="pln"> i</span><span class="pun">,</span><span class="pln"> </span><span class="typ">String</span><span class="pln"> parameter</span><span class="pun">,</span><span class="pln"> </span><span class="typ">JdbcType</span><span class="pln"> jdbcType</span><span class="pun">)</span><span class="pln"> </span><span class="kwd">throws</span><span class="pln"> </span><span class="typ">SQLException</span><span class="pln"> </span><span class="pun">{</span><span class="pln">
    ps</span><span class="pun">.</span><span class="pln">setString</span><span class="pun">(</span><span class="pln">i</span><span class="pun">,</span><span class="pln"> parameter</span><span class="pun">);</span><span class="pln">
  </span><span class="pun">}</span><span class="pln">

  </span><span class="lit">@Override</span><span class="pln">
  </span><span class="kwd">public</span><span class="pln"> </span><span class="typ">String</span><span class="pln"> getNullableResult</span><span class="pun">(</span><span class="typ">ResultSet</span><span class="pln"> rs</span><span class="pun">,</span><span class="pln"> </span><span class="typ">String</span><span class="pln"> columnName</span><span class="pun">)</span><span class="pln"> </span><span class="kwd">throws</span><span class="pln"> </span><span class="typ">SQLException</span><span class="pln"> </span><span class="pun">{</span><span class="pln">
    </span><span class="kwd">return</span><span class="pln"> rs</span><span class="pun">.</span><span class="pln">getString</span><span class="pun">(</span><span class="pln">columnName</span><span class="pun">);</span><span class="pln">
  </span><span class="pun">}</span><span class="pln">

  </span><span class="lit">@Override</span><span class="pln">
  </span><span class="kwd">public</span><span class="pln"> </span><span class="typ">String</span><span class="pln"> getNullableResult</span><span class="pun">(</span><span class="typ">ResultSet</span><span class="pln"> rs</span><span class="pun">,</span><span class="pln"> </span><span class="kwd">int</span><span class="pln"> columnIndex</span><span class="pun">)</span><span class="pln"> </span><span class="kwd">throws</span><span class="pln"> </span><span class="typ">SQLException</span><span class="pln"> </span><span class="pun">{</span><span class="pln">
    </span><span class="kwd">return</span><span class="pln"> rs</span><span class="pun">.</span><span class="pln">getString</span><span class="pun">(</span><span class="pln">columnIndex</span><span class="pun">);</span><span class="pln">
  </span><span class="pun">}</span><span class="pln">

  </span><span class="lit">@Override</span><span class="pln">
  </span><span class="kwd">public</span><span class="pln"> </span><span class="typ">String</span><span class="pln"> getNullableResult</span><span class="pun">(</span><span class="typ">CallableStatement</span><span class="pln"> cs</span><span class="pun">,</span><span class="pln"> </span><span class="kwd">int</span><span class="pln"> columnIndex</span><span class="pun">)</span><span class="pln"> </span><span class="kwd">throws</span><span class="pln"> </span><span class="typ">SQLException</span><span class="pln"> </span><span class="pun">{</span><span class="pln">
    </span><span class="kwd">return</span><span class="pln"> cs</span><span class="pun">.</span><span class="pln">getString</span><span class="pun">(</span><span class="pln">columnIndex</span><span class="pun">);</span><span class="pln">
  </span><span class="pun">}</span><span class="pln">
</span><span class="pun">}</span></pre></div>

        
<div class="source"><pre class="prettyprint"><span class="com">&lt;!-- mybatis-config.xml --&gt;</span><span class="pln">
</span><span class="tag">&lt;typeHandlers&gt;</span><span class="pln">
  </span><span class="tag">&lt;typeHandler</span><span class="pln"> </span><span class="atn">handler</span><span class="pun">=</span><span class="atv">"org.mybatis.example.ExampleTypeHandler"</span><span class="tag">/&gt;</span><span class="pln">
</span><span class="tag">&lt;/typeHandlers&gt;</span></pre></div>

        
<p>
          使用这个的类型处理器将会覆盖已经存在的处理 Java 的 String 类型属性和 VARCHAR 参数及结果的类型处理器。
          要注意 MyBatis 不会窥探数据库元信息来决定使用哪种类型，所以你必须在参数和结果映射中指明那是 VARCHAR 类型的字段，
          以使其能够绑定到正确的类型处理器上。
          这是因为：MyBatis 直到语句被执行才清楚数据类型。
        </p>
        
<p>
          通过类型处理器的泛型，MyBatis 可以得知该类型处理器处理的 Java 类型，不过这种行为可以通过两种方法改变：
        </p>
        
<ul>
          
<li>在类型处理器的配置元素（typeHandler element）上增加一个 <tt>javaType</tt> 属性（比如：<tt>javaType="String"</tt>）；
          </li>
          
<li>在类型处理器的类上（TypeHandler class）增加一个 <tt>@MappedTypes</tt> 注解来指定与其关联的 Java 类型列表。
            如果在 <tt>javaType</tt> 属性中也同时指定，则注解方式将被忽略。
          </li>
        </ul>

        
<p>可以通过两种方式来指定被关联的 JDBC 类型：</p>
        
<ul>
          
<li>
            在类型处理器的配置元素上增加一个 <tt>javaType</tt> 属性（比如：<tt>javaType="VARCHAR"</tt>）；
          </li>
          
<li>在类型处理器的类上（TypeHandler class）增加一个 <tt>@MappedJdbcTypes</tt> 注解来指定与其关联的 JDBC 类型列表。
            如果在 <tt>javaType</tt> 属性中也同时指定，则注解方式将被忽略。
          </li>
        </ul>

        
<p>最后，可以让 MyBatis 为你查找类型处理器：</p>
        
<div class="source"><pre class="prettyprint"><span class="com">&lt;!-- mybatis-config.xml --&gt;</span><span class="pln">
</span><span class="tag">&lt;typeHandlers&gt;</span><span class="pln">
  </span><span class="tag">&lt;package</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"org.mybatis.example"</span><span class="tag">/&gt;</span><span class="pln">
</span><span class="tag">&lt;/typeHandlers&gt;</span></pre></div>

        
<p>注意在使用自动检索（autodiscovery）功能的时候，只能通过注解方式来指定 JDBC 的类型。</p>
        
<p>你能创建一个泛型类型处理器，它可以处理多于一个类。为达到此目的，
          需要增加一个接收该类作为参数的构造器，这样在构造一个类型处理器的时候 MyBatis 就会传入一个具体的类。</p>

        
<div class="source"><pre class="prettyprint"><span class="com">//GenericTypeHandler.java</span><span class="pln">
</span><span class="kwd">public</span><span class="pln"> </span><span class="kwd">class</span><span class="pln"> </span><span class="typ">GenericTypeHandler</span><span class="pun">&lt;</span><span class="pln">E </span><span class="kwd">extends</span><span class="pln"> </span><span class="typ">MyObject</span><span class="pun">&gt;</span><span class="pln"> </span><span class="kwd">extends</span><span class="pln"> </span><span class="typ">BaseTypeHandler</span><span class="pun">&lt;</span><span class="pln">E</span><span class="pun">&gt;</span><span class="pln"> </span><span class="pun">{</span><span class="pln">

  </span><span class="kwd">private</span><span class="pln"> </span><span class="typ">Class</span><span class="pun">&lt;</span><span class="pln">E</span><span class="pun">&gt;</span><span class="pln"> type</span><span class="pun">;</span><span class="pln">

  </span><span class="kwd">public</span><span class="pln"> </span><span class="typ">GenericTypeHandler</span><span class="pun">(</span><span class="typ">Class</span><span class="pun">&lt;</span><span class="pln">E</span><span class="pun">&gt;</span><span class="pln"> type</span><span class="pun">)</span><span class="pln"> </span><span class="pun">{</span><span class="pln">
    </span><span class="kwd">if</span><span class="pln"> </span><span class="pun">(</span><span class="pln">type </span><span class="pun">==</span><span class="pln"> </span><span class="kwd">null</span><span class="pun">)</span><span class="pln"> </span><span class="kwd">throw</span><span class="pln"> </span><span class="kwd">new</span><span class="pln"> </span><span class="typ">IllegalArgumentException</span><span class="pun">(</span><span class="str">"Type argument cannot be null"</span><span class="pun">);</span><span class="pln">
    </span><span class="kwd">this</span><span class="pun">.</span><span class="pln">type </span><span class="pun">=</span><span class="pln"> type</span><span class="pun">;</span><span class="pln">
  </span><span class="pun">}</span><span class="pln">
  </span><span class="pun">...</span></pre></div>

        
<p><tt>EnumTypeHandler</tt> 和 <tt>EnumOrdinalTypeHandler</tt> 都是泛型类型处理器（generic TypeHandlers），
          我们将会在接下来的部分详细探讨。</p>

      </div>

      
<div class="section">
<h3><a name="a"></a>处理枚举类型</h3>
        
<p>若想映射枚举类型 <tt>Enum</tt>，则需要从 <tt>EnumTypeHandler</tt> 或者 <tt>EnumOrdinalTypeHandler</tt> 中选一个来使用。</p>

        
<p>比如说我们想存储取近似值时用到的舍入模式。默认情况下，MyBatis 会利用 <tt>EnumTypeHandler</tt> 来把 <tt>Enum</tt> 值转换成对应的名字。</p>

        <b>注意 <tt>EnumTypeHandler</tt> 在某种意义上来说是比较特别的，其他的处理器只针对某个特定的类，而它不同，它会处理任意继承了 <tt>Enum</tt> 的类。</b>

        
<p>不过，我们可能不想存储名字，相反我们的 DBA 会坚持使用整形值代码。那也一样轻而易举：
          在配置文件中把 <tt>EnumOrdinalTypeHandler</tt> 加到 <tt>typeHandlers</tt> 中即可，
          这样每个 <tt>RoundingMode</tt> 将通过他们的序数值来映射成对应的整形。
        </p>
        
<div class="source"><pre class="prettyprint"><span class="com">&lt;!-- mybatis-config.xml --&gt;</span><span class="pln">
</span><span class="tag">&lt;typeHandlers&gt;</span><span class="pln">
  </span><span class="tag">&lt;typeHandler</span><span class="pln"> </span><span class="atn">handler</span><span class="pun">=</span><span class="atv">"org.apache.ibatis.type.EnumOrdinalTypeHandler"</span><span class="pln"> </span><span class="atn">javaType</span><span class="pun">=</span><span class="atv">"java.math.RoundingMode"</span><span class="tag">/&gt;</span><span class="pln">
</span><span class="tag">&lt;/typeHandlers&gt;</span></pre></div>
        
<p>但是怎样能将同样的 <tt>Enum</tt> 既映射成字符串又映射成整形呢？</p>
        
<p>
          自动映射器（auto-mapper）会自动地选用 <tt>EnumOrdinalTypeHandler</tt> 来处理，
          所以如果我们想用普通的 <tt>EnumTypeHandler</tt>，就非要为那些 SQL 语句显式地设置要用到的类型处理器不可。
        </p>
        
<p>（下一节才开始讲映射器文件，所以如果是首次阅读该文档，你可能需要先越过这一步，过会再来看。）</p>
        
<div class="source"><pre class="prettyprint"><span class="dec">&lt;!DOCTYPE mapper
    PUBLIC "-//mybatis.org//DTD Mapper 3.0//EN"
    "http://mybatis.org/dtd/mybatis-3-mapper.dtd"&gt;</span><span class="pln">

</span><span class="tag">&lt;mapper</span><span class="pln"> </span><span class="atn">namespace</span><span class="pun">=</span><span class="atv">"org.apache.ibatis.submitted.rounding.Mapper"</span><span class="tag">&gt;</span><span class="pln">
	</span><span class="tag">&lt;resultMap</span><span class="pln"> </span><span class="atn">type</span><span class="pun">=</span><span class="atv">"org.apache.ibatis.submitted.rounding.User"</span><span class="pln"> </span><span class="atn">id</span><span class="pun">=</span><span class="atv">"usermap"</span><span class="tag">&gt;</span><span class="pln">
		</span><span class="tag">&lt;id</span><span class="pln"> </span><span class="atn">column</span><span class="pun">=</span><span class="atv">"id"</span><span class="pln"> </span><span class="atn">property</span><span class="pun">=</span><span class="atv">"id"</span><span class="tag">/&gt;</span><span class="pln">
		</span><span class="tag">&lt;result</span><span class="pln"> </span><span class="atn">column</span><span class="pun">=</span><span class="atv">"name"</span><span class="pln"> </span><span class="atn">property</span><span class="pun">=</span><span class="atv">"name"</span><span class="tag">/&gt;</span><span class="pln">
		</span><span class="tag">&lt;result</span><span class="pln"> </span><span class="atn">column</span><span class="pun">=</span><span class="atv">"funkyNumber"</span><span class="pln"> </span><span class="atn">property</span><span class="pun">=</span><span class="atv">"funkyNumber"</span><span class="tag">/&gt;</span><span class="pln">
		</span><span class="tag">&lt;result</span><span class="pln"> </span><span class="atn">column</span><span class="pun">=</span><span class="atv">"roundingMode"</span><span class="pln"> </span><span class="atn">property</span><span class="pun">=</span><span class="atv">"roundingMode"</span><span class="tag">/&gt;</span><span class="pln">
	</span><span class="tag">&lt;/resultMap&gt;</span><span class="pln">

	</span><span class="tag">&lt;select</span><span class="pln"> </span><span class="atn">id</span><span class="pun">=</span><span class="atv">"getUser"</span><span class="pln"> </span><span class="atn">resultMap</span><span class="pun">=</span><span class="atv">"usermap"</span><span class="tag">&gt;</span><span class="pln">
		select * from users
	</span><span class="tag">&lt;/select&gt;</span><span class="pln">
	</span><span class="tag">&lt;insert</span><span class="pln"> </span><span class="atn">id</span><span class="pun">=</span><span class="atv">"insert"</span><span class="tag">&gt;</span><span class="pln">
	    insert into users (id, name, funkyNumber, roundingMode) values (
	    	#{id}, #{name}, #{funkyNumber}, #{roundingMode}
	    )
	</span><span class="tag">&lt;/insert&gt;</span><span class="pln">
	
	</span><span class="tag">&lt;resultMap</span><span class="pln"> </span><span class="atn">type</span><span class="pun">=</span><span class="atv">"org.apache.ibatis.submitted.rounding.User"</span><span class="pln"> </span><span class="atn">id</span><span class="pun">=</span><span class="atv">"usermap2"</span><span class="tag">&gt;</span><span class="pln">
		</span><span class="tag">&lt;id</span><span class="pln"> </span><span class="atn">column</span><span class="pun">=</span><span class="atv">"id"</span><span class="pln"> </span><span class="atn">property</span><span class="pun">=</span><span class="atv">"id"</span><span class="tag">/&gt;</span><span class="pln">
		</span><span class="tag">&lt;result</span><span class="pln"> </span><span class="atn">column</span><span class="pun">=</span><span class="atv">"name"</span><span class="pln"> </span><span class="atn">property</span><span class="pun">=</span><span class="atv">"name"</span><span class="tag">/&gt;</span><span class="pln">
		</span><span class="tag">&lt;result</span><span class="pln"> </span><span class="atn">column</span><span class="pun">=</span><span class="atv">"funkyNumber"</span><span class="pln"> </span><span class="atn">property</span><span class="pun">=</span><span class="atv">"funkyNumber"</span><span class="tag">/&gt;</span><span class="pln">
		</span><span class="tag">&lt;result</span><span class="pln"> </span><span class="atn">column</span><span class="pun">=</span><span class="atv">"roundingMode"</span><span class="pln"> </span><span class="atn">property</span><span class="pun">=</span><span class="atv">"roundingMode"</span><span class="pln"> </span><span class="atn">typeHandler</span><span class="pun">=</span><span class="atv">"org.apache.ibatis.type.EnumTypeHandler"</span><span class="tag">/&gt;</span><span class="pln">
	</span><span class="tag">&lt;/resultMap&gt;</span><span class="pln">
	</span><span class="tag">&lt;select</span><span class="pln"> </span><span class="atn">id</span><span class="pun">=</span><span class="atv">"getUser2"</span><span class="pln"> </span><span class="atn">resultMap</span><span class="pun">=</span><span class="atv">"usermap2"</span><span class="tag">&gt;</span><span class="pln">
		select * from users2
	</span><span class="tag">&lt;/select&gt;</span><span class="pln">
	</span><span class="tag">&lt;insert</span><span class="pln"> </span><span class="atn">id</span><span class="pun">=</span><span class="atv">"insert2"</span><span class="tag">&gt;</span><span class="pln">
	    insert into users2 (id, name, funkyNumber, roundingMode) values (
	    	#{id}, #{name}, #{funkyNumber}, #{roundingMode, typeHandler=org.apache.ibatis.type.EnumTypeHandler}
	    )
	</span><span class="tag">&lt;/insert&gt;</span><span class="pln">

</span><span class="tag">&lt;/mapper&gt;</span></pre></div>
        
<p>注意，这里的 select 语句强制使用 <tt>resultMap</tt> 来代替 <tt>resultType</tt>。</p>
      </div>

      <a name="objectFactory"></a>
<div class="section" id="objectFactory">
<h3><a name="aobjectFactory"></a>对象工厂（objectFactory）</h3>
        
<p>MyBatis 每次创建结果对象的新实例时，它都会使用一个对象工厂（ObjectFactory）实例来完成。
          默认的对象工厂需要做的仅仅是实例化目标类，要么通过默认构造方法，要么在参数映射存在的时候通过参数构造方法来实例化。
          如果想覆盖对象工厂的默认行为，则可以通过创建自己的对象工厂来实现。比如：</p>
        
<div class="source"><pre class="prettyprint"><span class="com">// ExampleObjectFactory.java</span><span class="pln">
</span><span class="kwd">public</span><span class="pln"> </span><span class="kwd">class</span><span class="pln"> </span><span class="typ">ExampleObjectFactory</span><span class="pln"> </span><span class="kwd">extends</span><span class="pln"> </span><span class="typ">DefaultObjectFactory</span><span class="pln"> </span><span class="pun">{</span><span class="pln">
  </span><span class="kwd">public</span><span class="pln"> </span><span class="typ">Object</span><span class="pln"> create</span><span class="pun">(</span><span class="typ">Class</span><span class="pln"> type</span><span class="pun">)</span><span class="pln"> </span><span class="pun">{</span><span class="pln">
    </span><span class="kwd">return</span><span class="pln"> </span><span class="kwd">super</span><span class="pun">.</span><span class="pln">create</span><span class="pun">(</span><span class="pln">type</span><span class="pun">);</span><span class="pln">
  </span><span class="pun">}</span><span class="pln">
  </span><span class="kwd">public</span><span class="pln"> </span><span class="typ">Object</span><span class="pln"> create</span><span class="pun">(</span><span class="typ">Class</span><span class="pln"> type</span><span class="pun">,</span><span class="pln"> </span><span class="typ">List</span><span class="pun">&lt;</span><span class="typ">Class</span><span class="pun">&gt;</span><span class="pln"> constructorArgTypes</span><span class="pun">,</span><span class="pln"> </span><span class="typ">List</span><span class="pun">&lt;</span><span class="typ">Object</span><span class="pun">&gt;</span><span class="pln"> constructorArgs</span><span class="pun">)</span><span class="pln"> </span><span class="pun">{</span><span class="pln">
    </span><span class="kwd">return</span><span class="pln"> </span><span class="kwd">super</span><span class="pun">.</span><span class="pln">create</span><span class="pun">(</span><span class="pln">type</span><span class="pun">,</span><span class="pln"> constructorArgTypes</span><span class="pun">,</span><span class="pln"> constructorArgs</span><span class="pun">);</span><span class="pln">
  </span><span class="pun">}</span><span class="pln">
  </span><span class="kwd">public</span><span class="pln"> </span><span class="kwd">void</span><span class="pln"> setProperties</span><span class="pun">(</span><span class="typ">Properties</span><span class="pln"> properties</span><span class="pun">)</span><span class="pln"> </span><span class="pun">{</span><span class="pln">
    </span><span class="kwd">super</span><span class="pun">.</span><span class="pln">setProperties</span><span class="pun">(</span><span class="pln">properties</span><span class="pun">);</span><span class="pln">
  </span><span class="pun">}</span><span class="pln">
  </span><span class="kwd">public</span><span class="pln"> </span><span class="pun">&lt;</span><span class="pln">T</span><span class="pun">&gt;</span><span class="pln"> </span><span class="kwd">boolean</span><span class="pln"> isCollection</span><span class="pun">(</span><span class="typ">Class</span><span class="pun">&lt;</span><span class="pln">T</span><span class="pun">&gt;</span><span class="pln"> type</span><span class="pun">)</span><span class="pln"> </span><span class="pun">{</span><span class="pln">
    </span><span class="kwd">return</span><span class="pln"> </span><span class="typ">Collection</span><span class="pun">.</span><span class="kwd">class</span><span class="pun">.</span><span class="pln">isAssignableFrom</span><span class="pun">(</span><span class="pln">type</span><span class="pun">);</span><span class="pln">
  </span><span class="pun">}}</span></pre></div>

        
<div class="source"><pre class="prettyprint"><span class="com">&lt;!-- mybatis-config.xml --&gt;</span><span class="pln">
</span><span class="tag">&lt;objectFactory</span><span class="pln"> </span><span class="atn">type</span><span class="pun">=</span><span class="atv">"org.mybatis.example.ExampleObjectFactory"</span><span class="tag">&gt;</span><span class="pln">
  </span><span class="tag">&lt;property</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"someProperty"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"100"</span><span class="tag">/&gt;</span><span class="pln">
</span><span class="tag">&lt;/objectFactory&gt;</span></pre></div>
        
<p>ObjectFactory 接口很简单，它包含两个创建用的方法，一个是处理默认构造方法的，另外一个是处理带参数的构造方法的。
          最后，setProperties 方法可以被用来配置 ObjectFactory，在初始化你的 ObjectFactory 实例后，
          objectFactory 元素体中定义的属性会被传递给 setProperties 方法。</p>

      </div>
      <a name="plugins"></a>
<div class="section" id="plugins">
<h3><a name="aplugins"></a>插件（plugins）</h3>
        
<p>
          MyBatis 允许你在已映射语句执行过程中的某一点进行拦截调用。默认情况下，MyBatis 允许使用插件来拦截的方法调用包括：
        </p>
        
<ul>
          
<li>
            Executor
            (update, query, flushStatements, commit, rollback,
            getTransaction, close,
            isClosed)
          </li>
          
<li>
            ParameterHandler
            (getParameterObject, setParameters)
          </li>
          
<li>
            ResultSetHandler
            (handleResultSets, handleOutputParameters)
          </li>
          
<li>
            StatementHandler
            (prepare, parameterize, batch, update, query)
          </li>
        </ul>
        
<p>这些类中方法的细节可以通过查看每个方法的签名来发现，或者直接查看 MyBatis 的发行包中的源代码。
          假设你想做的不仅仅是监控方法的调用，那么你应该很好的了解正在重写的方法的行为。
          因为如果在试图修改或重写已有方法的行为的时候，你很可能在破坏 MyBatis 的核心模块。
          这些都是更低层的类和方法，所以使用插件的时候要特别当心。</p>
        
<p>通过 MyBatis 提供的强大机制，使用插件是非常简单的，只需实现 Interceptor 接口，并指定了想要拦截的方法签名即可。</p>

        
<div class="source"><pre class="prettyprint"><span class="com">// ExamplePlugin.java</span><span class="pln">
</span><span class="lit">@Intercepts</span><span class="pun">({</span><span class="lit">@Signature</span><span class="pun">(</span><span class="pln">
  type</span><span class="pun">=</span><span class="pln"> </span><span class="typ">Executor</span><span class="pun">.</span><span class="kwd">class</span><span class="pun">,</span><span class="pln">
  method </span><span class="pun">=</span><span class="pln"> </span><span class="str">"update"</span><span class="pun">,</span><span class="pln">
  args </span><span class="pun">=</span><span class="pln"> </span><span class="pun">{</span><span class="typ">MappedStatement</span><span class="pun">.</span><span class="kwd">class</span><span class="pun">,</span><span class="typ">Object</span><span class="pun">.</span><span class="kwd">class</span><span class="pun">})})</span><span class="pln">
</span><span class="kwd">public</span><span class="pln"> </span><span class="kwd">class</span><span class="pln"> </span><span class="typ">ExamplePlugin</span><span class="pln"> </span><span class="kwd">implements</span><span class="pln"> </span><span class="typ">Interceptor</span><span class="pln"> </span><span class="pun">{</span><span class="pln">
  </span><span class="kwd">public</span><span class="pln"> </span><span class="typ">Object</span><span class="pln"> intercept</span><span class="pun">(</span><span class="typ">Invocation</span><span class="pln"> invocation</span><span class="pun">)</span><span class="pln"> </span><span class="kwd">throws</span><span class="pln"> </span><span class="typ">Throwable</span><span class="pln"> </span><span class="pun">{</span><span class="pln">
    </span><span class="kwd">return</span><span class="pln"> invocation</span><span class="pun">.</span><span class="pln">proceed</span><span class="pun">();</span><span class="pln">
  </span><span class="pun">}</span><span class="pln">
  </span><span class="kwd">public</span><span class="pln"> </span><span class="typ">Object</span><span class="pln"> plugin</span><span class="pun">(</span><span class="typ">Object</span><span class="pln"> target</span><span class="pun">)</span><span class="pln"> </span><span class="pun">{</span><span class="pln">
    </span><span class="kwd">return</span><span class="pln"> </span><span class="typ">Plugin</span><span class="pun">.</span><span class="pln">wrap</span><span class="pun">(</span><span class="pln">target</span><span class="pun">,</span><span class="pln"> </span><span class="kwd">this</span><span class="pun">);</span><span class="pln">
  </span><span class="pun">}</span><span class="pln">
  </span><span class="kwd">public</span><span class="pln"> </span><span class="kwd">void</span><span class="pln"> setProperties</span><span class="pun">(</span><span class="typ">Properties</span><span class="pln"> properties</span><span class="pun">)</span><span class="pln"> </span><span class="pun">{</span><span class="pln">
  </span><span class="pun">}</span><span class="pln">
</span><span class="pun">}</span></pre></div>

        
<div class="source"><pre class="prettyprint"><span class="com">&lt;!-- mybatis-config.xml --&gt;</span><span class="pln">
</span><span class="tag">&lt;plugins&gt;</span><span class="pln">
  </span><span class="tag">&lt;plugin</span><span class="pln"> </span><span class="atn">interceptor</span><span class="pun">=</span><span class="atv">"org.mybatis.example.ExamplePlugin"</span><span class="tag">&gt;</span><span class="pln">
    </span><span class="tag">&lt;property</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"someProperty"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"100"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;/plugin&gt;</span><span class="pln">
</span><span class="tag">&lt;/plugins&gt;</span></pre></div>
        
<p>上面的插件将会拦截在 Executor 实例中所有的 “update” 方法调用，
          这里的 Executor 是负责执行低层映射语句的内部对象。</p>
        
<p><span class="label important">NOTE</span>
          <b>覆盖配置类</b>
        </p>
        
<p>除了用插件来修改 MyBatis 核心行为之外，还可以通过完全覆盖配置类来达到目的。只需继承后覆盖其中的每个方法，再把它传递到 sqlSessionFactoryBuilder.build(myConfig) 方法即可。再次重申，这可能会严重影响 MyBatis 的行为，务请慎之又慎。</p>
      </div>
      <a name="environments"></a>
<div class="section" id="environments">
<h3><a name="aenvironments"></a>配置环境（environments）</h3>
        
<p>MyBatis 可以配置成适应多种环境，这种机制有助于将 SQL 映射应用于多种数据库之中，
          现实情况下有多种理由需要这么做。例如，开发、测试和生产环境需要有不同的配置；或者共享相同 Schema 的多个生产数据库，
          想使用相同的 SQL 映射。许多类似的用例。</p>
        
<p>
          <b>不过要记住：尽管可以配置多个环境，每个 SqlSessionFactory 实例只能选择其一。</b>
        </p>
        
<p>
          所以，如果你想连接两个数据库，就需要创建两个 SqlSessionFactory 实例，每个数据库对应一个。而如果是三个数据库，就需要三个实例，依此类推，记起来很简单：
        </p>
        
<ul>
          
<li>
            <b>每个数据库对应一个 SqlSessionFactory 实例
            </b>
          </li>
        </ul>
        
<p>为了指定创建哪种环境，只要将它作为可选的参数传递给 SqlSessionFactoryBuilder 即可。可以接受环境配置的两个方法签名是：
        </p>

        
<div class="source"><pre class="prettyprint"><span class="typ">SqlSessionFactory</span><span class="pln"> factory </span><span class="pun">=</span><span class="pln"> sqlSessionFactoryBuilder</span><span class="pun">.</span><span class="pln">build</span><span class="pun">(</span><span class="pln">reader</span><span class="pun">,</span><span class="pln"> environment</span><span class="pun">);</span><span class="pln">
</span><span class="typ">SqlSessionFactory</span><span class="pln"> factory </span><span class="pun">=</span><span class="pln"> sqlSessionFactoryBuilder</span><span class="pun">.</span><span class="pln">build</span><span class="pun">(</span><span class="pln">reader</span><span class="pun">,</span><span class="pln"> environment</span><span class="pun">,</span><span class="pln">properties</span><span class="pun">);</span></pre></div>

        
<p>如果忽略了环境参数，那么默认环境将会被加载，如下所示：
        </p>

        
<div class="source"><pre class="prettyprint"><span class="typ">SqlSessionFactory</span><span class="pln"> factory </span><span class="pun">=</span><span class="pln"> sqlSessionFactoryBuilder</span><span class="pun">.</span><span class="pln">build</span><span class="pun">(</span><span class="pln">reader</span><span class="pun">);</span><span class="pln">
</span><span class="typ">SqlSessionFactory</span><span class="pln"> factory </span><span class="pun">=</span><span class="pln"> sqlSessionFactoryBuilder</span><span class="pun">.</span><span class="pln">build</span><span class="pun">(</span><span class="pln">reader</span><span class="pun">,</span><span class="pln">properties</span><span class="pun">);</span></pre></div>

        
<p>环境元素定义了如何配置环境。
        </p>

        
<div class="source"><pre class="prettyprint"><span class="tag">&lt;environments</span><span class="pln"> </span><span class="atn">default</span><span class="pun">=</span><span class="atv">"development"</span><span class="tag">&gt;</span><span class="pln">
  </span><span class="tag">&lt;environment</span><span class="pln"> </span><span class="atn">id</span><span class="pun">=</span><span class="atv">"development"</span><span class="tag">&gt;</span><span class="pln">
    </span><span class="tag">&lt;transactionManager</span><span class="pln"> </span><span class="atn">type</span><span class="pun">=</span><span class="atv">"JDBC"</span><span class="tag">&gt;</span><span class="pln">
      </span><span class="tag">&lt;property</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"..."</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"..."</span><span class="tag">/&gt;</span><span class="pln">
    </span><span class="tag">&lt;/transactionManager&gt;</span><span class="pln">
    </span><span class="tag">&lt;dataSource</span><span class="pln"> </span><span class="atn">type</span><span class="pun">=</span><span class="atv">"POOLED"</span><span class="tag">&gt;</span><span class="pln">
      </span><span class="tag">&lt;property</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"driver"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"${driver}"</span><span class="tag">/&gt;</span><span class="pln">
      </span><span class="tag">&lt;property</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"url"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"${url}"</span><span class="tag">/&gt;</span><span class="pln">
      </span><span class="tag">&lt;property</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"username"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"${username}"</span><span class="tag">/&gt;</span><span class="pln">
      </span><span class="tag">&lt;property</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"password"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"${password}"</span><span class="tag">/&gt;</span><span class="pln">
    </span><span class="tag">&lt;/dataSource&gt;</span><span class="pln">
  </span><span class="tag">&lt;/environment&gt;</span><span class="pln">
</span><span class="tag">&lt;/environments&gt;</span></pre></div>
        
<p>
          注意这里的关键点:
        </p>
        
<ul>
          
<li>
            默认的环境 ID（比如:default=”development”）。
          </li>
          
<li>
            每个 environment 元素定义的环境 ID（比如:id=”development”）。
          </li>
          
<li>
            事务管理器的配置（比如:type=”JDBC”）。
          </li>
          
<li>
            数据源的配置（比如:type=”POOLED”）。
          </li>
        </ul>
        
<p>默认的环境和环境 ID 是一目了然的。随你怎么命名，只要保证默认环境要匹配其中一个环境ID。
        </p>
        
<p>
          <b>事务管理器（transactionManager）</b>
        </p>
        
<p>在 MyBatis 中有两种类型的事务管理器（也就是 type=”[JDBC|MANAGED]”）：</p>
        
<ul>
          
<li>JDBC – 这个配置就是直接使用了 JDBC 的提交和回滚设置，它依赖于从数据源得到的连接来管理事务范围。
          </li>
          
<li>MANAGED – 这个配置几乎没做什么。它从来不提交或回滚一个连接，而是让容器来管理事务的整个生命周期（比如 JEE 应用服务器的上下文）。
            默认情况下它会关闭连接，然而一些容器并不希望这样，因此需要将 closeConnection 属性设置为 false 来阻止它默认的关闭行为。例如:
            
<div class="source"><pre class="prettyprint"><span class="tag">&lt;transactionManager</span><span class="pln"> </span><span class="atn">type</span><span class="pun">=</span><span class="atv">"MANAGED"</span><span class="tag">&gt;</span><span class="pln">
  </span><span class="tag">&lt;property</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"closeConnection"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"false"</span><span class="tag">/&gt;</span><span class="pln">
</span><span class="tag">&lt;/transactionManager&gt;</span></pre></div>
          </li>
        </ul>
        
<p>
          <span class="label important">NOTE</span>如果你正在使用 Spring + MyBatis，则没有必要配置事务管理器，
          因为 Spring 模块会使用自带的管理器来覆盖前面的配置。
        </p>
        
<p>
          这两种事务管理器类型都不需要任何属性。它们不过是类型别名，换句话说，你可以使用 TransactionFactory 接口的实现类的完全限定名或类型别名代替它们。
        </p>
        
<div class="source"><pre class="prettyprint"><span class="kwd">public</span><span class="pln"> </span><span class="kwd">interface</span><span class="pln"> </span><span class="typ">TransactionFactory</span><span class="pln"> </span><span class="pun">{</span><span class="pln">
  </span><span class="kwd">void</span><span class="pln"> setProperties</span><span class="pun">(</span><span class="typ">Properties</span><span class="pln"> props</span><span class="pun">);</span><span class="pln">  
  </span><span class="typ">Transaction</span><span class="pln"> newTransaction</span><span class="pun">(</span><span class="typ">Connection</span><span class="pln"> conn</span><span class="pun">);</span><span class="pln">
  </span><span class="typ">Transaction</span><span class="pln"> newTransaction</span><span class="pun">(</span><span class="typ">DataSource</span><span class="pln"> dataSource</span><span class="pun">,</span><span class="pln"> </span><span class="typ">TransactionIsolationLevel</span><span class="pln"> level</span><span class="pun">,</span><span class="pln"> </span><span class="kwd">boolean</span><span class="pln"> autoCommit</span><span class="pun">);</span><span class="pln">  
</span><span class="pun">}</span></pre></div>
        
<p>任何在 XML 中配置的属性在实例化之后将会被传递给 setProperties() 方法。你也需要创建一个 Transaction 接口的实现类，这个接口也很简单：</p>
        
<div class="source"><pre class="prettyprint"><span class="kwd">public</span><span class="pln"> </span><span class="kwd">interface</span><span class="pln"> </span><span class="typ">Transaction</span><span class="pln"> </span><span class="pun">{</span><span class="pln">
  </span><span class="typ">Connection</span><span class="pln"> getConnection</span><span class="pun">()</span><span class="pln"> </span><span class="kwd">throws</span><span class="pln"> </span><span class="typ">SQLException</span><span class="pun">;</span><span class="pln">
  </span><span class="kwd">void</span><span class="pln"> commit</span><span class="pun">()</span><span class="pln"> </span><span class="kwd">throws</span><span class="pln"> </span><span class="typ">SQLException</span><span class="pun">;</span><span class="pln">
  </span><span class="kwd">void</span><span class="pln"> rollback</span><span class="pun">()</span><span class="pln"> </span><span class="kwd">throws</span><span class="pln"> </span><span class="typ">SQLException</span><span class="pun">;</span><span class="pln">
  </span><span class="kwd">void</span><span class="pln"> close</span><span class="pun">()</span><span class="pln"> </span><span class="kwd">throws</span><span class="pln"> </span><span class="typ">SQLException</span><span class="pun">;</span><span class="pln">
</span><span class="pun">}</span></pre></div>
        
<p>使用这两个接口，你可以完全自定义 MyBatis 对事务的处理。</p>
        
<p>
          <b>数据源（dataSource）</b>
        </p>
        
<p>dataSource 元素使用标准的 JDBC 数据源接口来配置 JDBC 连接对象的资源。</p>
        
<ul>
          
<li>许多 MyBatis 的应用程序将会按示例中的例子来配置数据源。然而它并不是必须的。要知道为了方便使用延迟加载，数据源才是必须的。
          </li>
        </ul>
        
<p>有三种内建的数据源类型（也就是 type=”[UNPOOLED|POOLED|JNDI]”）：</p>
        
<p>
          <b>UNPOOLED</b>– 这个数据源的实现只是每次被请求时打开和关闭连接。虽然一点慢，它对在及时可用连接方面没有性能要求的简单应用程序是一个很好的选择。
          不同的数据库在这方面表现也是不一样的，所以对某些数据库来说使用连接池并不重要，这个配置也是理想的。UNPOOLED 类型的数据源仅仅需要配置以下 5 种属性：</p>
        
<ul>
          
<li><tt>driver</tt> – 这是 JDBC 驱动的 Java 类的完全限定名（并不是JDBC驱动中可能包含的数据源类）。
          </li>
          
<li><tt>url</tt> – 这是数据库的 JDBC URL 地址。
          </li>
          
<li><tt>username</tt> – 登录数据库的用户名。
          </li>
          
<li><tt>password</tt> – 登录数据库的密码。
          </li>
          
<li><tt>defaultTransactionIsolationLevel</tt> – 默认的连接事务隔离级别。
          </li>
        </ul>
        
<p>作为可选项，你也可以传递属性给数据库驱动。要这样做，属性的前缀为“driver.”，例如：
        </p>
        
<ul>
          
<li><tt>driver.encoding=UTF8</tt></li>
        </ul>
        
<p>这将通过DriverManager.getConnection(url,driverProperties)方法传递值为 <tt>UTF8</tt> 的 <tt>encoding</tt> 属性给数据库驱动。
        </p>
        
<p>
          <b>POOLED</b>– 这种数据源的实现利用“池”的概念将 JDBC 连接对象组织起来，避免了创建新的连接实例时所必需的初始化和认证时间。
          这是一种使得并发 Web 应用快速响应请求的流行处理方式。
        </p>
        
<p>除了上述提到 UNPOOLED 下的属性外，会有更多属性用来配置 POOLED 的数据源：</p>
        
<ul>
          
<li><tt>poolMaximumActiveConnections</tt> – 在任意时间可以存在的活动（也就是正在使用）连接数量，默认值：10
          </li>
          
<li><tt>poolMaximumIdleConnections</tt> – 任意时间可能存在的空闲连接数。

          </li>
          
<li><tt>poolMaximumCheckoutTime</tt> – 在被强制返回之前，池中连接被检出（checked out）时间，默认值：20000 毫秒（即 20 秒）
          </li>
          
<li><tt>poolTimeToWait</tt> – 这是一个底层设置，如果获取连接花费的相当长的时间，它会给连接池打印状态日志并重新尝试获取一个连接（避免在误配置的情况下一直安静的失败），默认值：20000 毫秒（即 20 秒）。
          </li>
          
<li><tt>poolPingQuery</tt> – 发送到数据库的侦测查询，用来检验连接是否处在正常工作秩序中并准备接受请求。默认是“NO PING QUERY SET”，这会导致多数数据库驱动失败时带有一个恰当的错误消息。
          </li>
          
<li><tt>poolPingEnabled</tt> – 是否启用侦测查询。若开启，也必须使用一个可执行的 SQL 语句设置 <tt>poolPingQuery</tt> 属性（最好是一个非常快的 SQL），默认值：false。
          </li>
          
<li><tt>poolPingConnectionsNotUsedFor</tt> – 配置 poolPingQuery 的使用频度。这可以被设置成匹配具体的数据库连接超时时间，来避免不必要的侦测，默认值：0（即所有连接每一时刻都被侦测 — 当然仅当 poolPingEnabled 为 true 时适用）。
          </li>
        </ul>
        
<p>
          <b>JNDI</b>– 这个数据源的实现是为了能在如 EJB 或应用服务器这类容器中使用，容器可以集中或在外部配置数据源，然后放置一个 JNDI 上下文的引用。这种数据源配置只需要两个属性：
        </p>
        
<ul>
          
<li><tt>initial_context</tt> – 这个属性用来在 InitialContext 中寻找上下文（即，initialContext.lookup(initial_context)）。这是个可选属性，如果忽略，那么 data_source 属性将会直接从 InitialContext 中寻找。
          </li>
          
<li><tt>data_source</tt> – 这是引用数据源实例位置的上下文的路径。提供了 initial_context 配置时会在其返回的上下文中进行查找，没有提供时则直接在 InitialContext 中查找。
          </li>
        </ul>
        
<p>和其他数据源配置类似，可以通过添加前缀“env.”直接把属性传递给初始上下文。比如：
        </p>
        
<ul>
          
<li><tt>env.encoding=UTF8</tt></li>
        </ul>
        
<p>这就会在初始上下文（InitialContext）实例化时往它的构造方法传递值为 <tt>UTF8</tt> 的 <tt>encoding</tt> 属性。
        </p>

        
<p>
          通过需要实现接口 <tt>org.apache.ibatis.datasource.DataSourceFactory</tt> ， 也可使用任何第三方数据源，：
        </p>

        
<div class="source"><pre class="prettyprint"><span class="kwd">public</span><span class="pln"> </span><span class="kwd">interface</span><span class="pln"> </span><span class="typ">DataSourceFactory</span><span class="pln"> </span><span class="pun">{</span><span class="pln">
  </span><span class="kwd">void</span><span class="pln"> setProperties</span><span class="pun">(</span><span class="typ">Properties</span><span class="pln"> props</span><span class="pun">);</span><span class="pln">
  </span><span class="typ">DataSource</span><span class="pln"> getDataSource</span><span class="pun">();</span><span class="pln">
</span><span class="pun">}</span></pre></div>

        
<p>
          <tt>org.apache.ibatis.datasource.unpooled.UnpooledDataSourceFactory</tt> 可被用作父类来构建新的数据源适配器，比如下面这段插入 C3P0 数据源所必需的代码：
        </p>

        
<div class="source"><pre class="prettyprint"><span class="kwd">import</span><span class="pln"> org</span><span class="pun">.</span><span class="pln">apache</span><span class="pun">.</span><span class="pln">ibatis</span><span class="pun">.</span><span class="pln">datasource</span><span class="pun">.</span><span class="pln">unpooled</span><span class="pun">.</span><span class="typ">UnpooledDataSourceFactory</span><span class="pun">;</span><span class="pln">
</span><span class="kwd">import</span><span class="pln"> com</span><span class="pun">.</span><span class="pln">mchange</span><span class="pun">.</span><span class="pln">v2</span><span class="pun">.</span><span class="pln">c3p0</span><span class="pun">.</span><span class="typ">ComboPooledDataSource</span><span class="pun">;</span><span class="pln">
        
</span><span class="kwd">public</span><span class="pln"> </span><span class="kwd">class</span><span class="pln"> C3P0DataSourceFactory </span><span class="kwd">extends</span><span class="pln"> </span><span class="typ">UnpooledDataSourceFactory</span><span class="pln"> </span><span class="pun">{</span><span class="pln">

  </span><span class="kwd">public</span><span class="pln"> C3P0DataSourceFactory</span><span class="pun">()</span><span class="pln"> </span><span class="pun">{</span><span class="pln">
    </span><span class="kwd">this</span><span class="pun">.</span><span class="pln">dataSource </span><span class="pun">=</span><span class="pln"> </span><span class="kwd">new</span><span class="pln"> </span><span class="typ">ComboPooledDataSource</span><span class="pun">();</span><span class="pln">
  </span><span class="pun">}</span><span class="pln">
</span><span class="pun">}</span></pre></div>

        
<p>为了令其工作，为每个需要 MyBatis 调用的 setter 方法中增加一个属性。下面是一个可以连接至 PostgreSQL 数据库的例子：</p>

        
<div class="source"><pre class="prettyprint"><span class="tag">&lt;dataSource</span><span class="pln"> </span><span class="atn">type</span><span class="pun">=</span><span class="atv">"org.myproject.C3P0DataSourceFactory"</span><span class="tag">&gt;</span><span class="pln">
  </span><span class="tag">&lt;property</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"driver"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"org.postgresql.Driver"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;property</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"url"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"jdbc:postgresql:mydb"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;property</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"username"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"postgres"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;property</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"password"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"root"</span><span class="tag">/&gt;</span><span class="pln">
</span><span class="tag">&lt;/dataSource&gt;</span></pre></div>

      </div>

      <a name="databaseIdProvider"></a>
<div class="section" id="databaseIdProvider">
<h3><a name="databaseIdProvider"></a>databaseIdProvider</h3>
        
<p>MyBatis 可以根据不同的数据库厂商执行不同的语句，这种多厂商的支持是基于映射语句中的 <tt>databaseId</tt> 属性。
          MyBatis 会加载不带 <tt>databaseId</tt> 属性和带有匹配当前数据库 <tt>databaseId</tt> 属性的所有语句。
          如果同时找到带有 <tt>databaseId</tt> 和不带 <tt>databaseId</tt> 的相同语句，则后者会被舍弃。
          为支持多厂商特性只要像下面这样在 mybatis-config.xml 文件中加入 <tt>databaseIdProvider</tt> 即可：</p>

        
<div class="source"><pre class="prettyprint"><span class="tag">&lt;databaseIdProvider</span><span class="pln"> </span><span class="atn">type</span><span class="pun">=</span><span class="atv">"DB_VENDOR"</span><span class="pln"> </span><span class="tag">/&gt;</span></pre></div>

        
<p>这里的 DB_VENDOR 会通过 <tt>DatabaseMetaData#getDatabaseProductName()</tt> 返回的字符串进行设置。
          由于通常情况下这个字符串都非常长而且相同产品的不同版本会返回不同的值，所以最好通过设置属性别名来使其变短，如下：</p>

        
<div class="source"><pre class="prettyprint"><span class="tag">&lt;databaseIdProvider</span><span class="pln"> </span><span class="atn">type</span><span class="pun">=</span><span class="atv">"DB_VENDOR"</span><span class="tag">&gt;</span><span class="pln">
  </span><span class="tag">&lt;property</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"SQL Server"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"sqlserver"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;property</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"DB2"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"db2"</span><span class="tag">/&gt;</span><span class="pln">        
  </span><span class="tag">&lt;property</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"Oracle"</span><span class="pln"> </span><span class="atn">value</span><span class="pun">=</span><span class="atv">"oracle"</span><span class="pln"> </span><span class="tag">/&gt;</span><span class="pln">
</span><span class="tag">&lt;/databaseIdProvider&gt;</span></pre></div>

        
<p>在有 properties 时，DB_VENDOR databaseIdProvider 的将被设置为第一个能匹配数据库产品名称的属性键对应的值，如果没有匹配的属性将会设置为 “null”。
          在这个例子中，如果 <tt>getDatabaseProductName()</tt> 返回“Oracle (DataDirect)”，databaseId 将被设置为“oracle”。</p>

        
<p>你可以通过实现接口 <tt>org.apache.ibatis.mapping.DatabaseIdProvider</tt> 并在 mybatis-config.xml 中注册来构建自己的 DatabaseIdProvider：</p>

        
<div class="source"><pre class="prettyprint"><span class="kwd">public</span><span class="pln"> </span><span class="kwd">interface</span><span class="pln"> </span><span class="typ">DatabaseIdProvider</span><span class="pln"> </span><span class="pun">{</span><span class="pln">
  </span><span class="kwd">void</span><span class="pln"> setProperties</span><span class="pun">(</span><span class="typ">Properties</span><span class="pln"> p</span><span class="pun">);</span><span class="pln">
  </span><span class="typ">String</span><span class="pln"> getDatabaseId</span><span class="pun">(</span><span class="typ">DataSource</span><span class="pln"> dataSource</span><span class="pun">)</span><span class="pln"> </span><span class="kwd">throws</span><span class="pln"> </span><span class="typ">SQLException</span><span class="pun">;</span><span class="pln">
</span><span class="pun">}</span></pre></div>

      </div>

      <a name="mappers"></a>
<div class="section" id="mappers">
<h3><a name="amappers"></a>映射器（mappers）</h3>
        
<p>既然 MyBatis 的行为已经由上述元素配置完了，我们现在就要定义 SQL 映射语句了。但是首先我们需要告诉 MyBatis 到哪里去找到这些语句。
          Java 在自动查找这方面没有提供一个很好的方法，所以最佳的方式是告诉 MyBatis 到哪里去找映射文件。你可以使用相对于类路径的资源引用，
          或完全限定资源定位符（包括 <tt>file:///</tt> 的 URL），或类名和包名等。例如：</p>
        
<div class="source"><pre class="prettyprint"><span class="com">&lt;!-- Using classpath relative resources --&gt;</span><span class="pln">
</span><span class="tag">&lt;mappers&gt;</span><span class="pln">
  </span><span class="tag">&lt;mapper</span><span class="pln"> </span><span class="atn">resource</span><span class="pun">=</span><span class="atv">"org/mybatis/builder/AuthorMapper.xml"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;mapper</span><span class="pln"> </span><span class="atn">resource</span><span class="pun">=</span><span class="atv">"org/mybatis/builder/BlogMapper.xml"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;mapper</span><span class="pln"> </span><span class="atn">resource</span><span class="pun">=</span><span class="atv">"org/mybatis/builder/PostMapper.xml"</span><span class="tag">/&gt;</span><span class="pln">
</span><span class="tag">&lt;/mappers&gt;</span></pre></div>

        
<div class="source"><pre class="prettyprint"><span class="com">&lt;!-- Using url fully qualified paths --&gt;</span><span class="pln">
</span><span class="tag">&lt;mappers&gt;</span><span class="pln">
  </span><span class="tag">&lt;mapper</span><span class="pln"> </span><span class="atn">url</span><span class="pun">=</span><span class="atv">"file:///var/mappers/AuthorMapper.xml"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;mapper</span><span class="pln"> </span><span class="atn">url</span><span class="pun">=</span><span class="atv">"file:///var/mappers/BlogMapper.xml"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;mapper</span><span class="pln"> </span><span class="atn">url</span><span class="pun">=</span><span class="atv">"file:///var/mappers/PostMapper.xml"</span><span class="tag">/&gt;</span><span class="pln">
</span><span class="tag">&lt;/mappers&gt;</span></pre></div>

        
<div class="source"><pre class="prettyprint"><span class="com">&lt;!-- Using mapper interface classes --&gt;</span><span class="pln">
</span><span class="tag">&lt;mappers&gt;</span><span class="pln">
  </span><span class="tag">&lt;mapper</span><span class="pln"> </span><span class="atn">class</span><span class="pun">=</span><span class="atv">"org.mybatis.builder.AuthorMapper"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;mapper</span><span class="pln"> </span><span class="atn">class</span><span class="pun">=</span><span class="atv">"org.mybatis.builder.BlogMapper"</span><span class="tag">/&gt;</span><span class="pln">
  </span><span class="tag">&lt;mapper</span><span class="pln"> </span><span class="atn">class</span><span class="pun">=</span><span class="atv">"org.mybatis.builder.PostMapper"</span><span class="tag">/&gt;</span><span class="pln">
</span><span class="tag">&lt;/mappers&gt;</span></pre></div>

        
<div class="source"><pre class="prettyprint"><span class="com">&lt;!-- Register all interfaces in a package as mappers --&gt;</span><span class="pln">
</span><span class="tag">&lt;mappers&gt;</span><span class="pln">
  </span><span class="tag">&lt;package</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"org.mybatis.builder"</span><span class="tag">/&gt;</span><span class="pln">
</span><span class="tag">&lt;/mappers&gt;</span></pre></div>

        
<p>这些配置会告诉了 MyBatis 去哪里找映射文件，剩下的细节就应该是每个 SQL 映射文件了，也就是接下来我们要讨论的。</p>
      </div>
    </div>
  

                  </div>
            </div>
          </div>

    <hr>

    <footer>
            <div class="container-fluid">
                      <div class="row-fluid">
                                      <p>Copyright ©                    2010–2015
                        <a href="http://www.mybatis.org/">MyBatis.org</a>.
            All rights reserved.      
                    
      </p>
                </div>

        
                </div>
    </footer>
        

</body></html>