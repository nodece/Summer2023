## 开源软件供应链点亮计划-暑期2022

### 开源软件供应链点亮计划-暑期2022”是什么？

“开源软件供应链点亮计划-暑期2022”（以下简称 暑期2022）是由中科院软件所与 openEuler 社区共同举办的一项面向高校学生的暑期活动，旨在鼓励在校学生积极参与开源软件的开发维护，促进国内优秀开源软件社区的蓬勃发展。

该计划将联合各大开源社区，针对重要开源软件的开发与维护提供项目，并向全球高校学生开放报名。学生可自主选择感兴趣的项目进行申请，并在中选后获得该软件资深维护者（社区导师）亲自指导的机会。根据项目的难易程度和完成情况，参与者还将获取“开源软件供应链点亮计划-暑期2022”活动奖杯和奖金。

暑期 2020 活动信息请查阅：https://summer-ospp.ac.cn/2020/

暑期 2021 活动信息请查阅：https://summer-ospp.ac.cn/2021/

**“暑期2022”项目在今年（2022）第三次举办，与Google Summer of Code类似，可以看做中国版的GSoC。**

1. 官网：https://summer-ospp.ac.cn/
2. 新闻：https://segmentfault.com/a/1190000041695372

### 活动的组织方有哪些

本次活动由中国科学院软件研究所、openEuler 社区主办，当前是第三届。

### 活动的参与方以及角色有哪些

活动参与方主要角色为学生、社区和导师。

1. 学生：学生自由选择项目，与社区导师沟通实现方案并撰写项目计划书。被选中的学生将在社区导师指导下，按计划完成开发工作，并将成果贡献给社区。社区评估学生的完成度，主办方根据评估结果发放资助金额给学生。
2. 社区：社区提供项目列表和描述，并安排项目对应的导师，导师与申请者沟通方案、并从申请者中选中一位承接项目。在为期三个月的开发周期中，导师指导学生进行对应项目的开发工作。
3. 导师：社区针对每一个项目指定一个社区导师，与学生一起制定合适的开发计划和方案，指导学生按计划完成开发。

### 项目的奖金是多少

学生可获得的奖金：

1. 进阶：奖金人民币 12000 元：优化类的任务，例如提高时间、降低内存占用、提供性能等
2. 基础：奖金人民币 8000 元：功能类的任务，例如为本社区开源项目增加一个或若干个重要特性等

难度分级由社区根据项目任务决定。

对于导师而言，无论何种难度，导师的奖金为每个项目税前 3000 元人民币，每位导师最多负责 1 个项目，即奖金最多为税前 3000 元人民币。

## Casbin开源项目介绍

Casbin是一个强大的、高效的开源访问控制框架。涉及到Go, Java, Node.js, Javascript (React), Python, PHP, .NET, Delphi, Rust等多种语言。Casbin由北京大学罗杨博士创立于2017年，核心维护团队有数十人。Casbin在业界具有广泛影响力。目前已经被Intel、VMware、Orange、RedHat、T-Mobile等公司开源使用，被腾讯云、Cisco、Verizon等公司闭源使用。具体详见Casbin主页。Casbin Go主项目目前GitHub 8800+ stars，加上所有语言的实现、插件等可达到15000+ stars。Casbin曾经在国际上多次宣讲：

1. 新加坡政府技术部门Open Government Products：https://www.youtube.com/watch?v=OTT84oplR9o
2. 俄罗斯最大在线旅游平台tutu.ru：https://www.youtube.com/watch?v=Z5dUxH4PqYM

具体请了解Casbin官网：https://casbin.org/

## 可选项目列表

下列所有项目都与Casbin一致，采用开源协议：[Apache 2.0 license](LICENSE)

