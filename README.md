# SecurityInterviewQuestions
网络信息安全从业者面试指南

1.理解安全行业现状 -> 2.安全从业人员必备素质 -> 3.好的简历 -> 4.招聘渠道 -> 5.安全面试流程 -> 6.安全面试和笔试题目

## 一、安全行业现状
### 1.1 薪酬最高
互联网是计算机行业中薪酬最高的，而技术工程师是互联网中薪酬最高的，而安全工程师又是技术工程师中最高的。安全行业井喷式的爆发，使得每家互联网企业的安全部门成为标配并逐渐蔓延开来，而由于高校的安全专业才开始普及，安全从业人员紧缺且入门门槛较高从而导致了薪酬水涨船高。

### 1.2 良莠不齐
好处是会有更多的人投身于安全，当然坏处也很明显，着急的岗位和紧缺人员导致存在大量良莠不齐的人在其中浑水摸鱼，明显的特征是你跟他聊技术细节他跟你聊推进落地，你跟他聊推进落地他跟你聊方向把控，你跟他聊方向把控他跟你聊团队管理，你跟他聊团队管理他跟你聊行业空间，如果这些方面都能聊一点那也行，更多的人是**答非所问**又或者**句句有理但空洞没有屁用**，又或者是今天这里听到一个理论还没弄明白呢明天就来跟你拽个概念，虽然这么说会得罪一部分人。

### 1.3 圈子文化
安全是一个小圈子，圈内的事情传播的非常快，比如谁家数据库泄露了、谁家被薅羊毛了、谁被抓了、谁被处罚了，这也是小圈子最大的好处，圈内的人很快能知道这个行业的新技术、新方向、新政策。你也可以很容易的知道每家公司的安全建设情况，比如你可以和阿里的人聊他们的线下配合公安的手段有多强，也可以和腾讯的人聊他们的SRC如何运营的这么好，也可以和百度的安全人聊如何让机器学习赋能安全产品的，这一切在安全圈内非常的容易。也有很多的安全会议可以学习到每家公司的经验，不用所有的事情都自己摸索也用闭门造车。
弊端也很明显，搞所谓的”圈子文化“，混迹于各种会议去主动认识各种圈内的人（当然这里不是指各家SRC运营的同学，这些是运营同学的工作一部分），认识的各种人如果是交流技术那也行，加了微信除了打招呼的自我介绍那句话就再也没说过有意义的东西，以为这样就进入了圈中心，可笑可悲。

### 1.4 安全起步晚
安全行业整体起来才没几年，多数企业因为资源投入和建设时间原因导致覆盖面和深入度都不够，这其中甚至包括一些国内大厂。其安全水位仅能应付一些白帽子级别，针对专业安全团伙持续定向攻击，大多数都不能防御住，看HW就知道了。

### 1.5 安全难以衡量
很多事情是有因果关系的，前面讲到的良莠不齐的根因在于很难通过结果来判断安全建设的水位。很多团队的KPI是不出安全事故，什么事都不做也不会出安全事故。造就了吹嘘拍马的人能够风生水起。但随着随着实战红蓝演练的普及，国家级别的实战攻防演练的，逐渐用模拟的方式来检验实战效果，能一定程度上解决此问题。

### 1.6 学历相对不那么重要
安全圈存在很多无学历或低学历的牛人，他们年龄可能不大、工作可能不久，但往往都兴趣驱动做安全，很早就开始在安全上投入了大量的时间，因此安全能力都很好。当长版特别突出时，往往也可以突破企业的一些要求限制，比如所有岗位几乎都是要求本科，但当你能力特别突出时，这些是可以商量的。但同时，也必须正确的认识到学历带来的影响，在当前安全越来越细分和深入的趋势下，不再是会挖漏洞就行的。建议通过自考的方式系统的学习下英语、数学以及计算机基础，并拿到一个国家承认的成人教育学历。在此基础上持续学习，拿到本科、研究生学历，届时学历对你就真的不重要了。

## 二、安全从业人员的必要素质
> 具备基础的工程师素质是一切的基础，在这个基础之上如果在攻防渗透和软件开发、兴趣驱动和适应能力上比较亮眼，则能很好的适应工作挑战。

