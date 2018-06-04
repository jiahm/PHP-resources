# PHP-resources
PHP 资源大全中文版


PHP 资源大全中文版

我想很多程序员应该记得 GitHub 上有一个 Awesome - XXX 系列的资源整理。awesome-php 就是 ziadoz 发起维护的 PHP 资源列表，内容包括：库、框架、模板、安全、代码分析、日志、第三方库、配置工具、Web 工具、书籍、电子书、经典博文等。

Awesome 系列虽然挺全，但基本只对收录的资源做了极为简要的介绍，如果有更详细的中文介绍，对相应开发者的帮助会更大。这也是我们发起这个开源项目的初衷。

我们要做什么？

基于 awesome-php 资源列表，我们将对各个资源项进行编译整理。
整理后的内容，将收录在伯乐在线资源频道。可参考已整理的内容： 
《Snappy：压缩工具的 PHP 扩展》
《phy-yaf：一个用C语言编写的php框架》
如何参与本项目？

从下面的目录来看，本项目的工作量小不了，所以非常期待能有更多程序员一起来参与。

不过加入前，有几个小要求：

英文还不错，能读懂英文并用自己的话复述；
有 PHP 开发经验；
如有兴趣，请加 QQ：50872495。加 Q 时请注明「PHP大全」

本项目的参与者

维护者：tangyouhua

贡献者：cucr、欧w、邢敏、冰斌、wispedia、You

注：名单不分排名，不定期补充更新

奖励计划

虽然奖励可能并不是你加入的主要原因，但还是有必要提一下：

整理超过 20 个资源后，可在伯乐在线上开通打赏；
每整理 20 个资源，有机会获得技术书籍或各种有意思的创意、极客产品；
官奖励详情网
依赖管理

依赖和包管理库

Composer/Packagist：一个包和依赖管理器 Composer官网/Packagist官网
Composer Installers：一个多框架Composer库安装器 官网
Pickle：一个PHP扩展安装器 官网
其他的依赖管理

其他的相关依赖管理

Satis：一个静态Composer存储库生成器 官网
Composition：一个在运行时检查Composer环境的库 官网
Version：语义版本的解析和比较库 官网
NameSpacer：转化下划线到命名空间的库 官网
Patch Installer：使用Composer安装补丁的库 官网 
Composer Checker：校验Composer配置的工具 官网
框架

Web开发框架

Symfony2：一个独立组件组成的框架 官网
Zend Framework 2：另一个由独立组件组成的框架 官网
Laravel 4：另一个PHP框架 官网
Aura PHP：独立组件的框架 官网
Yii2： 另一个PHP框架 官网
Nette： 另一个由个体组件组成的框架 官网
PPI Framework 2：一个互操作性框架 官网
Phalcon：通过C扩展实现的框架 官网、Github
其他框架

其他Web开发框架

Symfony CMF：创建自定义CMS的内容管理框架 官网
Knp RAD Bundle：Symfony 2的快速应用程序（RAD）包 官网
框架组件

来自Web开发框架的独立组件

Symfony2 Components：Symfony2组件 官网
Zend Framework 2 Components：ZF2组件 官网
Aura Components：PHP5.4组件包 官网
Hoa Project：另一个PHP组件包 官网
微型框架

微型框架和路由

Silex：基于Symfony2组件的微型框架 官网
Slim：另一个简单的微型框架 官网
Bullet PHP：用于构建REST APIs的微型框架 官网
Fast Route：快速路由库 官网
Pux：另一个快速路由库 官网
其他微型框架

其他相关的微型框架和路由

Silex Skeleton：Silex的项目架构 官网
Silex Web Profiler：Silex web调试工具条 官网
Stack： Silex/Symfony的可堆叠中间件库 官网
Slim Skeleton：Slim架构 官网
Slim View：Slim的自定义视图集合 官网
Slim Middleware：Slim的自定义中间件集合 官网
phy-yaf：一个用C语言编写的php框架 官网
模板

模板化和词法分析的库和工具

