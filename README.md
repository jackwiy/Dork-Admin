<p align="center">
    <img src=".//img/logo.png">
</p>

---

## Manual🎟
盘点近年来的各国各行较知名的数据泄露事件

灵感来源: https://haveibeenpwned.com/PwnedWebsites

消息源: [haveibeenpwned](haveibeenpwned)、[securityaffairs](https://securityaffairs.co/wordpress/tag/data-leak)、[hackernews](http://hackernews.cc/archives/category/%E6%95%B0%E6%8D%AE%E6%B3%84%E9%9C%B2)、[Freebuf](https://www.freebuf.com)、[bleepingcomputer](https://www.bleepingcomputer.com)、[zdnet](https://www.zdnet.com)、[Solidot](https://www.solidot.org)

<p align="center">
    <img src=".//img/readme.jpg">
</p>


# 2019🤦‍
**1月**
- **德国政界** 数百德国政客个人数据泄露
```
泄露目标：除极右翼民主党以外的所有其他政党，其中还包括一些名人和记者。
泄露内容：电子邮件地址、手机号码、身份证照片以及相当一部分聊天记录
事件经过：据BBC、路透社等多家海外媒体报道，所有泄露的信息都是通过一个名为“G0d”的Twitter帐户在之前的数周内放出的，账户信息显示，该账户目前有粉丝约17000人，地址位于汉堡，并使用了“安全研究”、“艺术家”、“讽刺与反讽”等标签形容自己。
```

- **华硕** 内网密码在 GitHub 上泄露
```
泄露内容：企业内网密码
事件经过：北京时间3月28日早间消息，据美国科技媒体TechCrunch报道，一名信息安全研究员两个月前向华硕发出警告称，有华硕员工在GitHub代码库中错误地发布了密码。这些密码可以被用于访问该公司的企业内网。其中一个密码出现在一名员工分享的代码库中。通过该密码，研究员可以访问内部开发者和工程师使用的电子邮件帐号，从而与计算机的使用者分享夜间构建的应用、驱动和工具。有问题的代码库来自华硕的一名工程师，他将电子邮件帐号密码公开已有至少一年时间。目前，尽管GitHub帐号仍然存在，但这个代码库已被清理。
link: http://hackernews.cc/archives/25173
```

**3月**
- **SkyMed** Database Exposes Medical Info, PII Data of 137k People in U.S.
```
影响人数：137k People
泄露目标：SkyMed members
泄露内容：full names, addresses, dates of birth, email addresses, phone numbers
link: https://www.bleepingcomputer.com/news/security/database-exposes-medical-info-pii-data-of-137k-people-in-us/
```

**4月**
- **Bilibili** 网站后台工程源代码被上传至[Github](https://github.com/openbilibili)(ikun大胜利?),官方回应:较老版本，已报案
```
影响人数：1亿bog
泄露目标：bilibili
泄露内容：网站后台工程源代码
大致时间：2019年4月22
事件经过：大家好，我是练习时长两年半的灭霸，爱好是唱跳rap篮球music~,打一下响指死一半bog
```

- **Docker Hub** 未经授权的访问者访问了Docker Hub的数据库，可能导致泄露19万用户敏感数据
```
影响人数：19万
泄露目标：Docker Hub用户
大致时间：2019年4月
事件经过：官方发送的安全通知，Docker于2019年4月25日发现有未经授权的访问者访问了Docker Hub的数据库。
在进行调查之后，确定该数据库包含大约190000个用户的敏感信息。这些信息包括用于Docker自动编译的GitHub和Bitbucket存储库的访问令牌以及一小部分用户的用户名和密码哈希值。
```

- **京东** 疑似泄露5千万用户数据,官方回应:谣传
```
影响人数：5000万
泄露目标：京东用户
大致时间：2019年4月
```

- **领英** 某AWS开放数据库泄露6000万条领英用户信息记录,官方回应:不是我们的数据库
```
影响人数：6000万
泄露目标：领英用户
泄露内容：数据中包含领英个人资料信息，包括ID、个人资料网址、工作经历、教育经历、住址、技能、其他社交个人资料以及个人资料上次更新的时间。
大致时间：2019年4月
事件经过：近日，研究人员发现了八个不安全的数据库泄露了约6000万条领英用户信息记录。虽然大多数信息是公开的，但数据库中包含领英用户的电子邮件地址。
```

- **Facebook** 再被指泄漏用户数据，至少5.4亿用户资料任由下载(厉害了，又是你facebook)
```
影响人数：至少5.4亿名用户
泄露目标：Facebook 用户
大致时间：2019年4月
事件经过：据《彭博社》报导，网络保安公司 UpGuard 在亚马逊云端数据库上发现大量 Facebook 用户的个人资料，涉及至少5.4亿名用户，且数据开放予任何人下载。报导指出，墨西哥城媒体公司 Cultura Colectiva 的数据库储存了5.4亿名 Facebook 用户的个人资料，包括身份证号码、帐号称谓、网上评论及回应记录等。Cultura Colectiva 专门发布拉丁美洲娱乐及文化消息，在 Facebook、Instagram、Twitter、YouTube 等开设专页，拥有逾4500万用户追踪。《彭博社》向 Facebook 查询，Facebook 随后通报亚马逊，相关数据库已被封锁。Facebook 发言人表示，公司政策禁止将用户资料储存于公开数据库，此次发现事件后即时通知亚马逊处理；发言人称，公司致力与平台开发商合作保障用户私隐。
```

**5月**
- **三星** 多个项目代码泄露 包括SmartThings源代码和密钥
```
泄露内容：多个内部项目，包括三星SmartThings敏感的源代码、证书和密钥。
事件经过：三星数十个自主编码项目出现在旗下Vandev Lab的GitLab实例中。该实例被三星员工用于分享并贡献各种应用、服务和项目的代码。由于这些项目被设置为“公开”，同时没有受到密码的保护，因此任何人都可以查看项目，获取并下载源代码。迪拜信息安全公司SpiderSilk的安全研究员莫撒布·胡赛因（Mossab Hussein）发现了这些泄露的文件。他表示，某个项目包含的证书允许访问正在使用的整个AWS帐号，包括100多个S3存储单元，其中保存了日志和分析数据。
link: http://hackernews.cc/archives/25425
```

- **Ladders** Database Exposed 13M User Records
```
影响人数：13M User
泄露目标：Ladders User
link: https://securityaffairs.co/wordpress/84861/data-breach/ladders-data-leak.html
```

- **Instagram** 4900万条数据曝光，影响人数达数百万
```
影响人数：4900万条记录
泄露目标：Instagram用户
大致时间：2019年5月
泄露内容：用户资料、图片、粉丝数据、以及验证过的国家/地区、私人联系信息（包括电话、电子邮件等），甚至还有用户已删除信息内容。
事件经过: 据TechCrunch网站报道，Instagram的一个大型数据库由于在AWS存储桶上没有受到保护，导致任何人都可以在没有身份验证的情况下访问它。该数据库首先由安全研究人员Anurag Sen发现，并立即报告给了TechCrunch网站。
link: https://securityaffairs.co/wordpress/85905/data-breach/instagram-data-leak.html
```

- **Hindustan** 大量员工和商业信息公开暴露
```
泄露目标：Hindustan雇员、应聘者
大致时间：2019年5月
泄露内容：包括新雇员的个人信息和明文密码、客户基础设施安装报告以及管理人员的Web应用程序,应聘者的ID、姓名，手机号码、加入日期、加入地点、招聘人员SAP代码、招聘人员姓名、创建日期、用户名、明文密码、BGV状态、已接受的offer以及应聘申请表的链接。超过2,800名员工的名称和SAP代码,可以使用SAP代码和名称查找和’停用’员工”的界面,使用SmartManage报告系统管理的客户安装报告和项目数据,一份内部分析报告数据库，包含5700条事件记录、每周客户报告（约18,000个条目）以及可追溯到2016年的安装报告
link:https://www.freebuf.com/news/204276.html
```

- **优衣库** 遭到黑客攻击，超过46万用户数据泄漏
```
影响人数：46万用户
泄露目标：用户
大致时间：2019年5月
泄露内容：个人信息、电子邮件、地址以及部分信用卡资料
事件经过：日本最大的服装零售商迅销集团发布消息称，旗下优衣库以及GU品牌的在线商城遭到黑客攻击，约46万用户的数据泄漏，包括用户个人信息、电子邮件、地址以及部分信用卡资料等。迅销称，此事件仅限于日本网站，发生在4月23日至5月10日期间，是一次基于列表的攻击。当客户在多个网站上使用相同的用户名和密码组合时，可能会遭受此类攻击，建议用户更改密码。
link: https://www.freebuf.com/news/203923.html
```

- **OGUsers** 论坛遭遇了数据泄露,被竞争对手脱裤
```
影响人数：161,143
大致时间：2019年5月19日
泄露内容：Email addresses, IP addresses, Passwords, Private messages, Usernames
事件经过：In May 2019, the account hijacking and SIM swapping forum OGusers suffered a data breach. The breach exposed a database backup from December 2018 which was published on a rival hacking forum. There were 161k unique email addresses spread across 113k forum users and other tables in the database. The exposed data also included usernames, IP addresses, private messages and passwords stored as salted MD5 hashes.
link: https://haveibeenpwned.com/PwnedWebsites#OGUsers
```

- **Canva** 1.39 亿用户数据泄露
```
影响人数：1.39 亿
泄露目标：Canva 用户
泄露内容：用户名字、真名 、电邮地址、城市国家信息 、哈希密码、Google 令牌 、Gmail 地址
事件经过：自称 GnosticPlayers 的黑客声称窃取了澳大利亚网站 Canva 的 1.39 亿用户数据。Canva 是一个非常受欢迎的平面设计服务，Alexa 排名在 200 以内。黑客窃取的数据包括了用户名字、真名 、电邮地址、城市国家信息，其中 6100 万用户有哈希密码，其他用户的信息还有用于登陆的 Google 令牌。有 7800 万用户使用了 Gmail 地址。Canva 证实它的数据库遭到非法访问，表示尚未发现账号被入侵，出于谨慎考虑它已经鼓励用户更改密码。
link: https://www.zdnet.com/article/australian-tech-unicorn-canva-suffers-security-breach/
```

- **Ordine Avvocati di Roma** 遭到一个自称意大利匿名者的组织的数据泄露。
```
影响人数：41,960
泄露目标：罗马律师
泄露内容：Email addresses, Email messages, Geographic locations, Passwords, Phone numbers
事件经过：In May 2019, the Lawyers Order of Rome suffered a data breach by a group claiming to be Anonymous Italy. Data on tens of thousands of Roman lawyers was taken from the breached system and redistributed online. The data included contact information, email addresses and email messages themselves encompassing tens of thousands of unique email addresses. A total of 42k unique addresses appeared in the breach.
link: https://haveibeenpwned.com/PwnedWebsites#OrdineAvvocatiDiRoma
```

---

# 2018🤷‍
**2月**
- **MyFitnessPal** 1.5亿用户数据泄露
```
影响人数：1.5亿
泄露目标：MyFitnessPal用户
泄露内容：姓名、电子邮箱、加密密码
大致时间：2018年2月下旬
事件经过：美国著名运动装备品牌Under Armour称有1.5亿MyFitnessPal用户数据被泄露了，MyFitnessPal是一款在苹果和谷歌应用商店中很受欢迎的应用，跟踪用户每天消耗的卡路里、设置运动目标、集成来自其它运动设备的数据，还可以分享运动成果到类似Facebook这样的社交平台上。此次关于用户数据泄露的声明使得该公司的股票价格盘后下跌了2.4%。
```

**3月**
- **Facebook** 用户数据泄露，影响美国大选(小扎你看你就像个外星人)
```
影响人数：8700万
泄露目标：Facebook用户
泄露内容：个人资料、政治倾向、好友信息、私人消息
大致时间：2018年3月
事件经过：事件起源于Facebook与剑桥分析公司的合作，剑桥分析公司为了学术研究，在脸书上创建了一个应用预测用户性格喜好的APP用来测试，可是剑桥分析公司不仅收集了用户的测试结果，还在未经允许地情况下顺道收集了5000万用户在Facebook上的个人信息。
剑桥分析公司获得了5000万活跃用户数据后，建立起用户画像，通过计算机对每个用户的兴趣爱好、性格和行为特点进行精确分析，预测他们的政治倾向。然后定向向用户推送新闻，借助Facebook的广告投放系统，影响用户的投票行为。于是，Facebook对美国大选产生了难以推脱的影响。
```

**4月**
- **Panera** 3700万用户数据泄露
```
泄露内容:姓名、邮箱、地址、生日、信用卡账号后四位
```

- **TrueMove H** 遭遇数据泄露
```
影响人数：46000人
泄露内容：驾驶执照和护照
事件经过：运营商向在线客户公开存储在亚马逊AWS S3存储桶中的个人数据。泄露的数据还包括身份证件的扫描，数据一直保留至4月12日，当时该公司限制访问。
安全研究人员Niall Merrigan发现了大量数据，试图将此问题告知TrueMove H，但运营商没有回应。Merrigan透露，该AWS存储桶包含总计32GB的46,000条记录。
```

**6月**
- **A站** 官方宣传近千万条用户数据外泄(把用户数报高一点好让快手爸爸多给钱?)
```
事件经过: 北京时间 6 月 13 日凌晨，AcFun 发布公告称网站遭遇黑客攻击，近千万条用户数据外泄。呼吁 2017 年 7 月 7 日之后从未登陆过的用户以及密码强度低的用户及时更改密码。如果在其他网站使用与 A 站相同的密码，也应及时修改。
```

- **Exactis** 3.4亿人口总数据泄露
```
影响人数：3.4亿（2.3亿消费者数据，1.1亿企业数据）
泄露目标：互联网个人和企业用户
泄露内容：数据种类超过400类，包括电话号码、电子邮箱、邮寄地址、兴趣爱好、年龄、宗教信仰、宠物情况等。
大致时间：2018年6月
事件经过：美国市场营销公司Exactis采集了大约3.4亿条记录，大小约2TB，可能涵盖了2.3亿人的个人数据，几乎是全美的上网人口。Exactis此次的信息泄露并不是黑客撞库引起或者其它恶意攻击，而是他们自己的服务器没有防火墙加密，直接暴露在公共的数据库查找范围内。
```

- **MyHeritage** 9200万用户数据泄露
```
影响人数：9200万
泄露目标：MyHeritage用户
泄露内容：邮箱地址、加密密码
大致时间：公开于2018年6月
事件经过：网络安全研究人员于2018年6月对MyHeritage发出安全警告，发现外部服务器上存有敏感的MyHeritage信息。该公司确认信息真实性后立即发布通告，提醒用户立即更改密码，所有在2017年10月26日之前注册的帐户都存在泄露风险。
```

**7月**
- **汽车供应商 Level One** 数据泄露导致一百多家汽车厂商机密数据曝光
```
泄露目标：在全球 100 多家合作伙伴
泄露内容：与 Level One 合作的多家汽车制造厂商（包括特斯拉、通用、福特、大众等）的装配线、工厂原理图、保密协议；机器人的配置、规格、动画；蓝图；ID 凭证和VPN 访问请求表；客户联系信息等。涉及厂商超过 100 家。
大致时间：公开于2018年7月
事件经过：据多家外媒报道，7 月初，来自 UpGuard 安全团队的研究员 Chris Vickery 在网上发现了汽车供应商 Level One 的不安全数据库，数据库包括将近 47000 份文件，涵盖汽车制造厂商近十年的详细蓝图、工厂原理图、客户材料（如合同、发票、工作计划等），以及各种保密协议文件，甚至连员工的驾驶证和护照扫描件等隐私信息也包含在内。整个数据库的数据总量达 157 GB。Chris Vickery 表示，通过 Level One 的文件传输协议 rsync，可以不需要密码，直接访问他发现的这个数据库。
```

- **500px**
```
影响人数：1486万
泄露内容：出生日期，电子邮件地址，性别，地理位置，姓名，密码，用户名
大致时间：2018年7月5日
事件经过：In mid-2018, the online photography community 500px suffered a data breach. The incident exposed almost 15 million unique email addresses alongside names, usernames, genders, dates of birth and either an MD5 or bcrypt password hash. In 2019, the data appeared listed for sale on a dark web marketplace (along with several other large breaches) and subsequently began circulating more broadly. The data was provided to HIBP by a source who requested it to be attributed to "BenjaminBlue@exploit.im".
link: https://haveibeenpwned.com/PwnedWebsites#500px
```

**8月**
- **华住酒店** 被曝5亿条个人信息泄露在暗网兜售
```
今年8月份，网曝华住酒店集团旗下酒店用户信息在“暗网”售卖，售卖者称数据已在8月14日脱库。身份证号、手机号，一应俱全，共涉及5亿条公民信息。此次泄露的全部数据信息被卖家打包以8比特币出售（当时约合人民币38万元）。卖家还称，以上数据信息的截止时间为2018年8月14日。
```

- **Newegg** 5000万信用卡账号支付信息泄露
```
影响人数：5000万
泄露目标：Newegg在线消费者
泄露内容：信用卡账号
大致时间：2018年8月14日-9月18日
事件经过：网络犯罪团伙Magecart在Newegg网站上注入了信用卡略读代码。每当消费者在线购买东西时，支付信息会直接发送到Magecart的C＆C（命令和控制服务器）上。
```

**9月**
- **喜达屋酒店** 5亿条个人信息泄露
```
影响人数：5亿
泄露目标：喜达屋酒店消费者
泄露内容：姓名、电子邮箱、邮寄地址、电话号码、护照号码、帐户信息、出生日期、性别、旅行信息、住宿信息、信用卡信息等。
大致时间：2018年9月10日，但泄露真正发生时间可追溯到2014年。
事件经过：与很多其它官方违规声明一样，这家万豪旗下的连锁酒店发布了一份称其服务器遭受“未授权访问”的声明，一个顾客预订数据库被黑客入侵，可能有约5亿顾客的信息泄露。该消息公布后，万豪国际酒店股价在当天盘前交易中一度下跌逾5%。
```

**10月**
- **国泰航空** 数据泄露，940万乘客受影响
```
影响人数：940万
泄露目标：国泰航空乘客
泄露内容：乘客姓名；国籍；出生日期；电话号码；电邮地址；地址；护照号码；身份证号码；飞行常客计划的会员号码；顾客服务备注；及过往的飞行记录信息。
大致时间：公开于2018年10月24日
事情经过: 根据国泰航空的说法，他们于今年3月在系统中发现可疑活动后立即与网络安全公司合作进行调查，确定攻击者如何获得系统访问权限以及如何修复漏洞。调查进行至5月，国泰航空发现攻击者能够访问包含多达940万条乘客个人数据的系统。
```

**11月**
- **Amazon** 部分用户信息被泄露：包括姓名和邮件地址
```
影响人数：不详
泄露目标：Amazon用户
泄露内容：姓名、邮件地址
大致时间：2018年11月22日
事件经过：北京时间11月22日早间消息，据美国财经媒体CNBC报道，亚马逊向给用户发邮件称，由于出现技术问题，一些用户的姓名和邮件地址被泄露。目前已经有一些人在网上发布他们收到的邮件截图。这些邮件中说，用户没有必要因此次事故而修改密码。但CNBC指出，有了名字和邮件地址，黑客仍然可以借此重设用户帐号，或利用邮件发起“钓鱼攻击”。
link: http://hackernews.cc/archives/24486
```

**12月**
- **Quora** 1亿用户数据因为第三方黑客恶意攻击而遭到泄露
```
影响人数：1亿
泄露目标：Quora用户
泄露内容：姓名、电子邮箱、加密密码、个人资料
大致时间：公开于2018年12月3日
事件经过：12月3日，美国知名问答社区 Quora 发公告称，1亿用户数据因为第三方黑客恶意攻击而遭到泄露，其中包括用户的邮箱、姓名和被加密的密码，以及他们在网站上分享的内容。
link: http://hackernews.cc/archives/24547
```

---

# 2017🙎‍
**8月**
- **Aadhaar印度国家身份认证系统** 11亿用户数据泄露(印度国家身份认证系统将公民信息卖给了乡村企业家?)
```
泄露目标：印度公民
泄露内容：Aadhaar号码、姓名、电子邮箱、住址、电话号码以及照片
大致时间：2017年8月—2018年1月
事件经过：2018年1月4日，印度乡村企业家 Bharat Bhushan Gupta爆料说，有人在移动社交工具WhatsApp上向他推销Aadhaar数据库，购买之后，Aadhaar数据库确实为他提供了大量意想不到的用户信息。
```

**9月**
- **Equifax** 一亿四千三百万美国人的数据泄露
```
影响人数：一亿四千三百万
泄露目标：基本上包括了美国的每一个成年人
泄露内容：姓名、社会保险号码、生日、地址，驾照号码，信用卡号码，信用报告纠纷相关文件。
大致时间：公开于2018年12月3日
```

---

# 2016🙇‍
**1月**
- **BitTorrent** 的论坛遭到黑客攻击
```
影响人数：34,235
泄露目标：BitTorrent用户
泄露内容：Email addresses, IP addresses, Passwords, Usernames
link: https://haveibeenpwned.com/PwnedWebsites#BitTorrent
```

**8月**
- **Epic Games** 252k账户被曝光
```
影响人数：251,661
泄露目标：Epic Games用户
泄露内容：Email addresses, IP addresses, Names, Passwords, Payment histories, Phone numbers, Physical addresses, Usernames, Website activity
link: https://haveibeenpwned.com/PwnedWebsites#EpicGames
```

**9月**
- **爱拍** 包含650万个账户的数据在网上被泄露
```
影响人数：6,496,778
泄露目标：爱拍用户
泄露内容：Email addresses, Passwords
link: https://haveibeenpwned.com/PwnedWebsites#Aipai
```

**12月**
- **优酷** 遭遇数据泄露，暴露了9200万个唯一用户帐户和相应的MD5密码散列
```
影响人数：91,890,110
泄露目标：优酷用户
泄露内容：Email addresses, Passwords
link: https://haveibeenpwned.com/PwnedWebsites#Youku
```

---

# 2014🙅‍
**5月**
- **Avast** 论坛被黑，423k会员数据被曝光
```
影响人数：422,959
泄露目标：Avast论坛用户
泄露内容：Email addresses, Passwords, Usernames
link: https://haveibeenpwned.com/PwnedWebsites#Avast
```

---

# 2013😢
**10月**
- **Adobe** 1.53亿账号泄露
```
影响人数：152,445,165
泄露目标：Adobe用户
泄露内容：Email addresses, Password hints, Passwords, Usernames
link: https://haveibeenpwned.com/PwnedWebsites#Adobe
```
