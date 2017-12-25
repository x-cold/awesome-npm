# awesome-nodejs

Collections for node.js.

## 1. 后端开发

### 1.1 HTTP

[Server]

- [spdy](https://github.com/spdy-http2/node-spdy) - SPDY/HTTP2服务器，兼容Express

[Client]

- [request](https://github.com/request/request) - Simplified HTTP request client
- [request-promise](https://github.com/request/request-promise) - request 模块的promise版本，流程控制更方便
- [got](https://github.com/sindresorhus/got) - 轻量化的[request](https://github.com/request/request)，支持async
- [superagent](https://github.com/visionmedia/superagent) - 功能丰富，支持插件，函数式风格，支持Node和浏览器
- [axios](https://github.com/axios/axios) - vue官方推荐的client库，功能丰富，支持Node和浏览器
- [node-fetch](https://github.com/bitinn/node-fetch) - 轻量级的Node版本的fetch
- [urllib](https://github.com/node-modules/urllib) - Request HTTP(s) URLs in a complex world
- [download](https://github.com/kevva/download) - 文件下载库

[Proxy]

- [http-proxy](https://github.com/nodejitsu/node-http-proxy) - 功能全面的http代理库
- [http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) - [http-proxy](https://github.com/nodejitsu/node-http-proxy) 中间件
- [anyproxy](https://github.com/alibaba/anyproxy) - 可供插件配置的HTTP/HTTPS代理服务器

[Mock]

- [Nock](https://github.com/node-nock/nock) - Node.js Mock库
- [Mock](https://github.com/nuysoft/Mock) - 浏览器和Node均可用，支持自定义schema和随机数据

[Util]

- [morgan](https://github.com/expressjs/morgan) - HTTP请求日志处理中间件
- [finalhandler](https://github.com/pillarjs/finalhandler) - Node.js final http responder
- [http-signature](https://github.com/joyent/node-http-signature) - Reference implementation of Joyent's HTTP Signature Scheme

### 1.2 框架

参考：http://nodeframework.com/

[静态服务器]

- [serve-static](https://github.com/expressjs/serve-static) - 静态文件服务器
- [http-server](https://github.com/indexzero/http-server) - 静态文件服务器命令行工具，无需配置，一条命令开启 http 服务

[web 框架]

- Express
- Koa
- fastify
- connect

- SailJS
- Total.js

- Thinkjs

[微服务]

- Hapi
- Feathers
- Restify
- Micro

[同构]

- [Meteor](https://github.com/meteor/meteor) - Node.js 全栈开发框架
- [Next.js](https://github.com/zeit/next.js) - React 同构框架
- [Nuxt.js](https://github.com/nuxt/nuxt.js) - Vue 同构框架

[无服务器]

- serverless
- serverless-aliyun-function-compute

[Real-Time]

- socket.io

[RPC]

- thrift
- dnoe
- axon
- avsc
- xmlrpc
- noice-json-rpc

[数据通信]

- [protobuf](https://github.com/google/protobuf/tree/master/js) - Google 数据通信协议

### 1.3 模板引擎

- pug (jade)
- handlebars
- mustaches
- hogan
- nunjucks
- marko
- ejs
- art-template
- swig
- doT

### 1.4 数据库

- sequlieze
- waterline
- knex
- bookshelf
- mysql2

- mongoose

- redis
- ioredis

### 1.5 日志

- log4js
- Bunyan
- winston

### 1.6 项目管理

[进程管理]

- [forever](https://github.com/foreverjs/forever) - 顾名思义，让你的进程永远运行下去
- [pm2](https://github.com/Unitech/pm2) - 支持热启动、负载、集群、监控、重启等功能
- [nodemon](https://github.com/remy/nodemon) - 支持热加载和自动重启
- [supervisor](https://github.com/petruisfan/node-supervisor) - 支持热加载和自动重启，较消耗内存

### 1.7 站点

[博客]

- [ghost](https://github.com/TryGhost/Ghost) - 强大的博客系统
- [calypso](https://github.com/Automattic/wp-calypso) - Wordpress Node版本

[CMS]

- [keystone](https://github.com/keystonejs/keystone) - 基于 Mongodb 的 CMS
- [directus](https://github.com/directus/directus) - 纯后台的 CMS 服务框架

[静态站点]

- [hexo](https://github.com/hexojs/hexo) - 静态博客生成器，已被golang的hugo超越
- [gatsby](https://github.com/gatsbyjs/gatsby) - React 静态站点生成器

[论坛]

- [NodeBB](https://github.com/NodeBB/NodeBB) - Node 论坛系统

## 2. 前端 & 无线开发

## 3. 命令行程序

### 3.2 推荐

- [redis-dump](https://github.com/jeremyfa/node-redis-dump) - Node 版本的 redis-dump 

### 3.1 开发库

[输入]

- readline
- get-stdin

[输出]

- chalk
- clear
- clui - 仪表盘 / 进度 / Loading / 线图
- figlet - Title
- multispinner
- qrcode-terminal - 控制台输出二维码

[交互]

- inquirer

[账户配置]

- preferences

[参数处理]

- minimist
- commander
- yargs
- meow

## 4. 工具

### 4.1 Util

[库]

- loadash
- underscore

[编码]

- libphonenumber

[时间处理]

- [moment](https://github.com/moment/moment) - 重量级时间处理库，支持时间解析、格式化、计算等，功能强大，支持浏览器和 Node.js，压缩后体积约为 16.3 KB
- [date-fns](https://github.com/date-fns/date-fns) - 较 moment 更轻量级的事件处理库，体积更小

### 4.2 系统相关

- [internal-ip](https://github.com/sindresorhus/internal-ip) - 获取IP地址
- [ipp](https://github.com/williamkapke/ipp) - Internet 打印机协议

### 4.3 办公

[excel]

- js-xlsx
- node-xlsx
- Node-Excel-Export

[ppt]

- node-ppt

[mail]

- nodemailer

### 4.4 安全

## 5. 构建工具

### 5.1 项目构建

- [parcel](https://github.com/parcel-bundler/parcel) - 新一代打包工具，更快更容易配置
- rollup
- webpack
- fis
- scrat
- gulp
- grunt
- browserify

### 5.2 css预处理

- stylus
- less
- sass
- postcss

### 5.3 语言编译

- babel
- marked

#### API

- [jsdoc](https://github.com/jsdoc3/jsdoc) - API 生成器，通过识别代码中的注释编译成 html 文档

## 6. 其他

### 6.1 AI

- [ConvNetJS](https://github.com/karpathy/convnetjs) - 卷积神经网络在浏览器的实现
- [deeplearnJS](https://github.com/PAIR-code/deeplearnjs) - 浏览器下的支持硬件加速的深度学习库

### 6.2 并行计算

- [gpu.js](https://github.com/gpujs/gpu.js/tree/develop) - 浏览器 GPU 运算模块
- [parallel.js](https://github.com/parallel-js/parallel.js) - 浏览器 web workers & Node多进程
- [napajs](https://github.com/Microsoft/napajs) - 基于 V8 多线程运行时环境

### 6.3 Iot

- [mqtt.js](https://github.com/mqttjs/MQTT.js) - MQTT 客户端，支持 node 和浏览器，是诸多 iot 库的基础设施
- [Ruff](https://ruff.io/) - 物联网硬件操作系统 & 平台，通过 JavaScript 控制硬件设备

### 6.4 图像

- [jimp](https://github.com/oliver-moran/jimp) - Node 图片读写、编辑库
- [node-opencv](https://github.com/peterbraden/node-opencv) - 基于opencv 2.4，无法完美支持 3+
- [opencv4node](https://github.com/justadudewhohacks/opencv4nodejs) - opencv 3+

### 6.5 Assembly

- [emscripten](https://github.com/kripken/emscripten) - LLVM to JavaScript Compiler.
- [compile-to-web](https://github.com/ChristianMurphy/compile-to-web) - Lang to LLVM & WASM Compiler.
- [joy](https://github.com/matthewmueller/joy) - Go to Javascript compiler.

### 6.6 NLP

- [natural](https://github.com/NaturalNode/natural) - 自然语言处理工具，已支持中文
- [jieba](https://github.com/yanyiwu/nodejieba) - 好用的中文分词工具

- [hubot](https://github.com/hubotio/hubot) - Github 的机器人框架

### 6.7 游戏

### 7. 调试

### 7.1 调试工具

- [debug](https://github.com/visionmedia/debug) - 最好用的debug日志辅助工具.
- [node-inspector](node-inspector) - Node debugger 和 Devtools结合的调试工具（PS：node v6.3+ 已内置）

### 7.2 web调试

> 以下模块主要用于移动端，无F12 调试工具下的场景

- [weinre](http://people.apache.org/~pmuellr/weinre/) - phonegap 时代的产物，WebView远程调试神器，不支持node v4+，使用时一般通过nvm先切换node版本；
- [spy-debugger](https://github.com/wuchangming/spy-debugger) - 页面远程调试 & 抓包工具，不支持node v4+
- [vconsole](https://github.com/Tencent/vConsole) - 微信小程序推出的调试工具，直接内嵌在页面内，支持控制台、网络、系统信息.

### 8. 测试