Twig：一个全面的模板语言 官网
Twig Cache Extension：一个用于Twig的模板片段缓存库 官网
Mustache：一个Mustache模板语言的PHP实现 官网
Phly Mustache：另一个Mustache模板语言的PHP实现 官网
MtHaml： 一个HAML 模板语言的PHP实现 官网
PHPTAL：一个 TAL 模板语言的PHP实现 官网
Plates：一个原生PHP模板库 官网
Lex：一个轻量级模板解析器 官网
静态站点生成器

预处理工具来生成Web页面的内容。

Sculpin：转换Markdown和Twig为静态HTML的工具 官网
Phrozn： 另一个转换Textile，Markdown和Twig为HTML的工具 官网
HTTP

用于HTTP和网站爬取的库

Guzzle：一个全面的HTTP客户端 官网
Buzz：另一个HTTP客户端 官网
Requests：一个简单的HTTP库 官网
HTTPFul：一个链式HTTP库 官网
Goutte：一个简单的web爬取器 官网
PHP VCR：录制和重放HTTP请求的库 官网
URL

解析URL的库

Purl：一个URL处理库 官网
PHP Domain Parser：一个本地前缀解析库 官网
Email

发送和解析邮件的库

SwiftMailer：一个邮件解决方案 官网
PHPMailer：另一个邮件解决方案 官网
Fetch：一个IMAP库 官网
Email Reply Parser：一个邮件回复解析库 官网
Stampie：邮件服务库，不如 SendGrid, PostMark, MailGun 和 Mandrill. 官网
CssToInlineStyles：一个在邮件模板内联CSS的库 官网
文件

文件处理和MIME类型检测库

Gaufrette：一个文件系统抽象层 官网
Flysystem：另一个文件系统抽象层 官网
Canal：一个检测互联网媒体类型的库 官网
Apache MIME Types：一个解析Apache MIME类型的库 官网
Ferret：一个MIME检测库 官网
Hoa Mime：另一个MIME检测库 官网
Lurker：一个资源跟踪库 官网
PHP File Locator：一个在大型项目定位文件的库 官网
PHP FFmpeg：一个用于FFmpeg 视频包装的库. 官网
CSV：一个CSV数据处理库 官网
流

处理流的库

Streamer：一个面向对象的流包装库 官网
依赖注入

实现依赖注入设计模式的库

Pimple：一个小的依赖注入容器 官网
Auryn：另一个依赖注入容器 官网
Orno DI：另一个可伸缩的依赖注入容器 官网
PHP DI：一个使用注释实现的依赖注入 官网
Acclimate：一个依赖注入容器和服务定位的通用接口 官网
图像

处理图像的库

Imagine：一个图像处理库 官网
PHP Image Workshop：另一个图像处理库 官网
Intervention Image：另一个图像处理库 官网
GIF Frame Extractor：一个提取GIF动画帧信息的库 官网
GIF Creator：一个通过多张图片创建GIF动画的库 官网
Image With Text：一个在图像中嵌入文本的库 官网
Color Extractor：一个从图像中提取颜色的库 官网
测试

测试代码和生成测试数据的库

PHPUnit：一个单元测试框架 官网
DBUnit：PHPUnit的数据库测试库 官网
ParaTest：PHPUnit的并行测试库 官网
PHPSpec：基于功能点设计的单元测试库 官网
Codeception：一个全栈测试框架 官网
AspectMock： PHPUnit/ Codeception 模拟框架。 官网
Atoum：一个简单的测试库 官网
Mockery：一个用测试的模拟对象库 官网
Phake：另一个用测试的模拟对象库 官网
Prophecy：一个可选度很高的模拟框架 官网
Faker：一个伪数据生成库 官网
Samsui：另一个伪数据生成库 官网
Alice：富有表现力的一代库 官网
Behat：一个行为驱动开发（BDD）测试框架 官网
Pho：一个行为驱动开发测试框架 官网
Mink：Web验收测试 官网
HTTP Mock：一个在单元测试模拟HTTP请求的库 官网
Stream：一个用于测试的虚拟文件系统流的包装器 VFS 官网
VFS：另一个用于测试虚拟文件系统 官网
Locust：一个用Python编写的现代加载测试库 官网
持续集成

