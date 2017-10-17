# 《Node全栈》

## 做Node全栈，你合格么？

自测一下

- 大前端相关
  - 基础
    - css 2 && 3
    - js && es6
    - http/ajax/rest
    - git/svn/issues/pr
    - markdown
  - 前端框架
    - 模块化加载seajs\requirejs\commonjs
    - mvc/mvvm
    - Bootstrap
    - jQuery/Extjs/Dojo/Mootools/Yui
    - Backbone
    - Angular
  - 移动端
    - h5/localstorage/websocket/canvas
    - phonegap/cordova
    - 是否具备编写原生插件能力
    - 优化：fastclick，zepto，iscroll等
    - 框架：sencha、jqmobile、ionicframework等
  - 最新技术
    - react 全家桶
    - vue2 全家桶
    - angular 2/ionic 2
    - react-native/weex
    - electron/nw.js
- 个人成长与技能
  - 通过开源项目学习
  - Git和GitHub
  - VSCode与Node调试
  - 个人成长
  - 有观点的八卦
  - 数据结构与设计模式
- Node
  - Node是什么
  - Node新手入门
  - 异步流程控制
  - 如何编写和发布npm模块
  - 10分钟写脚手架
  - cli工具举例
  - 变态npm
  - Stream
  - Node考证
  - 跨平台
  - Node Web框架
- 测试
  - bdd/tdd
    - qunit
    - mocha/jest/ava/tap/jasmine + karma
    - cucumber
  - spies, stubs and mocks
  - faker/sinon
  - chai/should
  - jenkins/travis
- 工程化
  - precommit
  - 环境变量与开发部署
  - 自己动手写一个web框架
  - 阿里云部署node
  - Node部署
  - 日志采集问题
  - 前端三大框架
  - webpack
  - 学习预编译
  - Typescrpt
  - tpl和vue的异同
  - Livereload
  - 代理：多环境下提高开发效率
  - Bigpipe
  - 优化移动端加载速度
- 你可以做的更多
  - 页面即服务
  - 使用node编写微服务
  - Node源码阅读与调试
  - 运维
  - 内存与性能
  - redis科普
  - mongodb和mongoose
  - addon开发和应对cpu密集任务
- 高效工具
  - coffee/typescript
  - sass/less/stylus
  - postcss/uncss
  - yeoman/slush
  - npm/bower/component
  - gulp/grunt/webpack
  - browserfy
  - hexo/jekyll
  - 工具类
    - 编辑器
    - 调试工具
    - 调优工具
- 案例讨论：如何设计一个高并发的活动系统
- 其他
  - linux/shell
  - 语言node、java、.net、php、python、perl等
  - rdbms/nosql
  - 读过哪些经典的前端相关书？
  - 如何参与开源项目

你合格么？

## Node是什么

- 怎么运行
- ee
- 单线程，不脆弱
- c++（libuv和eventloop）
- py
- js和c++如何互通
- 写法与约定
  - commonjs和实现
  - error-first cb
  - eventemiter
  - 编码风格

## Node新手入门

- 如何学习
- node安装
  - 3m大法+nvs
  - 为什么需要py
  - 开发限制
- 推荐的书
- 基本技能
- 参见《写开源项目》一章

## 通过开源项目学习

- 迷茫时学习Node.js最好的方法：每日精进，每天学10个npm
- 如何学
- 前端构建等等
- Study-For-StuQ

## Git和GitHub

git

- 和svn对比
- 无server
- 分布式
- 分支
- git工作流模型
- 开发和提pr流程
- cherrypick
- gitlab
- githook
- pr

github

- ghpages
- 博客
- gitbook
- md和编译
- tocmd做法

## VSCode与Node调试

- vscode用法和快捷键
- 对比各种编辑器
- 各种调试
  - 单个文件调试
  - 固定文件调试
  - 跨进程调试
  - 远程调试
- debug和inspect协议
- npm xx
- githook
- 单元测试插件
- 自己写一个vscode插件

## 异步流程控制

- 学习要点：promise和async函数
- promise并行如何写：all和race，比如获取多个接口的数据
- sleep写法
- async函数和async.js不是一个东西
- 异常处理

## 如何编写和发布npm模块

- 创建git项目
- 写点代码
- 发布
- better 发布
- 搭建私有源
- 解释registry的关系

## 10分钟写脚手架

1. 初始化模块
1. cli二进制模块
1. 模板引擎使用
1. 解析cli参数和路径
1. npm发布

## cli工具举例

- 入门见《10分钟写脚手架》
- kp
- je

## precommit

- husky
- standardjs
- precommit = standard * && npm test
- 测试，见test部分

## test

- tdd/bdd
- 模块
  - mocha、ava、jest、tape
  - chai
  - sinon 三个概念（spies，stub、mock）
  - supertest以及superagent原理
  - zombie
- 例子
  - mocha、express和supertest做接口测试
  - ava、koa和supertest做接口测试
  - fixture概念
  - badge
  - travis（多版本自动化）和jenkins
  - 测试覆盖率
- 其他
  - factory—girl
  - faker
  - Mock.js随机生成数据

## 变态npm

- 黑洞
- 生态
- left-pad事件
- shell写npm模块（适合运维和其他语言爱好者）
- 配置（见precommit）
- npm run xx
- -D和-S区别
- yarn

## 环境变量与开发部署

- debug
- NODE_ENV
  - dev
  - test
  - staging
  - product
- webpack的配置

## Stream

- pipe
- http
- gulp
- request.end
- ee

## 数据结构与设计模式

- 基本array
- LRU
- trie
- radix-tree

