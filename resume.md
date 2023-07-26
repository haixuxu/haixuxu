# 个人信息

- xuxihai/男/1993
- 本科/山西大学/计算机科学与技术
- 毕业时间:  2015年7月
- 工作年限：7年
- Github：[http://github.com/xuxihai123](http://github.com/xuxihai123)
- 在线简历: [https://www.xuxihai.top/2017/05/12/page100](https://www.xuxihai.top/2017/05/12/page100)
- 目前职位：前端开发工程师

---

# 联系方式

- 手机：18234116049
- Email：xuxihai123[@gmail.com ](/gmail.com ) 
- QQ：373241884
- 微信：18234116049

---

# 个人技能

以下均为我熟练使用的技能

- 熟悉HTML/CSS/JS/ES5/ES6/Vue2/Vue3/Angular.js
- 熟悉浏览器兼容性问题处理
- 熟悉前端工具Grunt/Gulp/webpack/vue-cli/vite的使用
- 熟悉nodejs后端框架Express/koa的使用
- 熟悉常见的计算机网络协议(HTTP/websocket/TCP/socks5)
- 熟悉移动端混合开发技术
- 熟悉常见linux命令的使用(有linux作为主系统使用经验)
- 熟悉Git和SVN的使用
- 熟悉小程序和公众号的开发
- 熟悉RPC实现原理(熟悉JSONP/jsbridge/(websocket/http2)实现RPC)
- 熟悉nginx使用
- 熟悉SQL注入，XSS和CSRF攻击防范
- 熟悉Oauth2原理
- 熟悉SSE消息推送原理
- 熟悉chrome的插件开发
- 熟悉异步请求的并发和链式处理
- 熟悉数据库MySQL/mongodb的使用
- 搭建过gitlab CI、jenkins、sonarlint，企业npm， easymock服务

# 工作经历

## 北京科蓝软件系统股份有限公司

前端工程师（2019年8月 ~ 至今）

1、科蓝PC密码安全控件研发

- S: 公司有一款PC密码安全控件，密码控件集成使用jquery版本，用于JSP环境使用，由于前后端分离，前端模块化，同时减少不必要的依赖(jquery)，提高集成效率和优化用户体验，需要为密码控件封装jssdk库，供vue2/vue3/angularjs、JSP老项目的使用.
- T: 开发密码控件的jssdk，提供npm包使用的形式，规范化前端开发流程，方便前端人员集成公司密码控件。
- A: 分析密码控件JS老版本实现，设计新的版本实现, 实现分chrome和IE两部分, chrome上使用JSONP请求操作系统上的控件服务,在IE上使用ActiveObject对象访问操作系统上的控件服务，同时不依赖jquery库，支持多语言, 解决浏览器兼容性(支持IE9+)问题。
- R: 完成发布该npm包，公司多个项目正常使用。

2、科蓝行为验证码研发

- S:  行为验证码产品使用广泛, 公司希望研发自己的行为验证码产品, 以解决各产品还在使用老旧图形验证码带来的安全问题。
- T:  仿易盾/顶象/极验等厂商实现自己的行为验证码产品。
- A: 分析各厂商实现，搜集开源实现，搭建开发环境，开发对应的前后端逻辑实现 , 开发初版，迭代并完善产品，解决各浏览器兼容性问题(最低支持到IE7)。同时实现前端(微信小程序/支持宝小程序)版本, 支持微信低版本SDK兼容大部分微信客户端，集成weex版本，帮助集成Android/IOS版本，持续优化产品性能和用户体验, 支持多语言国际化。
- R: 功能开发完成，产品经过检测，已完成相关文档，已被多家银行采购使用。
- P: 预览: 微信小程序版本: 可搜索"悠悠有节"小程序体验,  [web在线版本](web在线版本)([https://vx.csii.com.cn/test/captcha/dist/](https://vx.csii.com.cn/test/captcha/dist/#/web))

3、科蓝无障碍产品研发

- S: 现在的互联网使用越来越广泛，但仍然存在部分行动障碍的残疾人、文化认知有障碍人士、以及阅读能力下降的人群，为帮助该人群提供有效的、友好的网站访问服务体验, 科蓝公司自主研发了辅助该人群浏览页面的无障碍工具。
- T:  作为技术负责人负责无障碍工具的总体设计，前端H5核心代码的实现。
- A: 分析主流无障碍工具实现方式，搭建开发环境，实现相应的功能 , 完成初版，迭代并完善产品，解决支持各浏览器兼容性问题(最低支持到IE9), 同时开发对应的chrome插件以支持用户测试使用该产品。
- R: 目前该产品已投产，已被多个客户采用
- P: 在线预览：[https://vx.csii.com.cn/products/csii.a11y/speak_v1.3.0/explainTab.html](https://vx.csii.com.cn/products/csii.a11y/speak_v1.3.0/explainTab.html)

4、科蓝员工考试系统研发

- S: 为解决公司对员工进行技术考试的需求。
- T: 负责员工考试系统总体设计，开发，部署，维护。达到满足公司员工考试需要。支持3000+用户并发下的用户访问。
- A: 负责员工考试系统总体设计，需求讨论，使用nodejs+expressjs+mongodb开发后台，使用vue2开发前端，支持使用(redis/mongodb)持久化session, 以实现分布式部署，使用pm2部署后台应用，使用ngixn部署静态资源，使用CDN加速静态资源访问,  版本迭代过程中，编写数据库迁移脚本，优化后台接口性能, 使用PWA、gzip和http缓存优化前端静态资源加载性能和用户体验, 解决高并发下nginx服务器上的TIME-AWAIT连接数过高的问题, 使用ab/jmeter/LoadRunner测试系统接口并发。 解决使用flutter开发系统移动端时app更新问题。
- R: 系统目前还有正常运行。 在线地址: [https://exam.csii.com.cn](https://exam.csii.com.cn)
## 360企业安全

前端工程师（2018年3月 ~ 2019年8月）

1、蓝信应用消息群发业务开发

- S: 该系统是一个类微信公众号管理端系统（类似公众号登录后看到的界面系统)
- T:  个人负责系统3x5菜单功能开发，公众号消息群发,消息卡片管理功能开发，达到需求描述的效果，通过QA测试，使用vue2技术实现, 前后端通讯层不使用ajax通讯方式，使用基于Websocket实现的自定义RPC协议
- A:  以下是我具体实施过程做的事情:  开发个人消息群发,消息卡片管理业务模块，开发3x5菜单配置模块,代码review，重构代码优化代码质量。
- R: 功能如期稳定上线．

2、天巡可视化项目开发

- S: 开发ISC大会可视化大屏展示项目
- T: 开发图表功能，支持使用控制端遥控大屏幕显示内容
- A: 开发相关图表，开发手机遥控器应用，使用websocket中转信号，使用electron打包整个应用。
- R: 在2018的ISC大会现场演示．

3、网站云防护业务开发

- S: 该产品是一个类似阿里云域名管理服务应用
- T: 基于vue2+typescript+element-ui开发，实现域名转入，域名防护, 域名访问数据统计等功能等功能，达到需求描述的效果，通过测试
- A: 业务开发，持续优化组件，优化产品用户体验。
- R: 功能稳定上线．


## 北京科蓝软件系统股份有限公司

前端工程师（2015年7月 ~ 2017年9月）

1、重庆力帆车贷系统

- S:　该项目需求是开发一个在线信用贷车系统，方便用户在线贷车．前端团队的我和同团队一位组长加上同公司后端团队一同完成，使用公司的类Angularjs框架
- T:　组长支持一周工作，负责框架的搭建工作，及预料到的棘手问题或组件的处理．我负责教会后台开发人员快速使用该框架前端如何编写业务逻辑代码及开发过程遇到的困难解决、维护该框架下的组件bug、后续需要的组件引入或实现．
- A:　我主要做的是下面一些事情: １．处理相关后台人台在使用前端框架过程中遇到的问题；２．使用２个单页加上angularjs路由机制实现系统的多角色下权限控制；３．使用正则表达式解决金额格式化组件在中文输入法下仍可以输入非数字字符bug；４．扩展日期组件不能根据后端数据动态显示某一日期的情况；５．变更分页控件的样式风格；６．引入可搜索的下拉框组件；等等其他工作内容
- R:  直到去支持同公司其他其他项目，相关组件都运行良好．同时也学到了许多东西．

2、公司研发的银行柜面系统

- S: 该项目需求是改造原系统(基于Java编写C/S结构应用)为B/S结构，然后嵌入开源浏览器，系统的使用者是银行柜员，分两个子系统，重要需求是需要让柜员尽量可以全键盘操作，使用公司的类Angularjs框架实施
- T: 我所属部门团队加上几位新人及项目经理完成这一改造，初期我负责全键盘操作的实现，实施过程中负责系统的技术问题解决、相关组件的开发和性能优化、部分业务逻辑代码的移植
- A:  以下是我具体实施过程做的事情: １．使用事件冒泡＋angularjs的事件广播机制＋$q实现系统的全键盘操作;２．优化团队他人编写的菜单组件；３．实现可编辑的下拉框，同时带按键控制下拉菜单弹出的；４．实现日期格式化组件；５．实现支持快捷键的搜索组件；６．优化系统的标签式导航组件；７．系统角色权限控制；等等其他
- R: 系统已经稳定运行并上线

3、民泰银行手机银行和直销银行移动app

- S: 该项目需求是开发一个移动端手机银行和直销银行应用，使用H5+Native混合开发技术
- T: 搭建前端开发环境，编写相关前端业务逻辑代码，与后台人员调试某些接口，与原生(安卓和IOS)调试某些插件，整合某些组件
- A: 以下是我具体实施过程做的事情:  根据设计稿编写HTML页面，编写前端业务逻辑代码，与后台人员调试某些接口，与原生调试某些插件，整合加载更多、短信验证码倒计时组件．
- R: 几个月的努力，系统已经稳定上线．组件运行良好．



# 个人兴趣作品

### HttpServer(http简单实现)

- 功能：响应html,js,css,json等静态文件资源和列出文件夹下的文件列表,不包含Http缓存,gzip等高级功能
- 相关技术: Http协议，socket编程，perl使用fork子进程，java 使用多线程，nodejs使用核心net模块
- 代码地址:[http://github.com/xuxihai123/HttpServer](http://github.com/xuxihai123/HttpServer)

### 个人博客

- 使用Node.js(Express+mysql+Ejs(前台)+Angularjs(后管))开发
- 代码地址:[http://github.com/xuxihai123/eblog](http://github.com/xuxihai123/eblog)

### 仿微信金额输入键盘

- 功能：实现模拟键盘金额输入效果
- 相关技术: jquery, DOM, javascript
- 代码地址:[https://xuxihai123.github.io/jquery-keyboardNum/](https://xuxihai123.github.io/jquery-keyboardNum/)

### 爬虫工具

- 功能：模拟用户登录网站，获取某一接口数据，使用该列表数据生成xlsx信息，发送到指定邮箱
- 相关技术: nodejs,熟悉使用nodejs相关模块:commander.js,moment,request,request-promise,mocha,excel.js
- 代码地址:[https://github.com/xuxihai123/csiivpmouth](https://github.com/xuxihai123/csiivpmouth)

### 端口扫描工具

- 功能：使用TCP/SYN扫描检测目标端口开放
- 相关技术: TCP协议/线程池, SYN扫描原理
- 代码地址:[https://github.com/xuxihai123/tcpscan](https://github.com/xuxihai123/tcpscan)


### vue-cli插件本地mock

- 功能：vue-cli脚手架支持mock
- 相关技术:express中间件, webpack, vue-cli原理
- 代码地址:[https://github.com/xuxihai123/vue-cli-plugin-mock](https://github.com/xuxihai123/vue-cli-plugin-mock)

### vite插件本地mock

- 功能：vite脚手架支持mock
- 相关技术: express中间件, nodejs， rollup, vite原理
- 代码地址:[https://github.com/xuxihai123/vite-plugin-mockit](https://github.com/xuxihai123/vite-plugin-mockit)

### chatgpt镜像

- 功能：支持chatgpt的接入使用
- 相关技术: express中间件, nodejs， socks5代理
- 代码地址:[https://github.com/xuxihai123/chatgpt-mirror](https://github.com/xuxihai123/chatgpt-mirror)

### 五笔拼音输入法(Mac)

- 功能：支持mac上使用五笔/拼音/五笔拼音混合输入
- 相关技术: swiftUI, 使用前缀树快速编码查找汉字
- 代码地址:[https://github.com/xuxihai123/lotus](https://github.com/xuxihai123/lotus) , 基于前缀树使用nodejs实现的五笔拼音搜索服务: [https://github.com/xuxihai123/inputengine](https://github.com/xuxihai123/inputengine)

### 翻墙工具

- 功能：突破网络封锁，浏览被封锁、遮蔽或干扰的内容, 个人主要用来访问Google相关服务。
- 相关技术: websocket/tcp/tls/http2传输协议, 自定义双工流实现，socks5/connect代理协议,  aes等加密技术
- 代码地址: nodejs版本: [https://github.com/bbk47/bbk](https://github.com/bbk47/bbk) GO版本 [https://github.com/bbk47/go-bbk](https://github.com/bbk47/go-bbk) 

### 协议转换服务(shadowsocks协议转http代理协议)

- 功能：实现shadowsocks协议转http代理(connect)协议，该服务可以用来把shadowsock客户端发出的数据包转换成未加密的connect协议数据包, 然后通过connect代理发送出去。个人主要用来在android上使用shadowsocks时转发数据到该服务，以突破网络封锁。
- 相关技术: shadowsocks协议, connect代理协议, 自定义transform流的运用， aes等加密技术
- 代码地址:  [https://github.com/xuxihai123/ssock2connect](https://github.com/xuxihai123/ssock2connect) 

---

# 致谢

感谢您的阅读，期待与您共事！