持续集成的库和应用

Travis CI：一个持续集成平台 官网
PHPCI：一个PHP的开源持续集成平台 官网
Sismo：一个持续测试服务库 官网
Jenkins-PHP：支持Jenkins的一个持续集成平台 官网
JoliCi：一个用PHP编写的由Docker支持的持续集成客户端 官网
文档

生成项目文档的库

Sami：一个API文档生成器 官网
APIGen：另一个API文档生成器 官网
PHP Documentor 2：一个API文档生成器 官网
phpDox：一个PHP项目的文档生成器（不限于API文档） 官网
安全

生成安全的随机数，加密数据，扫描漏洞的库

HTML Purifier：一个兼容标准的HTML过滤器 官网
RandomLib：一个生成随机数和字符串的库 官网
True Random：使用 www.random.org生成随机数的库 官网
SecurityMultiTool：一个PHP安全库 官网
PHPSecLib：一个纯PHP安全通信库 官网
TCrypto：一个简单的键值加密存储库 官网
IDS： 一个结构化的PHP安全层 PHP 官网
PHP-SSH：一个试验的面向对象的SSH包装库 官网
IniScan：一个扫描PHP INI文件安全的库 官网
SensioLabs Security Check：一个为检查Composer依赖提供安全建议的web工具 官网
Zed：一个集成的web应用渗透测试工具 官网
密码

处理和存储密码的库和工具

Password Compat：一个新的PHP5.5密码函数的兼容库 官网
phpass： 一个便携式的密码哈希框架 官网
PHP Password Lib：一个生成和校验密码的库 官网
Password Policy：一个PHP和JavaScript的密码策略库 官网
Password Validator：校验和升级密码哈希的库 官网
Zxcvbn PHP：一个基于Zxcvbn JS的现实的PHP密码强度估计库 官网
代码分析

分析，解析和处理代码库的库的工具

PHP Parser：一个PHP编写的PHP解析器 官网
PHPPHP： 一个PHP实现的PHP虚拟机 官网
PHPSandbox：一个PHP沙盒环境 官网
Dissect：一个词法和语法分析的工具集合 官网
PHP Mess Detector：一个扫描代码缺陷,次优代码，未使用的参数等等的库。 官网
PHP Code Sniffer：一个检测PHP、CSS和JS代码标准冲突的库 官网
PHPCPD： 一个检测复制和粘贴代码的库 官网
PHP Analyser：一个分析PHP代码查找缺陷和错误的库 官网
PHP CS Fixer： 一个编码标准库 官网
PHP Manipulator：一个分析和修改PHP源代码的库 官网
PHP Metrics：一个静态测量库 官网
PHP Refactoring Browser：一个重构PHP代码的命令行工具集 官网
UBench：一个简单的微型基准检测库 官网
Athletic：一个基于注释的基准检测库 官网
Mondrian： 使用使用图论的代码分析工具 官网
Scrutinizer：一个审查PHP代码的web工具 官网
PHPLOC：一个快速测量PHP项目大小的工具 官网
xHprof：另一个PHP分析工具 官网
PHPCheckstyle：一个帮助遵守特定的编码惯例的工具。 官网
调试

调试代码的库和工具

xDebug：一个调试和分析PHP的工具 官网
PHP Debug Bar： 一个调试工具栏 官网
PHP Console：一个web调试控制台 官网
Barbushin PHP Console：另一个使用Google Chrome的web调试控制台 官网
PHPDBG：一个交互的PHP调试器 官网
Tracy：一个简单的错误检测，写日志和时间测量库 官网
构建工具

项目构建和自动化工具

Go：一个简单的PHP构建工具 官网
Bob：一个简单的项目自动化工具 官网
Phake：一个PHP克隆库 官网
Box：一个构建PHAR文件的工具 官网
Phing：一个灵感来自于Apache Ant的PHP项目构建系统 官网
任务运行器

