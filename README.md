# awesome npm

__Table of Contents__  *generated with *[DocToc](https://github.com/thlorenz/doctoc)

* [0. 概述](#0-%E6%A6%82%E8%BF%B0)
* [1. 后端开发](#1-%E5%90%8E%E7%AB%AF%E5%BC%80%E5%8F%91)
    * [1.1 HTTP](#11-http)
    * [1.2 框架](#12-%E6%A1%86%E6%9E%B6)
    * [1.3 模板引擎](#13-%E6%A8%A1%E6%9D%BF%E5%BC%95%E6%93%8E)
    * [1.4 数据库](#14-%E6%95%B0%E6%8D%AE%E5%BA%93)
    * [1.5 日志](#15-%E6%97%A5%E5%BF%97)
    * [1.6 项目管理](#16-%E9%A1%B9%E7%9B%AE%E7%AE%A1%E7%90%86)
    * [1.7 站点](#17-%E7%AB%99%E7%82%B9)
* [2. 前端 & 无线开发](#2-%E5%89%8D%E7%AB%AF--%E6%97%A0%E7%BA%BF%E5%BC%80%E5%8F%91)
* [3. 命令行程序](#3-%E5%91%BD%E4%BB%A4%E8%A1%8C%E7%A8%8B%E5%BA%8F)
    * [3.2 推荐](#32-%E6%8E%A8%E8%8D%90)
    * [3.1 开发库](#31-%E5%BC%80%E5%8F%91%E5%BA%93)
* [4. 工具](#4-%E5%B7%A5%E5%85%B7)
    * [4.1 Util](#41-util)
    * [4.2 系统相关](#42-%E7%B3%BB%E7%BB%9F%E7%9B%B8%E5%85%B3)
    * [4.3 办公](#43-%E5%8A%9E%E5%85%AC)
    * [4.4 安全](#44-%E5%AE%89%E5%85%A8)
* [5. 构建工具](#5-%E6%9E%84%E5%BB%BA%E5%B7%A5%E5%85%B7)
    * [5.1 项目构建](#51-%E9%A1%B9%E7%9B%AE%E6%9E%84%E5%BB%BA)
    * [5.2 css预处理](#52-css%E9%A2%84%E5%A4%84%E7%90%86)
    * [5.3 语言编译](#53-%E8%AF%AD%E8%A8%80%E7%BC%96%E8%AF%91)
        * [API](#api)
* [6. 其他](#6-%E5%85%B6%E4%BB%96)
    * [6.1 AI](#61-ai)
    * [6.2 并行计算](#62-%E5%B9%B6%E8%A1%8C%E8%AE%A1%E7%AE%97)
    * [6.3 Iot](#63-iot)
    * [6.4 图像](#64-%E5%9B%BE%E5%83%8F)
    * [6.5 Assembly](#65-assembly)
    * [6.6 NLP](#66-nlp)
    * [6.7 游戏](#67-%E6%B8%B8%E6%88%8F)
* [7. 调试](#7-%E8%B0%83%E8%AF%95)
    * [7.1 调试工具](#71-%E8%B0%83%E8%AF%95%E5%B7%A5%E5%85%B7)
    * [7.2 web调试](#72-web%E8%B0%83%E8%AF%95)
* [8. 测试](#8-%E6%B5%8B%E8%AF%95)
    * [8.1 测试框架](#81-%E6%B5%8B%E8%AF%95%E6%A1%86%E6%9E%B6)
    * [8.2 断言库](#82-%E6%96%AD%E8%A8%80%E5%BA%93)
    * [8.3 工具](#83-%E5%B7%A5%E5%85%B7)
    * [8.4 web 自动化](#84-web-%E8%87%AA%E5%8A%A8%E5%8C%96)
    
## 0. 概述

收藏和调研过的一些 npm 包的集合。(Npm packages)

## 1. 后端开发

### 1.1 HTTP

[Server]

* [spdy](https://github.com/spdy-http2/node-spdy) - SPDY/HTTP2服务器，兼容Express

[Client]

* [request](https://github.com/request/request) - Simplified HTTP request client
* [request-promise](https://github.com/request/request-promise) - request 模块的promise版本，流程控制更方便
* [got](https://github.com/sindresorhus/got) - 轻量化的[request](https://github.com/request/request)，支持async
* [superagent](https://github.com/visionmedia/superagent) - 功能丰富，支持插件，函数式风格，支持Node和浏览器
* [axios](https://github.com/axios/axios) - vue官方推荐的client库，功能丰富，支持Node和浏览器
* [node-fetch](https://github.com/bitinn/node-fetch) - 轻量级的Node版本的fetch
* [urllib](https://github.com/node-modules/urllib) - Request HTTP(s) URLs in a complex world
* [download](https://github.com/kevva/download) - 文件下载库

[Proxy]

* [http-proxy](https://github.com/nodejitsu/node-http-proxy) - 功能全面的http代理库
* [http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) - [http-proxy](https://github.com/nodejitsu/node-http-proxy) 中间件
* [anyproxy](https://github.com/alibaba/anyproxy) - 可供插件配置的HTTP/HTTPS代理服务器

[Mock]

* [Nock](https://github.com/node-nock/nock) - Node.js Mock库
* [Mock](https://github.com/nuysoft/Mock) - 浏览器和Node均可用，支持自定义schema和随机数据

[Util]

* [morgan](https://github.com/expressjs/morgan) - HTTP请求日志处理中间件
* [finalhandler](https://github.com/pillarjs/finalhandler) - Node.js final http responder
* [http-signature](https://github.com/joyent/node-http-signature) - Reference implementation of Joyent's HTTP Signature Scheme

### 1.2 框架

参考：[http://nodeframework.com/](http://nodeframework.com/)

[静态服务器]

* [serve-static](https://github.com/expressjs/serve-static) - 静态文件服务器
* [http-server](https://github.com/indexzero/http-server) - 静态文件服务器命令行工具，无需配置，一条命令开启 http 服务

[web 框架]

* [express](https://github.com/expressjs/express) - 可以说是使用最广泛的 Node.js web 框架
* [koa](https://github.com/koajs/koa) - express 原班人马打造，轻量精美的框架
* [fastify](https://github.com/fastify/fastify) - 提出 JSON Schema，使得序列化更快速，性能强大的框架
* [connect](https://github.com/senchalabs/connect) - 只提供中间件层的迷你框架
* [sails](https://github.com/balderdashy/sails) - 支持快速开发的 MVC 框架，Node 版 Rails
* [total.js](https://github.com/totaljs/framework) - MVC 框架，提供了丰富的 CMS 案例

[企业框架]

> 支持 Typescript

* [egg](https://github.com/eggjs/egg) - 基于 Koa，强大的 loader / plugin 等机制，项目架构更清晰可控，阿里巴巴企业级应用框架
* [nest](https://github.com/nestjs/nest) - 对标 Spring Boot 的企业级框架，提供了便利的装饰器
* [thinkjs](https://github.com/thinkjs/thinkjs) - 参考 ThinkPHP，基于 Koa 的企业级应用框架，360 奇舞团团队支持

[微服务]

* [hapi](https://github.com/hapijs/hapi) - 一款极简的框架，常用于 API Gateway
* [feathers](https://github.com/feathersjs/feathers) - 富有 Hook 特色的微服务框架
* [restify](https://github.com/restify/node-restify) - 基于 connect，同时支持 Server / Client
* [micro](https://github.com/zeit/micro) - 异步编程特色的微服务框架

[同构]

* [Meteor](https://github.com/meteor/meteor) - Node.js 全栈开发框架
* [Next.js](https://github.com/zeit/next.js) - React 同构框架
* [Nuxt.js](https://github.com/nuxt/nuxt.js) - Vue 同构框架
* [beidou](https://github.com/alibaba/beidou) - Egg / React 同构框架，性能强劲，支持客户端渲染降级

[无服务器]

* [serverless](https://github.com/serverless/serverless) - AWS 无服务器架构，支撑 AWS、Azure、Google Cloud 等相关服务
* [serverless-aliyun-function-compute](https://github.com/aliyun/serverless-aliyun-function-compute) - 阿里云 serverless 框架

[Real-Time]

* [socket.io](https://github.com/socketio/socket.io) - 强大的 WebSocket 框架
* [ws](https://github.com/websockets/ws) - 轻量快速，易测试的 WebSocket 框架

[RPC]

* thrift
* dnoe
* axon
* avsc
* xmlrpc
* noice-json-rpc

[数据通信]

* [protobuf](https://github.com/google/protobuf/tree/master/js) - Google 数据通信协议

### 1.3 模板引擎

* pug (jade)
* handlebars
* mustaches
* hogan
* nunjucks
* marko
* ejs
* art-template
* swig
* doT

### 1.4 数据库

下面介绍的都是基于数据库驱动程序(如 mysql2, redis, mongodb, odbc 等)之上封装，足以直接应用在生产环境的客户端工具。

[关系型]

* [sequelize](https://github.com/sequelize/sequelize) - 一款支持 mysql, sqlite3, pg, msssql 的多功能 orm 库
* [waterline](https://github.com/balderdashy/waterline) - Sail.js 默认的 orm 库，酷在其基于适配器，可以支持关系型 & 非关系型数据库，支持 mysql, sqlite3, pg, redis, mongodb
* [knex](https://github.com/tgriesser/knex) - 一款灵活编写的 SQL 构建工具，被 Ghost 采用，支持 mysql, sqlite3, pg
* [bookshelf](https://github.com/bookshelf/bookshelf) - 基于 knex 的上层 ORM 库，支持 mysql, sqlite3, pg

[其他]

* [mongoose](https://github.com/Automattic/mongoose) - 全能的 MongoDB ORM 库
* [ioredis](https://github.com/luin/ioredis) - 健硕全能的 redis 客户端工具

### 1.5 日志

* [log4js](https://github.com/log4js-node/log4js-node) - 中规中矩的 log4js 日志工具
* [bunyan](https://github.com/trentm/node-bunyan) - 基于 JSON 的日志模块
* [winston](https://github.com/winstonjs/winston) - 支持结构化 & 非结构化的更全能的日志工具

### 1.6 项目管理

[进程管理]

* [forever](https://github.com/foreverjs/forever) - 顾名思义，让你的进程永远运行下去
* [pm2](https://github.com/Unitech/pm2) - 支持热启动、负载、集群、监控、重启等功能
* [nodemon](https://github.com/remy/nodemon) - 支持热加载和自动重启
* [supervisor](https://github.com/petruisfan/node-supervisor) - 支持热加载和自动重启，较消耗内存

### 1.7 站点

[博客]

* [ghost](https://github.com/TryGhost/Ghost) - 强大的博客系统
* [calypso](https://github.com/Automattic/wp-calypso) - Wordpress Node版本

[CMS]

* [keystone](https://github.com/keystonejs/keystone) - 基于 Mongodb 的 CMS
* [directus](https://github.com/directus/directus) - 纯后台的 CMS 服务框架

[静态站点]

* [hexo](https://github.com/hexojs/hexo) - 静态博客生成器，已被golang的hugo超越
* [gatsby](https://github.com/gatsbyjs/gatsby) - React 静态站点生成器

[论坛]

* [NodeBB](https://github.com/NodeBB/NodeBB) - Node 论坛系统

## 2. 前端 & 无线开发

## 3. 命令行程序

### 3.2 推荐

* [redis-dump](https://github.com/jeremyfa/node-redis-dump) - Node 版本的 redis-dump

### 3.1 开发库

[输入]

* [get-stdin](https://github.com/sindresorhus/get-stdin) - 获取标准输入流的工具
* [inquirer](https://github.com/SBoudrias/Inquirer.js) - 命令行工具中的用户交互界面（包括「输入/选择/确认」等功能）

[输出]

* [chalk](https://github.com/chalk/chalk) - 输出五颜六色的字符
* [clear](https://github.com/bahamas10/node-clear) - 清除屏幕（同命令 clear）
* [clui](https://github.com/nathanpeck/clui) - 终端下的数据可视化工具，支持仪表盘 / 进度 / Loading / 线图等
* [figlet](https://github.com/patorjk/figlet.js) - 大字符 Banner 生成工具，比如一个超级大的 "Webpack" 标识
* [qrcode-terminal](https://github.com/gtanner/qrcode-terminal) - 终端输出二维码
* [ora](https://github.com/sindresorhus/ora) - 一款优雅的终端进度条 (spinner) 展示的库

[参数处理]

* [commander](https://github.com/tj/commander.js) - 完整的命令行用户界面的处理方案
* [yargs](https://github.com/yargs/yargs) - 海盗主题的命令行用户界面的处理方案
* [minimist](https://github.com/substack/minimist) - 标准命令行参数解析工具
* [meow](https://github.com/sindresorhus/meow) - 功能丰富的命令行开发库，主要用于处理参数

[其他]

* [update-check](https://github.com/zeit/update-check) - 版本更新检查模块

## 4. 工具

### 4.1 Util

[库]

* loadash
* underscore

[编码]

* libphonenumber

[时间处理]

* [moment](https://github.com/moment/moment) - 重量级时间处理库，支持时间解析、格式化、计算等，功能强大，支持浏览器和 Node.js，压缩后体积约为 16.3 KB
* [date-fns](https://github.com/date-fns/date-fns) - 较 moment 更轻量级的事件处理库，体积更小

### 4.2 系统相关

* [internal-ip](https://github.com/sindresorhus/internal-ip) - 获取IP地址
* [ipp](https://github.com/williamkapke/ipp) - Internet 打印机协议

### 4.3 办公

[excel]

* js-xlsx
* node-xlsx
* Node-Excel-Export

[ppt]

* node-ppt

[mail]

* nodemailer

### 4.4 安全

## 5. 构建工具

### 5.1 项目构建

* [parcel](https://github.com/parcel-bundler/parcel) - 新一代打包工具，更快更容易配置
* rollup
* webpack
* fis
* scrat
* gulp
* grunt
* browserify

### 5.2 css预处理

* stylus
* less
* sass
* postcss

### 5.3 语言编译

* babel
* marked

#### API

* [jsdoc](https://github.com/jsdoc3/jsdoc) - API 生成器，通过识别代码中的注释编译成 html 文档

## 6. 其他

### 6.1 AI

* [ConvNetJS](https://github.com/karpathy/convnetjs) - 卷积神经网络在浏览器的实现
* [deeplearnJS](https://github.com/PAIR-code/deeplearnjs)~~ - 浏览器下的支持硬件加速的深度学习库，使用 tfjs 代替~~
* [tfjs](https://github.com/tensorflow/tfjs) - TensorFlow JS 版本，官方计划大力支持
* [brain.js](https://github.com/BrainJS/brain.js) - 基于模型训练的神经网络 JS 库，支持浏览器和 Node

### 6.2 并行计算

* [gpu.js](https://github.com/gpujs/gpu.js/tree/develop) - 浏览器 GPU 运算模块
* [parallel.js](https://github.com/parallel-js/parallel.js) - 浏览器 web workers & Node多进程
* [napajs](https://github.com/Microsoft/napajs) - 基于 V8 多线程运行时环境

### 6.3 Iot

* [mqtt.js](https://github.com/mqttjs/MQTT.js) - MQTT 客户端，支持 node 和浏览器，是诸多 iot 库的基础设施
* [Ruff](https://ruff.io/) - 物联网硬件操作系统 & 平台，通过 JavaScript 控制硬件设备

### 6.4 图像

* [jimp](https://github.com/oliver-moran/jimp) - Node 图片读写、编辑库
* [node-opencv](https://github.com/peterbraden/node-opencv) - 基于opencv 2.4，无法完美支持 3+
* [opencv4node](https://github.com/justadudewhohacks/opencv4nodejs) - opencv 3+

### 6.5 Assembly

* [emscripten](https://github.com/kripken/emscripten) - LLVM to JavaScript Compiler.
* [compile-to-web](https://github.com/ChristianMurphy/compile-to-web) - Lang to LLVM & WASM Compiler.
* [joy](https://github.com/matthewmueller/joy) - Go to Javascript compiler.

### 6.6 NLP

* [natural](https://github.com/NaturalNode/natural) - 自然语言处理工具，已支持中文
* [jieba](https://github.com/yanyiwu/nodejieba) - 好用的中文分词工具
* [hubot](https://github.com/hubotio/hubot) - Github 的机器人框架
* [nlp.js](https://github.com/axa-group/nlp.js) - 自然语言处理工具，支持语义提取、情感分析、自动语言识别等

### 6.7 游戏

## 7. 调试

### 7.1 调试工具

* [debug](https://github.com/visionmedia/debug) - 最好用的 debug 日志辅助工具.
* [node-inspector](https://github.com/node-inspector/node-inspector) - Node debugger 和 Devtools 结合的调试工具（PS：node v6.3+ 已内置）

### 7.2 web调试

> 以下模块主要用于移动端，无F12 调试工具下的场景

* [weinre](http://people.apache.org/~pmuellr/weinre/) - phonegap 时代的产物，WebView 远程调试神器，不支持 node v4+，使用时一般通过nvm先切换node版本；
* [spy-debugger](https://github.com/wuchangming/spy-debugger) - 页面远程调试 & 抓包工具，不支持 node v4+
* [vconsole](https://github.com/Tencent/vConsole) - 微信小程序推出的调试工具，直接内嵌在页面内，支持控制台、网络、系统信息.

## 8. 测试

### 8.1 测试框架

### 8.2 断言库

### 8.3 工具

### 8.4 web 自动化