- [Casbin核心权限库改进（Go + Java）](#casbin核心权限库改进go--java)
- [Casbin核心权限库改进（Go + .NET）](#casbin核心权限库改进go--net)
- [Casbin/Casdoor 文档优化](#casbincasdoor-文档优化)
- [加速 Node-Casbin、Casbin.js 在 Web 和 Node.js 平台上的插件生态建设](#加速-node-casbincasbinjs-在-web-和-nodejs-平台上的插件生态建设)
- [Casdoor单点登录系统、Casnode社区系统（前端React + JS，后端Go）](#casdoor单点登录系统casnode社区系统前端react--js后端go)
- [Python/PHP-Casbin 在分布式系统和主流框架下的应用扩展开发（Python/PHP）](#pythonphp-casbin-在分布式系统和主流框架下的应用扩展开发pythonphp)
- [SwiftCasbin 开发（Swift)或Casdoor单点登录系统大前端支持](#swiftcasbin-开发swift或casdoor单点登录系统大前端支持)

### Casbin核心权限库改进（Go + Java）
1. 项目名称：Casbin（Go + Java）
2. 项目主导师：[唐阳 (Yang Tang)](https://github.com/tangyang9464), tangyang9464 (AT) 163.com
3. 项目描述：Casbin采用独特的PERM模型语法（model）来实现强大、灵活的访问控制。Casbin Golang版本作为Casbin的第一个语言实现，拥有最多的用户以及最先进的feature。我们希望在Casbin Golang上： 1）增强Casbin语法的表达能力，满足用户多样化的策略制定需求； 2）优化Casbin在大规模规则集上（百万以上）的策略评估性能。 jCasbin是Casbin的Java版本，它需要及时跟踪Golang Casbin主库的最新feature并移植到Java版本中来。同时维护Java特有的生态
4. 项目难度：进阶
5. 涉及技术领域标签：Authorization
6. 编程语言标签：Go, Java
7. 项目产出要求：
   - 增强Casbin语法的表达能力，满足用户多样化的策略制定需求
   - 优化Casbin在大规模规则集上（百万以上）的策略评估性能
   - 跟踪Casbin-Go最新特性并移植到jCasbin，如实现WatcherEx:[casbin#943](https://github.com/casbin/casbin/issues/943)
   - 维护完善jCasbin的Java特有生态，如实现Play框架中间件：[jcasbin#104](https://github.com/casbin/jcasbin/issues/104)
   - 解决Casbin-Go和jCasbin以及相关仓库中的issues：[Casbin-Go](https://github.com/casbin/casbin/issues) & [jCasbin](https://github.com/casbin/jcasbin/issues)
8. 项目技术要求：
   - 熟悉Golang或Java语言
   - 熟悉Git、GitHub相关操作
9. 项目成果仓库：
   - https://github.com/casbin/casbin
   - https://github.com/casbin/jcasbin


### Casbin核心权限库改进（Go + .NET）
1. 项目名称：Casbin（Go + .NET）
2. 项目主导师：[汤贤赫 (Sagilio)](https://github.com/sagilio), sagilio (AT) outlook.com
3. 项目描述：Casbin采用独特的PERM模型语法（model）来实现强大、灵活的访问控制。Casbin Golang版本作为Casbin的第一个语言实现，拥有最多的用户以及最先进的feature。我们希望在Casbin Golang上： 1）增强Casbin语法的表达能力，满足用户多样化的策略制定需求； 2）优化Casbin在大规模规则集上（百万以上）的策略评估性能。 Casbin.NET是Casbin的.NET版本，它需要及时跟踪Golang Casbin主库的最新feature并移植到.NET版本中来。并维护.NET特有的生态
4. 项目难度：进阶
5. 涉及技术领域标签：Authorization
6. 编程语言标签：Go, C#(.NET)
7. 项目产出要求：
   - 增强Casbin语法的表达能力，满足用户多样化的策略制定需求
   - 优化Casbin在大规模规则集上（百万以上）的策略评估性能
   - 跟踪Casbin-Go最新特性与BUG修复，并同步到Casbin.NET，如重构的RoleManager:[Casbin.NET#250](https://github.com/casbin/Casbin.NET/issues/250)
   - 完善Casbin.NET的特有生态, 1) 完善现有的aspnetcore中间件：https://github.com/casbin-net/casbin-aspnetcore; 2) 完善Casdoor.SDK的.NET版本: https://github.com/casdoor/casdoor-dotnet-sdk
   - 解决Casbin-Go和Casbin.NET以及相关仓库中的issues：[Casbin-Go](https://github.com/casbin/casbin/issues) & [Casbin.NET](https://github.com/casbin/Casbin.NET/issues)
8. 项目技术要求：
   - 熟悉Golang或C#语言
   - 熟悉Git、GitHub相关操作
9. 项目成果仓库：
   - https://github.com/casbin/casbin
   - https://github.com/casbin/Casbin.NET

### Casbin/Casdoor 文档优化
1. 项目标题：Casbin/Casdoor 文档优化
2. 项目主导师：[刘子轩 (nodece)](https://github.com/nodece), nodeces (AT) gmail.com
3. 项目描述：Casbin和Casdoor是Casbin社区的出色项目，他们的官网和文档都是使用[Docusaurus](https://docusaurus.io/)框架进行搭建，文档翻译是使用[CrowdIn](https://crowdin.com/)在线翻译平台进行众包翻译，随着项目的不断发展，文档与代码会存在一定的落差。文档是软件的重要组成部分，改进文档提升用户体验是不可或缺的部分。
4. 项目难度：基础
5. 涉及技术领域标签：Authorization, Authentication
6. 编程语言标签：JavaScript, Golang
7. 项目产出要求：
   - 同步Casbin以支持的语言的management API和rabc API到Casbin文档中的API模块
   - 改进Casdoor文档整体体验，梳理Casdoor各个功能，对文档内容和布局进行优化
   - 对Casbin文档进行英译汉，当前进度86%，目标进度100%
   - 对Casdoor文档进行英译汉，当前进度80%，目标进度100%
   - （有时）撰写、编辑Casbin社区推广（如Casbin官方微信公众号）文章
8. 项目技术要求：
   - 热爱并有能力撰写技术博客、文章
   - 了解Git、GitHub相关操作
   - 了解Casbin的工作原理
   - 了解Casdoor的工作原理
9. 项目成果仓库：
   - https://github.com/casbin/casbin-website
   - https://github.com/casdoor/casdoor-website

### 加速 Node-Casbin、Casbin.js 在 Web 和 Node.js 平台上的插件生态建设
1. 项目标题：加速 Node-Casbin、Casbin.js 在 Web 和 Node.js 平台上的插件生态建设
2. 项目主导师：[刘子轩 (nodece)](https://github.com/nodece)，nodeces (AT) gmail.com
3. 项目描述：Node-Casbin 和 Casbin.js 采用独特的 PERM 模型语法（model）来实现强大、灵活的访问控制，能够在 Web、Node.js、Electron 等 JavaScript 平台上轻松运行。我们希望加速 Node-Casbin 和 Casbin.js 在 Web 和 Node.js 平台上的插件生态系统的快速发展，为开发者提供一系列丰富的 Adapter、Watcher 和 Starter 插件，实现便捷的开箱即用体验。我们计划以 Web 平台为核心，为 Angular、React、Vue 主流框架提供 Starter 插件，帮助开发者快速在项目中使用 Node-Casbin 和 Casbin.js，同时继续维护并优化现有 Node.js 平台的 Adapter、Watcher 和 Starter 插件，全面加速 Node-Casbin 和 Casbin.js 生态建设。
4. 项目难度：进阶
5. 涉及技术领域标签：Authorization
6. 编程语言标签：JavaScript, TypeScript, React, Vue, Angular, Node.js
7. 项目产出要求：
   - 为 Angular、React、Vue 框架提供 Starter 插件，以帮助用户快速使用 Node-Casbin
   - 解决 Node-Casbin 主仓库的 issues：https://github.com/casbin/node-casbin/issues
   - 解决 Casbin.js 主仓库的 issues：https://github.com/casbin/casbin.js/issues
   - 对现有的 Adapter、Watcher 和 Starter 插件进行维护，并提供插件使用文档和插件索引文档，方便用户快速查看和使用插件
8. 项目技术要求：
   - 熟练使用 JavaScript 语言
   - 了解 Casbin 的工作原理
   - 了解 Git、GitHub 相关操作
   - 有能力撰写技术文章
9. 项目成果仓库：
   - https://github.com/casbin/node-casbin
   - https://github.com/casbin/casbin.js

### Casdoor单点登录系统、Casnode社区系统（前端React + JS，后端Go）

1. 项目名称：Casdoor单点登录系统、Casnode社区系统（前端React + JS，后端Go）
2. 项目主导师：[罗杨 (hsluoyz)](https://github.com/hsluoyz), hsluoyz (AT) gmail.com
3. 项目描述：Casdoor是一套基于基于OAuth 2.0 / OIDC协议的统一身份认证（单点登录）系统。其支持多种第三方登录方式，如QQ、微信、Google, GitHub等。Casdoor具有Web管理界面，可以用来管理用户、角色、权限（基于Casbin）。Casbin社区目前采用QQ群（中文），Gitter（英文）进行社区交流，交流渠道比较有限。我们打算开发一个同时面向Casbin开发者和用户的官方论坛：casnode（https://github.com/casbin/casnode ）。该论坛开源，因此也欢迎其他开源社区使用。
4. 项目难度：进阶
5. 涉及技术领域标签：Micro Service
6. 编程语言标签：Go, JavaScript
7. 项目产出要求：
   - 扩展架构，添加更多的第三方登录支持
   - 优化、美化Web界面
   - 支持Casbin权限管理
   - 继续维护该项目，添加features，解决bugs，完善其邮件列表功能
   - 解决Casdoor主仓库&相关仓库中的issues：https://github.com/casbin/casdoor/issues
   - 解决Casnode&相关仓库中的issues：https://github.com/casbin/casnode/issues
8. 项目技术要求：
   - 熟悉React、Javascript语言（前端）
   - 熟悉Golang语言（后端）
   - 熟悉Git、GitHub相关操作
9. 项目成果仓库：
   - https://github.com/casdoor/casdoor
   - https://github.com/casbin/casnode

### Python/PHP-Casbin 在分布式系统和主流框架下的应用扩展开发（Python/PHP）

1. 项目名称：Python/PHP-Casbin 生态完善（Python/PHP）
2. 项目主导师：[李强 (Jon Lee)](https://github.com/leeqvip), leeqvip (AT) gmail.com
3. 项目描述：Casbin 是一个强大的、高效的开源访问控制框架，对主流语言都有相关实现，包括Python、PHP版本的Casbin。Casbin在业界具有广泛影响力，社区活跃。目前，目前PyCasbin/PHP-Casbin主库主要功能虽然相对完善和稳定，但仍然需要不断迭代演进，特别是对Python和PHP生态内各种框架、插件的集成，代码质量和性能还有调优的可能，所以我们希望对主库及其周边生态系统进行完善和优化，以增强Casbin在脚本语言Python和PHP领域的应用场景，提高外部系统接入Casbin效率和成本，进而扩大Casbin在Python和PHP领域的生态圈，使其能更好更快的发展。
4. 项目难度：进阶
5. 涉及技术领域标签：Authorization、API
6. 编程语言标签：Python，PHP，Go
7. 项目产出要求：
   - 对分布式存储系统`ETCD`的适配`etcd-adapter`
   - 完善Py/PHP-Casbin的对Redis（`redis-adapter`）适配器
   - 对权限决策`enforce()`的过程做基准测试、弱点分析、性能优化
   - 增加`addPermissionsForUser()` API.
   - 增加对`g`方法的缓存, 参考: https://github.com/casbin/casbin/blob/master/util/builtin_operators.go#L333.
   - 实现和完善[WatcherEx](https://casbin.org/docs/en/watchers#watcherex)
   - 引入Casbin核心引擎[Casbin Core Engine (Golang)](https://github.com/casbin/casbin/releases)中的新功能
   - 对主流框架的支持增强，例如：如果在Python的`Django`的扩展中, 需要引入Django的`Middleware`, `Caching`, `Logging`, 集成`Django`的认证系统（authentication system）；而PHP主流框架Laravel中已有[Laravel-Authz](https://github.com/php-casbin/laravel-authz)，但需要引入Laravel的[Gates](https://laravel.com/docs/9.x/authorization#gates)等
   - 解决[PyCasbin](https://github.com/casbin/pycasbin)或[PHP-Casbin](https://github.com/php-casbin/php-casbin)主库以及相关仓库中的issues
8. 项目技术要求：
   - 熟悉Python、PHP任意一种语言即可
   - 熟悉Git、GitHub相关操作
9. 项目成果仓库：
   - https://github.com/casbin/pycasbin
   - https://github.com/pycasbin
   - https://github.com/php-casbin/php-casbin
   - https://github.com/php-casbin

### SwiftCasbin 开发（Swift）或Casdoor单点登录系统大前端支持

1. 项目名称：SwiftCasbin 开发（Swift）SwiftCasbin 开发（Swift)或Casdoor单点登录系统大前端支持。
2. 项目主导师：[孟祥文 (xiaobeiswift)](https://github.com/xiaobeiswift) cit117 (AT) me.com
3. 项目描述：开发Swift版本的Casbin，支持iOS App、Swift服务器端应用等生态。Casdoor单点登录系统大前端应用 ios、安卓、flutter、uinapp、小程序等sdk的开发
4. 项目难度：进阶
5. 涉及技术领域标签：Authorization,SDK,Casdoor,App
6. 编程语言标签：swift,dart,java,kotlin,js
7. 项目产出要求：
   - 实现 Casbin 的 Swift 版本
   - 实现纯数据库驱动的 adapter: PostgresQL, Mysql, Microsoft SQL Server, Oracle, SQLite, IBM Db2.
   - 解决 SwiftCasbin 主仓库&相关仓库中的 issues：https://github.com/casbin/SwiftCasbin/issues
   - 设计前端友好的casdoor api,完成安卓，ios，flutter，uniapp，小程序的sdk
   - 每个sdk演示app的开发及文档完善。
8. 项目技术要求：
   - 熟悉 Swift/Dart/Java/Kotlin/js 语言的一种
   - 熟悉 iOS/andriod/flutter一种原生开发或小程序/uniapp框架的使用
   - 了解Oauth2流程
   - 熟悉 Git、GitHub 相关操作
9. 项目成果仓库：
   - https://github.com/casbin/SwiftCasbin
   - https://github.com/SwiftCasbin
   - https://github.com/casdoor/casdoor-ios-sdk
   - https://github.com/casdoor/casdoor-android-sdk
   - https://github.com/casdoor/casdoor-dart-sdk

所有可选项目详见：https://github.com/casbin/Summer2022#可选项目列表

## 候选人要求

### 工作职责：

- 每周与项目导师进行线上讨论，完成项目规定的开发任务。项目导师由开源项目创始人或其他核心成员担任；
- 积极参与开源社区的建设，参与代码提交、解决Issue、审核PR等日常工作；
- 配合完成官方要求的材料提交等事项，包括项目申请书撰写、社区反馈任务完成度追踪等。

### 职位要求：

- 本科、硕士或博士在读（已毕业、工作的无法参加）；
- 对开源软件、开源社区感兴趣；
- 熟悉一种或多种编程语言，有较强的工程能力，代码格式清晰规范，善于团队协作；
- 有一定英文读写能力，能够熟练运用英语在GitHub进行开发、协作；
- 较强的沟通能力和逻辑表达能力。

### 具有以下条件者优先：

- 熟悉计算机网络、网络安全，有相关项目经验；
- 熟悉Go, Rust等语言、分布式系统、微服务架构，有相关项目经验；
- 在GitHub较为活跃，有自己的开源项目，或参与过知名开源项目；
- 可以在项目结束后继续长期参与开源社区的开发、建设或维护。


## 投递要求

申请学生需要同时完成以下“联系社区”和“官网投递”两个环节：

### 1. 联系社区（即日起至2022年6月4日）

1. 发送【中文简历PDF】至Casbin社区官方邮箱：admin (AT) casbin.org 
2. 加入《Casbin访问控制社区群》（QQ大群）：[546057381](https://shang.qq.com/wpa/qunwpa?idkey=8ac8b91fc97ace3d383d0035f7aa06f7d670fd8e8d4837347354a31c18fac885)
3. 加入《Casbin明日之星预选生-Talent 2022-群》（QQ小群）：[540163681](https://qm.qq.com/cgi-bin/qm/qr?k=5MjIdZuPmAio6lfAr-NTxBY0CcoGL1yl&jump_from=webapi) ，联系导师，与导师沟通项目细节和方案，完善项目申请书
4. 选择技术写作题目“Casbin文档中文翻译 + 官网优化”的同学，还需要加入《Casbin文档题目申请》（QQ文档群）：[714309545](https://qm.qq.com/cgi-bin/qm/qr?k=T-hOJN1IzKN638y2N9rJJDdIT1fqpfua&jump_from=webapi)，并仔细阅读群公告，联系导师沟通项目细节

### 2. 官网投递（2022年5月21日至2022年6月4日）

详见：https://summer-ospp.ac.cn/help/