自动运行任务的库

Task：一个灵感来源于Grunt和Gulp的纯PHP任务运行器 官网
Robo：一个面向对象配置的PHP任务运行器 官网
Bldr：一个构建在Symfony组件上的PHP任务运行器 官网
导航

构建导航结构的工具

KnpMenu：一个菜单库 官网
Cartographer：一个站点地图生成库 官网
资源管理

管理，压缩和最小化web站点资源的工具

Assetic：一个资源管理的管道库 官网
Pipe：另一个资源管理的管道库 官网
Munee：一个资源优化库 官网
JShrink：一个JavaScript最小化库 官网
Puli：一个检测资源绝对路径的库 官网
地理位置

为地理编码地址和使用纬度经度的库。

GeoCoder：一个地理编码库 官网
GeoTools：一个地理工具相关的库 官网
PHPGeo：一个简单的地理库 官网
GeoJSON：一个地理JSON的实现 官网
日期和时间

处理日期和时间的库

Carbon：一个简单的日期时间API扩展 官网
ExpressiveDate：另一个日期时间API扩展 官网
CalendR：一个日历管理库 官网
事件

时间驱动或非阻塞事件循环实现的库

React：一个事件驱动的非阻塞I/O库 官网
Rx.PHP：一个reactive扩展库 官网
Ratchet： 一个web套接字库 官网
Hoa WebSocket：另一个web套接字库 官网
Hoa EventSource：一个事件源库 官网
Evenement：一个事件分发库 官网
FuelPHP Event：另一个事件分发库 官网
日志

生成和处理日志文件的库

Monolog：一个全面的日志工具 官网
KLogger：一个易用的PSR-3兼容的日志类 官网
电子商务

处理支付和构建在线电子商务商店的库和应用

OmniPay：一个框架混合了多网关支付处理的库 官网
Payum：一个支付抽象库 官网
Sylius：一个开源的电子商务解决方案 官网
Thelia：另一个开源的电子商务解决方案 官网
Money：一个Fowler金钱模式的PHP实现 官网
Sebastian Money：另一个处理货币值的库 官网
Swap：一个汇率库 官网
PDF

处理PDF文件的库和软件

Snappy：一个PDF和图像生成器库 官网
WKHTMLToPDF：一个将HTML转换为PDF的工具 官网
数据库

使用对象关系映射（ORM）或数据映射技术的数据库交互库

Doctrine：一个全面的DBAL和ORM 官网
Doctrine Extensions：一个Doctrine行为扩展的集合 官网
Propel：一个快速的ORM，迁移库和查询构架器 官网
Eloquent：Laravel 4 ORM 官网
Baum：一个Eloquent的嵌套集实现 官网
Spot2：一个MySQL的ORM映射器 官网
RedBean：一个轻量级，低配置的ORM 官网
Pomm：一个PostgreSQL对象模型管理器 官网
ProxyManager：一个为数据映射生成代理对象的工具集 官网
迁移

帮助管理数据库模式和迁移的库

PHPMig：另一个迁移管理库 官网
Phinx：另一个数据库迁移管理库 官网
Migrations：一个迁移管理库 官网
Doctrine Migrations：一个Doctrine迁移库 官网
NoSQL

处理NoSQL后端的库

MongoQB：一个MongoDB查询构建库 官网
Monga：一个MongoDB抽象库 官网
Predis： 一个功能完整的Redis库 官网
队列

处理事件和任务队列的库

Pheanstalk：一个Beanstalkd 客户端库 官网
HP AMQP：一个纯PHP AMQP库 P官网
Thumper： 一个RabbitMQ模式库 官网
Bernard：一个多后端抽象库 官网
搜索

在数据上索引和执行查询的库和软件

ElasticSearch PHP：ElasticSearch的官方客户端库 官网
Elastica：ElasticSearch的客户端库 官网
Solarium：Solr的客户端库 官网
SphinxQL query builder：Sphinx搜索引擎的的查询库 官网
命令行

构建命令行工具的库