各种设计模式举几个例

## Node web框架

- koa与express
- 中间件
- 路由（自动挂载路由）
- 视图
- 健壮性
- koa-compose

## 自己动手写一个web框架

- express/koa
- thinkjs
- slet

## 阿里云部署node

- 买
- 域名
- 访问
- 准备
- cd

## Node部署

- 为什么Node单线程单进程并不脆弱？
- 4种启动方式
  - node
  - nodemon
  - forever
  - pm2
- pm2用法
  - 基础管理、启动、查看状态、日志、监控等
  - 远程部署多台机器（如果复杂的，推荐使用saltstack，后面有专门的部署章节）
- 部署模式思考
  - 8核8g的机器怎么部署
  - 1核1g
  - 防止雪崩
  - 部署实例和cpu核数的关系
  - 为什么4核上部署12个应用，cpu使用率会非常高

## 日志采集问题

- elk、splank
- sentry
- h5=》采集=》grafana =》d3可时候会
- 收集信息，mq，然后入库

## 页面即服务

- 好处，对比单体应用
- 成本优势，比如实习生能否搞定
- 具体做法

## 使用node编写微服务

- rpc
  - dnode
  - senaca
  - grpc
- tcp（粘包）配置同步
- global

## Node源码阅读与调试

- clion
- 调试

## 运维

- 简单的纯node多机器pm2
- 复杂的saltstack
- devops

## 内存与性能

- benchmark和压测
- 4个工具
  - v8-profiler 对v8堆内存抓取快照和对cpu进行分析
  - node-heapdump 对v8堆内存抓取快照，事后分析+chrome分析
  - node-mtrace 分析堆栈使用
  - node-memwatch 监听垃圾回收情况
- tracegc和prof+压测
- 简易实现easy-monitor
- 终极方案dtrace调优、火焰图
- 偷懒做法：apm比如alinode、听云等

## redis科普

- 五中数据结构
- 读写分离
- node选型：ioredis和源码
- 美图弹幕系统分析
- 做队列
- pubsub
- 存session
- 限流

## mongodb和mongoose

不需要运维就可以有很好的性能

- 事务
- 启动mh
- mr
- expire
- 部署
  - 副本集
  - sharding

mongoose

- mvc中m作用
- 各种技巧

## 案例讨论：如何设计一个高并发的活动系统

- 流程
- 生成html（解析psd，坐标和图层）
- mq、cache
- 计算机器和限流量
- 配置中心tcp
- 限流
  - redis
  - global
  - incr与blpop
  - 中间件写法
   
## 你可以做的更多

- sql的故事
- psd转html
- node做运维
  - shipit
  - gulp
  - npm #! /bin/bash
- gulp-ftp
- 静态化：写-》压缩-》cdn-》一键发布
- 爬虫
- 区块链：ipfs举例
- 通过http和rpc等解耦
  - kafka提供http，美图的弹幕
  - rabbitmq
  - node-redis-java
  
## addon开发和应对cpu密集任务

- nan
- n-api
- node-java
- rust
- napajs

## 前端三大框架

- 点评前端三大框架
- 基础、样例
- 和node关系
- 使用node做api后端
- 学习构建和定制过程
- 参见（通过开源项目学习）

## webpack

- 模块化，按需加载
- 模块，加载器和打包器
- 打包过程
- 浏览器加载过程
- code spit
  - 通过react动态路由来分泡
- tree shaking
- 合并公共项目（react + react-router + redux 打成一个包）

## 学习预编译

- 单个文件编译
- 静态网站高级写法：moddileman类似的写法
- 模板的好处
- 10行代码写一个
- express里的conect-xxx的中间件
- ykit做法
- gulp做法
- webpack做法

## Typescrpt

- js需要类型系统
- 各种写法继承
- ts-check
- typeorm
- 注解
- 字节写一个web框架

## tpl和vue的异同

- 直接写html很好，但太low了
- tpl
- vue
- 布局等实现
- 脚手架：基于tpl和vue的crud
- ssr

## Livereload

- 与nodemon的异同
- webpack dev和hot插件
- brower-sync
- chrome插件
- node和vue同构时，启动守护的，完成自动触发，类似于pm2机制
- sockit.io同步处理，比如hade源码

## 代理：多环境下提高开发效率

- 代理原理，http和https、中间人等
- jsonp跨域
- nginx转接口
- hiproxy

## Bigpipe

麻雀虽小五脏俱全

- 原理和例子
- bigview
  - learn
  - yarn
  - es6语法
- 浏览器渲染原理

## 优化移动端加载速度

- App内置httpserver
- webview注入
- macaca
- pwa和ssr

## 个人成长

- 精力
- 时间
- 目标：技术or管理

## 有观点的八卦

- node之父已死
- uber换go
- left-pad
- 黑npm是黑洞
- 版本帝
- iojs到aya分裂
- 回调地狱

## Node考证

待定

- 考证
- 考题
- 重点

## 跨平台

- pc：nw.js和electron
- 移动端：cordova和ionic
- web


## 如果想提问，请加入《狼叔爱Node》群，有问必答

部分问题[回复](q.md)

> 互相尊重，坦诚，不说没用的

《狼叔爱Node》是我在小密圈上创建的私密沟通群

- 主要内容涵盖Node、全栈、开源三大部分
- 偶尔发点感想、备忘、笔记类的，会有不想公开的哦
- 方便沟通，可以直接提问，应急支援，解答疑问、点评
- 更有justjavac、fundon、老雷，nswbmw、alsotang等大神陪伴

会员策略

年前价格199元/年，年后价格299元/年

![Connect](connect.jpg)