### 2.1 攻防渗透和软件开发
首先要明确一个概念，术业有专攻在安全行业不是常态。安全本身就是一个覆盖了客户端、前端、网络、后端、服务器等涉及JavaScript、Python、PHP、Java等各语言的工作，如果非要讲究术业有专攻就没法做了，当你可以有擅长的方向，但前提是你都懂，这个懂不应该停留在了解的层面，如果你是安全开发工程师除了研发技能外还必须知道常见漏洞的形成原因、利用方式和修复方案，如果你是渗透工程师除了理解各种漏洞的攻击细节外，还必须有基本的开发能力。同时拥有攻防渗透和软件开发的人，在后面做事的方方面面会体现出极大的优势。
我们有过很资深研发工程师，但安全产品不同于用户产品，往往是都没有经验也没有参照物的，摸黑前行最好的情况是你曾住过这个房子，所以往往需要有很强的安全背景/不断的试错调整才能开发最好的产品。甚至在很多时候，沟通交流/思维上都需要进行转变才能更好的协作，减少代沟和沟通成本。这个要求并不是非要精通各种。
现状是安全行业更多的人是偏向于攻防渗透，而如果同时拥有很强的开发技能，优势将非常明显。在安全产品开发/漏洞挖掘/代码审计上。不同岗位间的互补显得非常重要，做漏洞扫描器的如果在SRC挖过漏洞、做代码审计如果会软件开发、做合规审计的如果有CISP证书就会得心应手。
### 2.2 兴趣驱动
像安全产品开发一样，渗透测试也需要不断的试错，不断的将各种可能存在漏洞的地方一一测试，往往测试数百个请求才有所收获，这需要很好的坚持，但坚持这种品质无法立刻学会，但往往有很多东西能促使我们坚持，比如兴趣。我对于安全的坚持就是兴趣所驱动的，我会遇到一个线索从早上折腾到凌晨，会因为一个突破点从晚上摸索到下午。 我见过太多优秀的白帽子都是因为热爱，他们能跨行业的热爱。
### 2.3 适应能力
软件工程师是三年换一轮新技术，而安全工程师则是每年都有新的方向。每天都会有新的漏洞/新的攻击方式/新的语言漏洞，每年也会有新的安全技术、安全防御手段、安全方向，而应对别无他法唯学习，良好的自驱自学能力是一切的基础。
## 三、好的简历
> 如何写出一份清晰明了的简历是基础，当然一切的前提是有真才实干。

整体要简洁明了，逻辑结构清晰。要能体现出知识、技能、经历、天赋、人脉。