Boris：一个微型PHP REPL 官网
PsySH：另一个微型PHP REPL 官网
Pecan：一个事件驱动和非阻塞内核 官网
GetOpt：一个命令行选择解析器 官网
OptParse：另一个命令行选择解析器 官网
Commando：另一个简单的命令行选择解析器 官网
GetOptionKit：另一个命令行选择解析器 官网
Cron Expression：计算cron运行日期的库 官网
ShellWrap：一个简单的命令行包装库 官网
Hoa Console：另一个命令行库 官网
Shunt：一个在多台远程机器上并行运行命令行的库 官网
Cilex：一个构建命令行工具的微型框架 官网
身份验证

实现身份验证的库

Sentry：一个混合的身份验证和授权的框架库 官网
Sentry Social：一个社交网络身份验证库 官网
Opauth：一个多渠道的身份验证框架 官网
OAuth2：一个OAuth2身份验证服务，资源服务器和客户端库 官网
OAuth2 Server：另一个OAuth2服务器实现 官网
PHP oAuthLib：另一个OAuth库 官网
TwitterOAuth：一个Twitter OAuth库 官网
TwitterSDK：一个完全测试的Twitter SDK 官网
Hawk：一个Hawk HTTP身份认证库 官网
HybridAuth：一个开源的社交登陆库 官网
标记

处理标记的库

Decoda：一个轻量级标记解析库 官网
PHP Markdown：一个Markdown解析器 官网
CommonMark PHP：一个对 CommonMark spec全支持的Markdown解析器 官网
Dflydev Markdown：另一个Markdown解析器 官网
Parsedown：另一个Markdown解析器 官网
Ciconia：另一个支持Github Markdown风格的Markdown解析器 官网
Cebe Markdown：一个快速的可扩展的Markdown解析器 官网
HTML5 PHP：一个HTML5解析和序列化库 官网
字符串

解析和处理字符串的库

ANSI to HTML5：ANSI到HTML5的转化库 官网
Patchwork UTF-8：一个处理UTF-8字符串的便携库 官网
Hoa String：另一个UTF-8字符串库 官网
Stringy：一个多字节支持的字符串处理库 官网
Color Jizz：处理和转换颜色的库 官网
UUID： 生成UUIDs的库 官网
Slugify：转换字符串到slug的库 官网
Urlify： 一个Django的 URLify.jsPHP通道 官网
Text： 一个文本处理库 官网
SQL Formatter：一个格式化SQL语句的库 官网
UA Parser： 一个解析用户代理字符串的库 官网
数字

处理数字的库

Numbers PHP：处理数字的库 官网
Math：处理大数字的库 官网
ByteUnits：在二进制和度量系统中解析,格式化和转换字节单元的库 官网
PHP Units of Measure：一个计量单位转换的库 官网
PHP Conversion：另一个计量单位转换的库 官网
LibPhoneNumber for PHP：Google电话号码处理的PHP实现库 官网
过滤和验证

过滤和验证数据的库

Filterus：一个简单的PHP过滤库 官网
Respect Validate：一个简单的验证库 官网
Valitron：另一个验证库 官网
Upload：一个处理文件上传和验证的库 官网
DMS Filter：一个注释过滤库 官网
MetaYaml：一个支持YAML,JSON和XML的模式验证库 官网
ISO-codes：验证各种ISO和ZIP编码的库(IBAN、SWIFT/BIC、BBAN、VAT、SSN、UKNIN) 官网
 REST API

开发REST-ful API的库和Web工具

Apigility：一个使用Zend Framework 2构建的API构建器 官网
Hateoas：一个HOATEOAS REST web服务库 官网
HAL：一个超文本应用语言（HAL)构建库 官网
Negotiation：一个内容协商库 官网
Drest：一个将Doctrine实体暴露为REST资源节点的库 官网
Restler：一个将PHP方法暴露为RESTful web API的轻量级框架 官网
缓存

缓存数据的库

Alternative PHP Cache (APC)：打开PHP伪代码缓存 官网
Cache：一个缓存库（Doctrine部分） 官网
Stash：另一个缓存库 官网
数据结构和存储

