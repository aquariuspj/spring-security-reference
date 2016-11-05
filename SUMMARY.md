# 目录


* [I.前言] ()
> 译：山人
### 1. 开始
### 2. 简介
#### 2.1. Spring Security是什么
#### 2.2. 背景
#### 2.3. 版本编号
#### 2.4. 获取Spring Security
##### 2.4.1. Maven
###### Maven的用法
###### Maven仓库
###### Spring Framework Bom
##### 2.4.2. Gradle
###### Gradle仓库
###### Spring 4.0.x and Gradle的使用
##### 2.4.3. 模块说明
###### Core - spring-security-core.jar
###### Remoting - spring-security-remoting.jar
###### Web - spring-security-web.jar
###### Config - spring-security-config.jar
###### LDAP - spring-security-ldap.jar
###### ACL - spring-security-acl.jar
###### CAS - spring-security-cas.jar
###### OpenID - spring-security-openid.jar
###### Test - spring-security-test.jar
##### 2.4.4. 检出源码
#### 3. Spring Security 4.1的新特性
##### 3.1. Java配置改进
##### 3.2. Web Application Security改进
##### 3.3. Authorization改进
##### 3.4. 密码模块改进
##### 3.5. 测试改进
##### 3.6. 通用改进

### 4. 示例与指南(从这开始)
### 5. Java配置
#### 5.1. Hello Web Security Java 配置
##### 5.1.1. AbstractSecurityWebApplicationInitializer
##### 5.1.2. AbstractSecurityWebApplicationInitializer 用于非Spring框架下
##### 5.1.3. AbstractSecurityWebApplicationInitializer 用于Spring MVC
#### 5.2. HttpSecurity
#### 5.3. Java配置 与 表单登陆
#### 5.4. Authorize请求
#### 5.5. 注销操作
##### 5.5.1. LogoutHandler
##### 5.5.2. LogoutSuccessHandler
##### 5.5.3. 更多注销相关的说明
#### 5.6. 权限
##### 5.6.1. 内存中的权限认证
##### 5.6.2. JDBC权限认证
##### 5.6.3. LDAP权限认证
##### 5.6.4. AuthenticationProvider
##### 5.6.5. UserDetailsService
##### 5.6.6. LDAP权限认证
#### 5.7. Multiple HttpSecurity
#### 5.8. Method Security
##### 5.8.1. EnableGlobalMethodSecurity
##### 5.8.2. GlobalMethodSecurityConfiguration
#### 5.9. 提交配置处理对象
### 6. Security Namespace配置
#### 6.1. 简介
##### 6.1.1. Namespace的设计
#### 6.2. 开始Security Namespace配置
##### 6.2.1. web.xml 配置
##### 6.2.2. 最简单的 `<http>` 配置
##### 6.2.3. 表单与基本登陆选项
##### 6.2.3. 设置默认的登陆提交地址
##### 6.2.4. 注销操作
##### 6.2.5. 使用其他的Authentication Providers
##### 6.2.5. 加入密码编码器
#### 6.3. 高级Web功能
##### 6.3.1. Remember-Me Authentication
##### 6.3.2. 添加 HTTP/HTTPS 渠道安全
##### 6.3.3. Session 管理
##### 6.3.3. 超时检查
##### 6.3.3. 并发 Session 控制
##### 6.3.3. 防范Session Fixation Attack
##### 6.3.4. OpenID 支持
##### 6.3.4. Attribute Exchange
##### 6.3.5. Response Headers
##### 6.3.6. 添加自定义 Filters
##### 6.3.6. 设置自定义 AuthenticationEntryPoint
6.4. Method Security
6.4.1. The <global-method-security> Element
Adding Security Pointcuts using protect-pointcut
6.5. The Default AccessDecisionManager
6.5.1. Customizing the AccessDecisionManager
6.6. The Authentication Manager and the Namespace
7. Sample Applications
7.1. Tutorial Sample
7.2. Contacts
7.3. LDAP Sample
7.4. OpenID Sample
7.5. CAS Sample
7.6. JAAS Sample
7.7. Pre-Authentication Sample
8. Spring Security Community
8.1. Issue Tracking
8.2. Becoming Involved
8.3. Further Information