- 基本信息**清晰**：姓名、ID、性别、年龄、毕业院校·专业、电话、邮箱、居住地
- 工作&项目经验：注意空档期、担任的角色与分工、公司行业知名度
- **体现**技术能力：主要的技术栈以及能佐证的事情
- 其它**优势**：职业证书、奖项、会议分享、开源项目等
- 工作期望和方向：希望得到一个什么样的工作或自己专注的方向
- 个人评价：全方位的总结，展示出自己的专业技能掌握程度、亮点、优势等等。
- 加分项
   - 使用PDF格式，简洁不花哨
   - 有GitHub并参与过开源项目，可以写一些自己做过的小项目放上去
   - 有个人博客，会写一些经验和问题的解决思路
   - 邮箱使用gmail、foxmail或技术类邮箱（[php.net](http://php.net/)）、私人域名邮箱等
- 询问面试官对于自己的评价和可以改进的地方
## 四、招聘渠道
### 4.1 公司内部推荐
> 内推是优于招聘网站或猎头的，和找女朋友一样，熟人介绍的比媒婆介绍的要好，更不用说相亲网站的质量了。大企业内部多数都是内推进来的。对于中高端岗位公司需要支付较高的猎头费用，所以内推渠道优于其它所有。

- 找到自己倾向的公司以及对应的招聘岗位
   - 注意岗位和个人技能及职业发展的匹配度
- 找到对应公司员工请求内部推荐简历（如果没有熟悉的人，可以通过`feei#feei.cn`联系我，可帮忙内推国内多数互联网公司）
   - 优先安全岗位的，其次同公司的
   - 优先熟悉自己的，其次自检写好
### 4.2 安全行业招聘网站
> 没有合适心仪的目标就上招聘网站。

- [FreeBuf](https://job.freebuf.com/) - 安全行业垂直招聘网站
- [拉钩](https://www.lagou.com/zhaopin/wangluoanquan/) - 互联网垂直招聘
- [BOSS直聘](https://www.zhipin.com/c101210100-p100407/) - 负责人1对1
- [猎聘](https://www.liepin.com/zpwangluoanquan/) - 猎头招聘
- 智联招聘、前程无忧、LinkedIn
## 五、安全面试流程
> 如何有效的甄别一些滥竽充数的人，最重要的肯定是面试这道坎。安全圈的东西行业内的人谁都能聊一点，所以一轮面试一定得安全技术负责人亲自把关，深入的问细节来判断。

### 5.1 提前准备

- 仔细看下面试者简历，看看GitHub项目情况、看看论文质量、看看SRC排名、看看演讲访谈，记录下需要特别关注的点。
- 提前约好面试时间和面试方式（电话/现场）
- 准时参与面试，有事情应提前电话沟通到位
### 5.2 面试开始

- 询问对方当前是否方便讲话。
- 面试官自我介绍，可以讲下本次主要考察的点。
- 让面试者自我介绍下个人情况、做过的项目和技能
- 观察谈吐，看思维逻辑是否有条理，沟通交流是否顺畅.性格类型是否合适
### 5.3 面试注意项

- 面试时把握好节奏，把控面试节奏，及时阻止发散的，多留停顿给话少的
- 面试时不问/不透露公司敏感信息
- 即使只聊一分钟就觉得面试者不合适，也不应该立即挂断，面试应不少于20分钟
### 5.4 技术功底
询问技术问题时切忌不可像机器人一样一个个预先准备好的问题砸向对方，理想状态下应该是把我们所关注的问题在对方介绍自己项目、技能时无缝插入进去。
• 参考安全笔试题目，根据做过的项目进行挑选问题进行提问 • 考察项目真实性、项目角色及分工 • 对项目的理解程度、掌握程度、思考等 • 岗位专业问题（见下一篇）
### 5.5 基础素质

- 遇到解决不了的问题怎么做？
   - 考察学习能力和动手解决能力
- CTF、乌云、翻墙、写技术博客、参与开源、常浏览的网站、游戏、电视剧、业余时间干嘛、业内牛人
   - 综合体现出其技术热度
- 算法、前端、服务器的掌握程度
   - 一些基础算法，比如快速排序、冒泡排序、选择排序、插入排序
   - 一些机器学习算法，CNN、RNN、Tensorflow、验证码识别等等
   - 前端JavaScript、HTML、CSS掌握程度，调试工具，编码等
   - 服务器常用命令、配置、文件权限、进程栈、端口占用、异常日志等
- 自认为自己比身边人的优势
   - 挖掘亮点，如何客观看待自己
- 自认为的缺点
   - 客观的自我评价，讲自己没有缺点的基本可以不要了
- 最有成就感的事情
   - 考察价值观
- 未来职业规划？
   - 长远思考
- 还有什么要问我的吗？
   - 了解面试者所关心的侧重点
## 六、安全面试和笔试题目
### 6.1 面试题目
#### 渗透测试（Web方向）

- 挑选两到四个不同方向常见和不常见的漏洞，就漏洞原理、利用方式和修复方案进行提问，然后根据回答的情况进行详细深入的二次提问
   - Redis未授权访问漏洞如何入侵利用？
   - SSRF漏洞原理、利用方式及修复方案？Java和PHP的SSRF区别？
   - 宽字节注入漏洞原理、利用方式及修复方案？
   - 简述JSONP的业务意义，JSONP劫持利用方式及修复方案？如何设计落地一个CSRF Token？
   - CORS原理、利用及修复
   - CRLF注入原理？
   - URL白名单绕过？
   - XSS持久化？
   - TLS1.2协议交互过程以及攻击方法？
- 渗透全流程
- 信息收集
   - 域名爆破中，泛域名解析问题如何解决？
- 就漏洞的检测发现进行提问
   - 越权问题如何检测？
   - 黑盒如何检测XSS漏洞？
   - 如果爬取更多的请求？
   - 黑盒带登录态扫描如何规避业务影响？
- 安全评估
   - 某些场景（登录、注册、修改密码、支付）会存在哪些风险以及如何防范？
   - 新应用如何评估安全风险？
   - 需求阶段、系分阶段安全评估的侧重点是什么？
   - 接口B的参数是从接口A的响应中获取的，会存在什么风险？
   - Docker容器以及K8s有哪些风险？
   - IPv6和IPv4安全差异？
- 移动安全
   - App自检升级场景下会存在哪些风险？
   - 如何设计一套通信机制，能够保证传输过程中的完整性、不可抵赖性以及防止重放？
   - 如何进行实体检测？
   - 常见的调试方法和检测方法？
   - 如何防止Frida、Xposed等注入攻击？
   - 如何防止当前设备的数据拷贝到其他设备？
- 应急思考
   - 有哪几种后门实现方式？
   - webshell检测有什么方法思路？
   - Linux服务器中了木马后，请简述应急思路？
   - 遇到新0day(比如Struts2)后，应该如何进行应急响应？
   - 新业务上线前可以从哪些方向进行安全评估？
   - 现有系统可以从哪些方向进行审计发现其中的安全风险？
   - 公司突然爆发大规模数据泄露导致的诈骗事件，如何应急？
- 基础开发
   - 简述Python装饰器、迭代器、生成器原理及应用场景？
   - 简述Python进程、线程和协程的区别及应用场景？
#### 安全开发（Java方向）

- Java基础
   - Java虚拟机区域如何划分？
   - HashMap和HashTable、ConcurrentHashMap的区别？
   - 进程和线程区别，进程间、线程间通信有哪几种方式？
   - Java BIO/NIO/AIO是什么？适用哪些场景？
- 算法基础
   - 快速排序的过程和复杂度？
   - 冒泡排序的过程和复杂度？
   - CNN对比RNN区别？
- 业务基础
   - 调试工具及异常排查流程？
   - 数据库索引结构，什么情况下应该建唯一索引？
   - 数据库分页语句如何写？
- 业务安全
   - HTTPS交互过程
   - OAuth2.0交互过程及其中可能存在的配置不当安全风险
   - 对称加密和非对称加密的区别及优缺点
   - 获取一个入参url，请求url地址的内容时应注意什么？
   - 参数入库前应该如何过滤？
   - 过滤器和拦截器原理和应用场景？
   - SESSION ID如何不被Javascript读取？
   - CSRF的Token如何设计？
   - 同源策略？如何实现跨域请求？
#### 威胁感知（数据分析）

- 如何在加密流量中检测出恶意流量？
- 常见的C&C通道种类和检测方法？
- 主机有哪些日志对安全有哪些帮助？
- 如何实现URL的去重？
- 如何识别公共和私有接口？
- 如何识别机器行为请求？
- 如何识别异常服务器外联？
- 如何识别攻击请求是定点攻击还是随机扫描？
- 如何识别钓鱼网站？
- 基于网络五元组可以做到哪些风险行为的分析？
#### 数据安全

- 数字水印的类型和应用领域？
- 哪些Hash和加密算法不建议使用？
- 硬编码秘钥如何解决？
- PKI原理
- 密码应该如何保存？
- 如何在不拿到明文数据的前提下，还能通过数据进行一些计算行为？
#### 安全运营（合规审计方向）

- 金融行业和传统互联网行业合规差异
- 对于内控、合规、审计的理解
   - 考察其对于要做的事情和岗位要求、公司环境是否匹配
   - 考察其大局上考虑是否周全或是片面
- 传统行业和互联网行业的安全建设的区别及各自的优劣势
   - 是否能准确的抓住核心原因
- 信息安全等级保护、网络安全法、GDPR
   - 挑选一到两个问其对其的来源理解以及落地程度取舍
- 数据安全治理可以用什么思路做？
- 如何通过技术手段实现对异常操作的自动化监控？
- 如何对一个应用进行安全评估？
- 如何对一个应用进行安全审计？
- 如何理解权限分离、最小化权限？
- 考察一些CISP、CISSP的知识点
- 流程的设计
   - 挑选一些较为复杂的流程，比如转岗、离职等，如何设计考虑其中的细节
#### 安全架构（安全管理方向）

- 传统IDC、云上、混合云架构的安全差异和各自挑战是什么？
- 纯云业务如何设计安全架构？
- SDL中的关键点是什么以及如何解决？
- 如何防止0day攻击？
- 渗透测试、安全研发、安全运营的问题可以挑选的问一些，以确保在各个方向上比较均衡
- 对于企业不同时期、不同阶段、不同体量的安全建设的方法、区别以及侧重
- 你所做过的安全架构图和所期望的安全架构
- 安全与其他团队（运维、研发、测试、GR/PR、内控、高管及三方安全公司）的关系
- 安全建设的理念/方法论理解
   - 纵深防御
   - 木桶原理
   - 由外而内
   - 先低后上
   - 能口不点
   - 最小权限
   - 权限分离
   - 白名单和黑名单
   - 漏洞和误报
   - 规则经验和机器学习
   - 漏洞危害证明
   - 技术管控与意识提升的关系
   - 安全推进方法
   - 自研OR外采？
   - 找到总的核心目标和各个项目的主要目标
   - 创新和极致
   - 责任分担
   - 黑天鹅和灰犀牛
- 衡量企业安全建设的水平
- 不同公司间的安全区别或差别是什么？比如腾讯和阿里，百度和京东
- 如何制定公司安全建设的三年甚至五年计划
- 未来安全行业的发展方向？
### 6.2 笔试题目
> 面试题目往往大同小异，而由于圈子小的原因很容易传播出去，如果做过准备哪怕深入的问也可能有漏网之鱼。而笔试往往能很好的看出来其动手能力，所以应尽可能的出一些无法提前预知、无法网上查询的专属题目，题目可以侧重于开发、调试、数据操作等方面。

#### 渗透测试方向

- 给定一个漏洞靶场，在一定时间内找出最多漏洞数
- 给定一个匿名访问Redis，请GET SHELL
- 给一个项目场景进行安全评估（e.g.与三方厂商进行API交互）
#### 代码审计方向

- 给定一些包含漏洞（建议SSRF、反序列化、营销活动）的代码，使其发现漏洞或风险、利用漏洞、修复漏洞
#### 软件开发方向

- 读取一个文件第100-200行并发送到一个指定的API接口（着重考察对于各种异常情况的考虑）
- 最快的方式获取100万个子域名请求的响应内容并找出其中真实存在的子域名
#### 数据结构方向

- 给一个数组`[3,4,5,6,2,1,8]`，输入所有二元组其和为8。
   - 每个数字只能用一次
   - 数组长度不定
   - 考虑时间复杂度和空间复杂度，以最高效率
- 存在一个list结构（表1），请转换为树状结构（表2）
   - pid和id关系为父子关系
   - name为无规律随意命名

表1：list结构（list length>1000）
```
[
    {
    'id': '111',
    'pid': '0',
    'name': 'A1'
    },
    {
    'id': '222',
    'pid': '111',
    'name': 'A-B1'
    },
    {
    'id': '223',
    'pid': '111',
    'name': 'A-B2'
    },
    {
    'id': '224',
    'pid': '111',
    'name': 'A-B3'
    },
    {
    'id': '333',
    'pid': '223',
    'name': 'A-B2-C1'
    },
    {
    'id': '444',
    'pid': '333',
    'name': 'A-B2-C1-D1'
    }
]
```
表2：最终的结构
```
{
  'id': '111',
  'pid': '0',
  'name': 'A1',
  'child': [
    {
      'id': '222',
      'pid': '111',
      'name': 'A-B1'
    },
    {
      'id': '223',
      'pid': '111',
      'name': 'A-B2',
      'child': [
        {
          'id': '333',
          'pid': '223',
          'name': 'A-B2-C1',
          'child': [
            {
              'id': '444',
              'pid': '333',
              'name': 'A-B2-C1-D1'
            }
          ]
        }
      ]
    },
    {
      'id': '224',
      'pid': '111',
      'name': 'A-B3'
    }
  ]
}
```