实现数据结构和存储技术的库

Ardent：一个数据结构库 官网
PHP Collections： 一个简单的集合库 官网
Serializer：一个序列化和反序列化数据的库 官网
PHP Object Storage：一个对象存储库 官网
Fractal：一个转换复杂数据结构到JSON输出的库 官网
Totem：一个管理和穿件数据交换集的库 官网
PINQ：一个PHP实时Linq库 官网
JsonMapper：一个将内嵌JSON结构映射为PHP类的库 官网
通知

处理通知软件的库

Nod：一个通知库（Growl等） 官网
Notificato：一个处理推送通知的库 官网
Notification Pusher：一个设备推送通知的独立库 官网
Notificator：一个轻量级的通知库 官网
部署

项目部署库

Pomander：一个PHP应用部署工具 官网
Rocketeer：PHP世界里的一个快速简单的部署器 官网
Envoy：一个用PHP运行SSH任务的工具 官网
Plum：一个部署库 官网
国际化和本地化

国际化（I18n）和本地化（L10n）

Aura.Intl：官网
第三方API

访问第三方API的库

Amazon Web Service SDK：PHP AWS SDK官方库 官网
S3 Stream Wrapper：Amazon S3流包装库 官网
Stripe：Stripe官方PHP库 官网
Campaign Monitor：Campaign Monitor官方PHP库 官网
Digital Ocean：Digital Ocean API 接口库 官网
Github：Github API交互库 官网
PHP Github API：另一个Github API交互库 官网
Twitter OAuth：Twitter OAuth工作流交互库 官网
Twitter REST：Twitter REST API交互库 官网
Dropbox SDK：Dropbox SDK官方PHP库 官网
Twilio：Twilio官方PHP REST API 官网
Mailgun：Mailgun官方PHP REST API 官网 
扩展

帮组构建PHP扩展的库

Zephir：用于开发PHP扩展，且介于PHP和C++之间的编译语言 官网
PHP CPP：一个开发PHP扩展的C++库 官网
杂项

不在上面分类中的有用库和工具

Spork：一个处理forking的库 官网
JSON Lint：一个JSON lint工具 官网
JSONPCallbackValidator：验证JSONP回调的库 官网
Pagerfanta：一个分页库 官网
Ruler：一个简单的无状态的生产环境规则引擎。 官网
LiteCQRS：一个CQRS(命令查询责任分离)库 官网
Sslurp：一个使得SSL处理减少的库 官网
OptionPHP 官网一个可选的类型库
Metrics：一个简单的度量API库 官网
Sabre VObject：一个解析VCard和iCalendar对象的库 官网
Annotations：一个注释库（Doctrine部分） 官网
Whoops：一个不错的错误处理库 官网
Finite：一个简单的PHP有限状态机 官网
LadyBug：一个dumper库 官网
Procrastinator：运行耗时任务的库 官网
Compose：一个功能组合库 官网
SuperClosure：一个允许闭包序列化的库 官网
Jumper：一个远程服务执行库 官网
Underscore：一个Undersccore JS库的PHP实现 官网
PHP PassBook：一个iOS PassBook PHP库 官网
PHP Expression：一个PHP表达式语言 官网
RMT：一个编写版本和发布软件的库 官网
Wise：一个配置管理器 官网
Opengraph：一个开放图库 官网
Essence：一个提取web媒体的库 官网
Embera：一个Oembed消费库 官网
Graphviz：一个图形库 官网
Monad PHP：官网 一个简单Monad库
Flux：一个正则表达式构建库 官网
Patchwork：一个重新定义用户的函数库 官网
Galapagos：语言转换进化 官网
Design Patterns PHP：一个使用PHP实现的设计模式存储库 官网
PHPCR：一个Java内容存储库（JCR)的PHP实现 官网
Functional PHP：一个函数式编程库 官网
ClassPreloader：一个优化自动加载的库 官网
Lib Country：一个国家和地区数据的库 官网
Lib Accessor：一个简化访问的库 官网
PHPStack：一个PHP编写的TCP/IP栈概念 官网
Nmap：一个Nmap PHP包装器 官网
Code Mover：一个移动代码的库 官网
Iter：一个使用生成器提供迭代原语的库 官网
Lambda PHP：一个PHP中的Lambda 计算解析器 官网
Country List：所有带有名称和ISO 3166-1编码的国家列表 官网
PHP-GPIO：用于Raspberry PI的GPIO pin的库 官网
print_o：一个对象图的可视化器 官网
Alias：一个类别名库 官网
软件

