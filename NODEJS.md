<h1 align="center">nodejs汇总</h1>


持续更新中……


## 目录

* [nodejs](#nodejs)
* [Puppeteer](#Puppeteer)
* [爬虫](#爬虫)
* [koa](#koa)
* [fastify](#fastify)
* [eggjs](#eggjs)
* [GraphQL](#GraphQL)
* [数据存储](#数据存储)
* [docker](#docker)
* [java](#java)
* [其他](#其他)


## nodejs
### 官网
- 英文官网  https://nodejs.org/en/
- 中文官网  http://nodejs.cn/
* [nvm](https://github.com/nvm-sh/nvm)(nodejs管理工具)
* [nvm-windows](https://github.com/coreybutler/nvm-windows)(nodejs管理工具)
* [n](https://github.com/tj/n)(nodejs管理工具)


### 参考资料
- 七天学会NodeJS文档  http://nqdeng.github.io/7-days-nodejs/
- node面试题  https://github.com/ElemeFE/node-interview
- Node应用内存泄漏分析方法论与实战 https://github.com/alibaba/beidou/blob/master/packages/beidou-docs/articles/node-memory-leak.md
- nodejs最佳实践   https://github.com/i0natan/nodebestpractices/blob/master/README.chinese.md
* [深入理解Node.js 中的进程与线程](https://juejin.im/post/5d43017be51d4561f40adcf9)
* [《Node.js 调试指南》](https://github.com/nswbmw/node-in-debugging)
* [Node.js技术栈](https://github.com/Q-Angelo/Nodejs-Roadmap)
* [Node.JS 应用最佳实践：日志](https://zhuanlan.zhihu.com/p/81989446)
* [使用verdaccio搭建npm私有仓库](https://www.jianshu.com/p/16b0a2f124fb)
* [npm包管理和配置npm的nexus私服](https://www.jianshu.com/p/bc71053e644c)
* [抛弃jenkins，使用node从零搭建自动化部署管理平台](https://mp.weixin.qq.com/s/UVcZh0QE8g52Iv5UB_61tQ)
* [每天都在用 SSH，你知道 SSH 的原理吗？](https://juejin.im/post/5e4e30dfe51d4527107c8835)
* [对node工程进行压力测试与性能分析](https://juejin.im/post/5b827cbbe51d4538c021f2da)
* [使用Node.js构建API网关](https://blog.risingstack.com/building-an-api-gateway-using-nodejs/)


### 开源项目
* [Node.js 实现远程桌面监控](https://juejin.im/post/5d18d4c36fb9a07ecb0bbe7b)
* [Egg + React 实战日记本（万字长文，望收藏点赞）](https://juejin.im/post/5e2a6215e51d454d50351f9b)


### 微服务
* [moleculerjs](https://github.com/moleculerjs/moleculer) (https://img.shields.io/github/stars/moleculerjs/moleculer.svg)
* [nodejs 微服务 用什么框架](https://cnodejs.org/topic/5895870f800323b708f7bbf4)
* [seneca](https://github.com/senecajs/seneca)  (https://img.shields.io/github/stars/senecajs/seneca.svg)
* [microless](https://github.com/Authing/microless) (https://img.shields.io/github/stars/Authing/microless.svg)
* [感觉Nodejs社区，在微服务架构层面的软件太少了啊！有没有类似于Spring Cloud这种的？](https://cnodejs.org/topic/59f6e8ff688da99d4fa91e11)
* [利用dubbo打造真正的nodejs端的微服务体系](https://juejin.im/post/5d60fec06fb9a06b19734382)
* [risingstack](https://risingstack.com/)(用nodejs搭建微服务的公司)
* [5 分钟搭建 Node.js 微服务原型](https://juejin.im/post/5e60aec0e51d45271d5d4382)


### 常用库
* [winston](https://github.com/winstonjs/winston)(A logger for just about everything)
* [node-bunyan](https://github.com/trentm/node-bunyan)(a simple and fast JSON logging module for node.js services)
* [gh-pages](https://github.com/tschaub/gh-pages)
* [中华人民共和国行政区划代码](https://www.npmjs.com/package/province-city-china)
* [pinyin](https://github.com/hotoo/pinyin)


## npm
* [npm scripts 使用指南](http://www.ruanyifeng.com/blog/2016/10/npm_scripts.html)


## Puppeteer
* [无头浏览器 Puppeteer 初探](https://juejin.im/post/59e5a86c51882578bf185dba)


## 爬虫
* [爬虫被封怎么办？用Node构建一个私人IP代理池](https://juejin.im/post/5cc45db8f265da037129a5f2)
* [awesome-spider](https://github.com/facert/awesome-spider)
* [crawlab](https://github.com/crawlab-team/crawlab)(基于Golang的分布式爬虫管理平台)
* [某团外卖H5版本爬虫开发和JS逆向过程](https://zhuanlan.zhihu.com/p/81773389)
* [GitHub 上有哪些优秀的 Python 爬虫项目？](https://www.zhihu.com/question/58151047/answer/859783454)


### 开源项目
* [spider-flow](https://gitee.com/jmxd/spider-flow)(新一代爬虫平台，以图形化方式定义爬虫流程，不写代码即可完成爬虫)

## koa
* [koa](https://github.com/koajs/koa)
* [koa文档](https://koajs.com/)
* [koa中文文档](https://demopark.github.io/koa-docs-Zh-CN/)
* [Koa2进阶学习笔记](https://github.com/chenshenhai/koa2-note)
* [koa example](https://github.com/koajs/examples)
* [koa+jwt实现token验证与刷新](https://segmentfault.com/a/1190000019338195)


## fastify
* [fastify](https://github.com/fastify/fastify)

## eggjs

* [一文看懂 Eggjs-基础全面讲解（下）](https://juejin.im/post/5d37ba17f265da1bc94f2f97)

### 常用工具库
* [cron-parser](https://www.npmjs.com/package/cron-parser)(用于定时任务)
    * 文档 https://segmentfault.com/a/1190000020403852
* [egg-valparams](https://www.npmjs.com/package/egg-valparams)(参数校验)
    * 文档 https://github.com/D780/valparams/blob/HEAD/doc/api.md
* [egg-cors]()(解决跨域)



### 文章
* [如何更优雅的使用egg的日志体系？](https://github.com/eggjs/egg/issues/2006)
* [基于Egg框架的日志链路追踪实践分享](https://juejin.im/post/5cf5f78951882574ce0133f3)

## 脚手架开发

### node内置
* path
* util.promisify
* child_process.execSync 

### 常用库

#### 必用
* babel-cli/babel-env: 语法转换
* semver: 提供版本比较
* minimist: 解析用户命令，将 process.argv 解析成对象
* commander: 命令行工具
* inquirer: 交互式命令行工具
* ora: 显示loading动画
* chalk: 修改控制台输出内容样式
* easy-table: 类似 console.table，输出漂亮的表格
* log-symbols: 显示出 √ 或 × 等的图标
* figlet: console.log出一个漂亮的大logo
* consolidate：Template engine consolidation library for node.js 。
* execa：更友好的child_process.exec。
* arg: 类似commander，arg is yet another command line option parser.


#### 经常用
* handlebars：一个 javascript 语以模版库。
* cross-spawn: 跨平台的child_process (跨 Windows/Mac)
* fs-extra: 对 fs 库的扩展，支持 promise
* import-from: 类似 require，但支持指定目录，让你可以跨工程目录进行 require，比如全局包想引用工程路径下的内容
* resolve-from: 同上，只不过是 require.resolve
* yeoman-environment: 【核心】用于执行一个「模板插件包」，后文详细描述
* yeoman-generator: 
* open: 跨平台打开 app，比如调试的时候开打 chrome
* download-git-repo: 用来下载远程模板
* ini: 格式转换
* metalsmith；An extremely simple, pluggable static site generator。
* slash: 把windows反斜线路径转换为斜线路径，foo\\bar ➔ foo/bar


#### 跨平台
* osenv: 跨平台的系统信息
* mkdirp 跨平台的创建文件夹
* cross-spawn: 跨平台的child_process

## GraphQL
### 官方
* [graphql-js github](https://github.com/graphql/graphql-js/)
* [express-graphql](https://github.com/graphql/express-graphql)
* [apollo-server](https://github.com/apollographql/apollo-server)
* [react-apollo](https://github.com/apollographql/react-apollo)
* [GraphQL中文](https://graphql.cn)
* [apollo](https://github.com/apollographql/apollo)(文档：https://www.apollographql.com/docs/)

### 开源项目
* [graphpack](https://github.com/glennreyes/graphpack)(零配置graphql服务器)
* [rejoiner](https://github.com/google/rejoiner)(Uniform GraphQL schema from gRPC microservices)
* [gql-generator](https://github.com/timqian/gql-generator)(通过schema生成query)

### 文章
* [前端er了解GraphQL，看这篇就够了](https://juejin.im/post/5ca1b7be51882543ea4b7f27)
* [GraphQL 入门看这篇就够了](https://mp.weixin.qq.com/s/cpPN5o_mbti9H8e-kZAY5Q)
* [awesome-graphql](https://github.com/chentsulin/awesome-graphql)
* [GraphQL 搭配 Koa 最佳入门实践](https://segmentfault.com/a/1190000012720317)
* [GraphQL 为何没有火起来?](https://www.zhihu.com/question/38596306)
* [全栈 React + GraphQL 教程（一）](https://www.zcfy.cc/article/full-stack-react-graphql-tutorial-apollo-graphql-4341.html?t=new)


## 数据存储

### level
* [level](https://github.com/Level/level)(Fast & simple storage)
* [then-levelup]()(level promisify)


### mysql
* [官网](https://www.mysql.com/)
* [mysqljs](https://github.com/mysqljs/mysql)
* [21分钟MySQL基础入门](https://segmentfault.com/a/1190000006876419)
* [2019-01-11亲测Navicat Premium for Mac破解](https://www.jianshu.com/p/4e93b48f9f63)
* [MySQL命令，一篇文章替你全部搞定](https://juejin.im/post/5ae55861f265da0ba062ec71)
* [bookshelf](https://github.com/bookshelf/bookshelf)(A simple Node.js ORM for PostgreSQL, MySQL and SQLite3 built on top of Knex.js)
* [Mysql常用命令行大全](https://www.cnblogs.com/bluealine/p/7832219.html)
* [MySQL5.7 常用命令](https://blog.csdn.net/m0_37774790/article/details/81007192)
* [sequelize](https://github.com/sequelize/sequelize)(An easy-to-use multi SQL dialect ORM for Node.js )
* [sequelize官网](https://sequelize.org/master/)
* [Sequelize Docs 中文版](https://github.com/demopark/sequelize-docs-Zh-CN/tree/master)


#### 客户端
* [navicat-premium](https://www.navicat.com.cn/download/navicat-premium)
* [mac破解版navicat 安装直接即可](https://www.52pojie.cn/thread-957406-1-1.html)

#### 常见问题
* [mysql8.0版本 报错：Error: ER_NOT_SUPPORTED_AUTH_MODE: Client does not support authentication protocol...](https://www.jianshu.com/p/c8eb6d2471f8)
* [解决2003 - 2003 - Can't connect to MySQL server on '127.0.0.1'(61 "Connection refused")](https://blog.csdn.net/zeal9s/article/details/98873165)
* [Mac mysql忘记密码](https://segmentfault.com/a/1190000020679306)
* [出现connect ECONNREFUSED 127.0.0.1:3306报错的解决方法](http://blog.ttionya.com/article-1709.html)


### mongodb
* [mongoose github](https://github.com/Automattic/mongoose)
* [mongoose中文网](http://www.mongoosejs.net)
* [MongoDB中文](https://www.mongodb.org.cn/tutorial/)
* [MongoDB中文文档](http://www.mongoing.com/docs/)
* [MongoDB 教程 | 菜鸟教程](https://www.runoob.com/mongodb/mongodb-tutorial.html)

### cassandra
* [cassandra教程](https://www.w3cschool.cn/cassandra/)(分布式数据库)(java)

### redis

* [Redis可视化工具](https://www.jianshu.com/p/721c3762a777)
* [Redis 入门](https://juejin.im/post/5b4dd82ee51d451925629622)
* [Redis 命令参考](http://doc.redisfans.com/index.html)
* [基于prometheus+grafana体系监控redis缓存服务](https://www.toutiao.com/a6740202216994374147)
* [Redis优化高并发下的秒杀功能](https://www.toutiao.com/a6755813844909556237)


#### 工具
* RedisDesktopManager
* FastRedis
* [AnotherRedisDesktopManager](https://github.com/qishibo/AnotherRedisDesktopManager)
### 图数据库

* [neo4j](https://github.com/neo4j/neo4j)
* [hive](https://github.com/apache/hive)

#### 文章
* [《一起学图数据库》之一：图数据库介绍](https://zhuanlan.zhihu.com/p/32857155)

### ELK
* [elasticsearch GitHub](https://github.com/elastic/elasticsearch)
* [elastic官网](https://www.elastic.co/cn/#)
* [elastic官方文档](https://www.elastic.co/guide/en/elasticsearch/reference/6.0/getting-started.html)
* [elk入门](https://segmentfault.com/a/1190000016665082)
* [elastic中文社区](https://elasticsearch.cn/)
* [大搜车NodeJS日志规范化与分析监控](http://f2e.souche.com/blog/ri-zhi-gui-fan-hua-yu-fen-xi-jian-kong/)
* [Node 框架接入 ELK 实践总结](https://juejin.im/post/5bf4c7ff5188250e8601d432)


#### logstash

* [logstash下载](https://www.elastic.co/cn/downloads/logstash)

#### ElasticSearch
* [手把手教你搭建一个 Elasticsearch 集群](https://juejin.im/post/5bad9520f265da0afe62ed95)
* [终于有人把Elasticsearch原理讲透了！](http://developer.51cto.com/art/201904/594615.htm)
* [elasticsearch reference](https://www.elastic.co/guide/en/elasticsearch/reference/current/index.html)
* [elasticsearch中文文档](https://www.elastic.co/guide/cn/elasticsearch/guide/current/index.html)
* [Elasticsearch 权威指南（中文版）](https://es.xiaoleilu.com/index.html)
* [ElasticSearch学习文档](https://juejin.im/post/5d82e5955188251b764b76ff)
* [全文搜索引擎 Elasticsearch 入门教程](http://www.ruanyifeng.com/blog/2017/08/elasticsearch.html)
* [Elasticsearch就这么简单](https://juejin.im/post/5ab4496e518825556d0e0713)
* [Elasticsearch学习笔记](https://juejin.im/post/5b9292b75188255c6b64eee5)
* [Elasticsearch 入门使用](https://juejin.im/post/58d1d7530ce4630057e6053a)
* [一文上手 Elasticsearch常用可视化管理工具](https://juejin.im/post/5bd797ce6fb9a05cd7778f8d)
* [ElasticSearch中"distinct","count"和"group by"的实现](https://www.jianshu.com/p/62bed9cc8349)
* [[转]23个最有用的Elasticsearch检索技巧](https://juejin.im/post/5b7fe4a46fb9a019d92469a9)
* [看完这篇还不会Elasticsearch，我跪搓衣板，90%程序员已收藏](https://www.jianshu.com/p/ae9271012b7b)
* [Elasticsearch聚合——Pipeline Aggregations ](https://my.oschina.net/bingzhong/blog/1975879)
* [ES Pipeline Aggregation(管道聚合)](https://www.jianshu.com/p/eb0645b9f620)

##### 插件
* [opendistro](https://opendistro.github.io/for-elasticsearch-docs/)(监控报警)
* [elastalert](https://github.com/Yelp/elastalert)(监控报警)


##### 遇到的问题
* The bulk request must be terminated by a newline [\\n]
https://www.jianshu.com/p/1c8ba834e15c?utm_source=oschina-app

* 关于ElasticSearch的聚类时出现fielddata=true问题
加```.keyword```

* GET查询，加.keyword与不加.keyword的区别是什么，为什么没有结果
https://segmentfault.com/q/1010000017312707


* ElasticSearch如何先聚合后过滤？
https://elasticsearch.cn/question/656

#### kafka
* [Kibana Guide](https://www.elastic.co/guide/en/kibana/7.4/index.html)
* [震惊了！原来这才是kafka！](https://www.jianshu.com/p/d3e963ff8b70)
* [kafka中文教程](https://www.orchome.com/kafka/index)


## 中台
* [漫画：什么是中台？](https://juejin.im/post/5d995f82f265da5ba308389d)

## docker
* [docker官网](https://docs.docker.com/)(英)
* [Docker Cheat Sheet](https://github.com/wsargent/docker-cheat-sheet/blob/master/zh-cn/README.md)
* [写给前端工程师看的Docker教程-基础篇](https://zhuanlan.zhihu.com/p/84891860)
* [Docker 教程](https://www.runoob.com/docker/docker-tutorial.html)
* [Docker中文文档](http://www.dockerinfo.net/document)
* [Docker中文社区](http://www.docker.org.cn/)
* [awesome-docker](https://github.com/veggiemonk/awesome-docker)(英)
* [awesome-dockercompose](https://github.com/bboysoulcn/awesome-dockercompose)
* [Chef Cookbook for Docker ](https://github.com/chef-cookbooks/docker)(英)
* [docker hub](https://hub.docker.com/)
* [docker-windows](https://docker.com/docker-windows)
### 常用命令
```
docker container ls -a     #获得容器信息
docker container ls -a  -p   #获得容器id
docker container stop <container ID>  #停止运行容器
docker container rm  <container ID> #删除容器
docker container stop $(docker container ls -a -q)  #批量停止容器
docker container rm $(docker container ls -a -q)    #批量删除容器


# 停止和删除Exited的docker实例
docker ps -a | grep "Exited" | awk '{print $1 }'|xargs docker stop
docker ps -a | grep "Exited" | awk '{print $1 }'|xargs docker rm
# 删除none的镜像
docker images|grep none|awk '{print $3 }'|xargs docker rmi

# 删除所有未被容器使用的镜像
docker image prune -a

```

### 文章
* [写给前端的Docker实战教程](https://juejin.im/post/5d8440ebe51d4561eb0b2751)
* [[手把手系列之]Docker 部署 vue 项目](https://juejin.im/post/5cce4b1cf265da0373719819)
* [[手把手系列之]docker 部署node+mongodb项目](https://juejin.im/post/5db7b549f265da4d556cecbc)
* [jenkins+docker+nodejs项目的自动部署环境](https://my.oschina.net/gaochunzhang/blog/2246923)
* [docker安装jenkins](https://github.com/jenkinsci/docker/blob/master/README.md)
* [从零搭建docker+jenkins+node.js自动化部署环境](https://juejin.im/post/5b8ddb70e51d45389153f288)
* [jenkins+docker+nodejs](https://www.codercto.com/a/72878.html)
* [Docker部署 nodejs项目](https://www.jianshu.com/p/ab76ba86eafc)
* [jenkins自动化部署vue](https://blog.csdn.net/jonsonler/article/details/81317352)
* [Jenkins一键部署vue项目](https://blog.csdn.net/qq_34479912/article/details/82417869)
* [使用 Jenkins 自动部署 Docker 服务（一、Jenkins 搭建篇）](https://blog.csdn.net/z497896143/article/details/81703016)
* [终于有人把 Docker 讲清楚了，万字详解](https://www.toutiao.com/a6753476749108969998)
* [全栈之路：从零搭建docker+jenkins+node.js自动化部署环境](https://www.toutiao.com/a6740132922214334979)
* [为什么你不必害怕 Kubernetes](https://www.toutiao.com/a6755667559334281742)
* [我花了10个小时，写出了这篇K8S架构解析](https://www.toutiao.com/a6759071724785893891)

## jenkins
* [让自动化工作流解放你的双手](https://juejin.im/post/5d3fb5046fb9a06b0935f47d)
* [jenkins插件](http://updates.jenkins-ci.org/download/plugins/)
* [构建gitlab、Jenkins、harbor、kubernetes的DevOps持续集成](https://learning.snssdk.com/feoffline/toutiao_wallet_bundles/toutiao_learning_wap/online/article.html?item_id=6751538964366098958&app_name=news_article)
## linux
* [Linux 教程](https://www.runoob.com/linux/linux-vim.html)
* [Mac使用ssh公钥登录Linux](https://segmentfault.com/a/1190000015369885)

## java
* [电商系统](https://github.com/macrozheng/mall)(包括前台商城系统及后台管理系统)

## nginx
* [前端想要了解的Nginx](https://juejin.im/post/5cae9de95188251ae2324ec3)
* [一文弄懂Nginx的location匹配](https://juejin.im/post/5cbe89b6f265da0373718707)
* [nginx 这一篇就够了](https://juejin.im/post/5d81906c518825300a3ec7ca)

## 其他
* [k8s日志收集实战](https://juejin.im/post/5b6eaef96fb9a04fa25a0d37)
* [[译] Kubernetes 儿童插图指南](https://juejin.im/post/5d1b2a656fb9a07edc0b7058)
* [不要用 JWT 来做 Web 应用的会话管理](https://juejin.im/entry/59748def518825592c4f9ac0)
* [万网云解析设置二级域名解析到同IP不同端口](https://jingyan.baidu.com/article/eb9f7b6d8a02a5869364e827.html)
* [怎样用 Bash 编程：语法和工具](https://www.toutiao.com/a6756741451649909259)

## 运维部署

* [jhipster](https://github.com/jhipster/generator-jhipster)(JHipster 是一个创建、开发、部署 Spring Boot + Angular/React 架构的 Web 应用或 Spring 微服务应用的开发平台。)
* [jhipster官网](https://www.jhipster.tech)
* [jhipster中文](https://www.jhipster-cn.tech/)