创建一个开发环境的软件

PHP安装

在你的电脑上帮助安装和管理PHP的工具

HomeBrew：一个OSX包管理器 官网
HomeBrew PHP：一个HomeBrew的PHP通道 官网
PHP OSX：一个OSX下的PHP安装器 官网
PHP Brew：一个PHP版本管理和安装器 官网
PHP Env：另一个PHP版本管理器 官网
PHP Switch：另一个PHP版本管理器 官网
PHP Build：另一个PHP版本安装器 官网
VirtPHP：一个创建和管理独立PHP环境的工具 官网
开发环境

创建沙盒开发环境的软件和工具

Vagrant：一个便携的开发环境工具 官网
Ansible：一个非常简单的编制框架 官网
Puppet：一个服务器自动化框架和应用 官网
PuPHPet：一个构建PHP开发虚拟机的web工具 官网
Protobox：另一个构建PHP开发虚拟机的web工具 官网
Phansible：一个用Ansible构建PHP开发虚拟机的web工具 官网
虚拟机

相关的PHP虚拟机

HipHop PHP：Facebook出品的PHP虚拟机，运行时和JIT 官网
HippyVM：另一个PHP虚拟机 官网
Hack：一个PHP进行无缝操作的 HHVM编程语言 官网
IDE

支持PHP的集成开发环境

Netbeans：一个支持PHP和HTML5的IDE 官网
Eclipse for PHP Developers：一个基于Eclipse平台的PHP IDE 官网
PhpStorm：一个商业PHP IDE 官网
Web应用

基于Web的应用和工具

3V4L：一个在线的PHP shell 官网
DBV：一个数据库版本控制应用 官网
PHP Queue：一个管理后端队列的应用 官网
Composer as a Service：作为一个zip文件下载Composer包的工具 官网
MailCatcher：一个抓取和查看邮件的web工具 官网
资源

各种提高你的PHP开发技能和知识的资源，比如书籍，网站，文章

PHP网站

PHP相关的有用网站

PHP The Right Way：一个PHP最佳实践的快速指引手册 官网
PHP Best Practices：一个PHP最佳实践指南 官网
PHP Weekly：一个PHP新闻周刊 官网
PHP Security：一个PHP安全指南 官网
PHP FIG：PHP框架交互组 官网
PHP UG：一个帮助用户定位最近的PHP用户组（UG)的网站 官网
Seven PHP：一个PHP社区成员采访的网站 官网
Nomad PHP：一个在线PHP学习资源 官网
PHP Mentoring：点对点PHP导师组织 官网
其他网站

Web开发相关的有用网站

The Open Web Application Security Project (OWASP)：一个开放软件安全社区 官网
WebSec IO：一个Web安全社区资源 官网
Web Advent：一个Web开发人员日历 官网
Semantic Versioning：一个解析语义版本的网站 官网
Atlassian Git Tutorials：一个Git教程系列 官网
Hg Init：一个Mercurial教程系列 官网
Servers for Hackers：一个关于服务器管理的新闻通讯 官网
PHP书籍

PHP相关的非常好的书籍

Scaling PHP Applications：一本Steve Corona关于扩展PHP应用程序的电子书 官网
The Grumpy Programmer’s Guide to Building Testable PHP Applications：一本Chris Hartjes关于构建PHP应用程序测试的书 官网
Grumpy PHPUnit：一本Chris Hartjes关于使用PHPUnit进行单元测试的书 官网
Mastering Object-Orientated PHP：一本Brandon Savage关于PHP面向对象的书 官网
Signaling PHP：一本Cal Evans关于在CLI脚本捕获PCNTL 信号的书 官网
Securing PHP: Core Concepts：一本Chris Cornutt关于PHP常见安全条款和实践的书 官网
Modernising Legacy Applications in PHP：一本Paul M.Jones关于遗留PHP应用进行现代化的书 官网
其他书籍

与一般计算和Web开发相关的书

The Linux Command Line：William Shotts关于Linux命令行的一本书 官网
Understanding Computation：Tom Stuart关于计算理论的一本书 官网
The Tangled Web — Securing Web Applications： Michal Zalewski关于web应用安全的一本书 官网
Elasticsearch: The Definitive Guide：Clinton Cormley和Zachary Tong编写的与Elasticsearch工作的一本指南 官网
Eloquent JavaScript：Marijin Haverbeke关于JavaScript编程的一本书 官网
Vagrant Cookbook：Erika Heidi关于创建 Vagrant环境的一本书 官网
Pro Git：Scott Chacon和Ben Straub关于Git的一本书 官网
PHP视频

PHP相关的非常不错的视频

Taking PHP Seriously：来自Facebook Keith Adams 讲述PHP优势 官网
PHP Town Hall：一个随意的Ben Edmunds和Phil Sturgeon的PHP播客 官网
Programming with Anthony：官网  Anthony Ferrara的视频系列
PHP阅读

PHP相关的阅读资料

Create Your Own PHP Framework：一部Fabien Potencier的关于如何创建你自己的PHP框架的系列文章 官网
Seven Ways to Screw Up BCrypt：一篇关于纠正BCrypt实现的文章 官网
Preventing CSRF Attacks：一篇组织CSRF攻击的文章 官网
Don’t Worry About BREACH：一篇关于BREACH攻击和CSRF令牌的文章 官网
On PHP 5.3, Lamda Functions and Closures：一篇关于lambda函数和闭包的文章 官网
Use Env：一篇关于使用unix环境帮助的文章 官网
Composer Primer：Composer初级 官网
Composer Versioning：一篇关于Composer版本的文章 官网
Composer Stability Flags：一篇关于Composer稳定性标志的文章 官网
Innocent Villagefolk or a Pillagin’ Pirate?：一篇关于PHP从其他语言获取想法的文章 官网
Predicting Random Numbers in PHP：一篇关于生成随机数的文章 官网
A 20 Point List for Preventing XSS in PHP：一篇关于组织XSS的文章 官网
PHP Sucks! But I Like It!：一篇关于PHP利弊的文章 官网
PHP Is Much Better Than You Think：一篇关于PHP语言和生态圈的文章 官网
PHP内核阅读

阅读PHP内核或性能相关的资料

PHP RFCs：PHP RFCs主页（请求注解） 官网
PHP Internals Book：一本由三名核心开发编写的关于PHP内核的在线书 官网
Print vs Echo, Which One is Faster?：一篇关于打印和echo性能的文章 官网
The PHP Ternary Operator. Fast or Not?：一篇关于三元操作性能的文章 官网
Disproving the Single Quotes Myth：一篇关于单引号，双引号字符串性能的文章 官网
You’re Being Lied To：一篇关于内核ZVALs的文章 官网
How Long is a Piece of String：一篇关于字符串原理的文章 官网
Understanding OpCodes：一篇关于伪代码的文章 官网
How Foreach Works：StackOverflow 关于foreach回答的详情 官网
When Does Foreach Copy?：一篇关于foreach原理的文章 官网
How Big Are PHP Arrays (And Values) Really?：一篇关于数组原理的文章 官网
Why Objects (Usually) Use Less Memory Than Arrays：一篇关于对象和数组原理的文章 官网
PHP Evaluation Order：一篇关于PHP评估顺序的文章 官网
开发人员的PHP源代码： 1 2 3 4：关于PHP源代码的系列
垃圾收集： 1 2 3 关于PHP垃圾收集原理的系列
