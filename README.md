项目的作用：提供安全服务岗的面经，查漏补缺，完善所需技能栈：
- 渗透测试(红队攻防)
- 代码审计
- 安全研究
- 红队开发
- ...

项目的结构：主要分由两部分组成，**I** 为个人面试；**II** 为互联网收纳整理。

#### 一、我的实习 & 校招

##### 2020实习 安全服务工程师(驻场)
```
# 2020年暑期实习
1.挖过的一些漏洞（举例说明）
2.渗透测试的思路（结合自己的经验）
3.安全工具的使用（xray,sqlmap,awvs等）
4.owasp top 10
- 记住是哪10个
- 知道漏洞原理
- 知道防御姿势
5.owasp top 10中自己熟悉/经常挖到的漏洞
6.sql注入
- 漏洞几种类型
- 漏洞成因
- 防御方法
7.编程能力(写一些小脚本，改一些poc等)
```
##### 2020实习 安全研究/技术支持(实战攻防)
```
# 2020年暑期实习
0.自我介绍
1.实习经历
2.hw经历
3.对红蓝对抗的看法
4.发展方向和规划
5.挖过哪些洞?追问原理
6.挖过最有意思/最难的一个洞
7.sql注入写shell
8.内网渗透
9.域渗透
10.Java反序列化基础
11.跟过哪些nday，怎样一个思路
12.shiro反序列化
13.怎样对一个站去挖nday
14.挖到过0day吗
15.代码审计
16.实战有没有遇到xxe，oracle注入，mssql注入，ssrf，csrf
17.一些逻辑漏洞
18.app渗透经历
19.会不会二进制/逆向
...

# 小结

只记得当时技术面结束后，面试官和我说: 你后面还有很多基础需要补啊！🙈
```

##### 2022校招 红队攻防工程师
```
sql注入的报错函数
dom 型 xss
ssrf 利用点
sql注入点，空表如何利用
mvc代码审计流程
看你简历有在挖洞，说一下你挖过的洞
Redis 利用姿势及环境差异
fastjson回显
jndi注入及原理
端口 389
Java 回显
泛微oa xstream的回显(jdk1.8和1.7的差异)
shiro 限制payload长度
Java回显的通用思路以及不同版本jdk的差异
文件上传白名单利用
00截断的原理
判断域控的几种方式
工作组横向
域内横向
Windows认证协议
白银票据黄金票据
判断是否在域内
hash传递原理
权限维持
横向移动的各种姿势及原理
凭证获取(姿势/常用/原理/对抗)
如何对抗杀软加后门用户
Chrome dump密码的原理，如果让你写个工具，思路是什么(或者别人工具的实现原理)
```

##### 2021实习 安全研究员 
> from towns_
```
# 主要是两大块：Java反序列化和内网
Java反序列化
1.有哪些CC链是有回显的
2.Java反序连化相关的协议
3.熟悉的Java的漏洞，选一个来深入问，shior系列，550，721原理，key对了无法反序列化，不是无链的原因
  - serialVersionUID

内网
1.有一台Windows机器你会做些什么
2.有明文密码，密文密码你会做些啥。
3.有个基于webshell的，但TCP不出网，不会怎么做。
4.PTH
5.DCsync原理，DCsync是那个协议
6.有台Windows域内机子，你怎么打域控
```

##### 2021校招 攻防研究员(应用安全)

```
# 基础
1. http状态码，502，503，501
2. http请求方式及各自作用
3. 计算机网络的分层及分别有哪些协议

# owasp top 10
1. xss如何执行代码
2. xss常用哪些标签
3. http only
4. 怎样判断是否存在注入
5. sql注入无回显怎么办
6. 延时注入除了sleep的其他姿势(mysql)
7. dnslog的实现原理
8. sql注入，单引号被拦截，如何绕过
9. sql注入，写shell的语句，除了into outfile还有什么mysql的特性可以getshell
10.redis的利用，如何shell,相关命令
11.ssrf的原理即后利用，怎么执行命令，常搭配使用的协议

# PHP安全相关
1. 审计流程
2. 命令执行函数
3. 文件上传函数
4. 代码执行函数
5. vender目录
6. phpunit
7. php可以构造无文件shell吗

# Java安全相关
1. 挖过的通用洞，你会怎么利用(组合)
2. 命令的函数或包
3. java哪些框架，审过哪些框架，它们常出现的问题是什么
4. 审计流程，你一般关注哪些洞，或擅长挖哪种类型
5. tomcat做回显
6. 内存马的实现

# 其他
- 写poc/exp的经历和心得
- 复现的一些漏洞
- Linux 提权的姿势
- Linux下有哪些文件进行渗透时比较关注的，及文件权限问题
- dirty cow 的时间及其修复版本(哪年后就没法用了)
- 你觉得什么是你自己比较擅长的而我没有问到的

# 小结
这个岗位主要是搞漏洞挖掘和利用以及原理分析，Web方面就是JAVA和PHP的安全研究，比如JAVA下的流行框架，组件和服务器应用的安全问题。
没有问内网!!!
```

##### 2022秋招 渗透测试工程师
```
1.自我介绍
2.印象深刻的一次渗透
3.渗透测试的流程
4.SQL注入原理，及常用payload(手写-爆表名)
5.SQL注入空格不能使用如何绕过
6.SQL注入防御，延申预处理不能预防哪些注入
7.同源策略
8.a.baidu.com和b.baidu.com是否同源
9.SSRF原理，利用
10.攻击redis的方式（手写payload）
11.CSRF的原理及防御
12.一种特殊的CSRF场景：后端只解析json格式的时候如何利用CSRF(非更改Content-Type)
13.SameSite
14.DNS Rebinding
15.Fastjson反序列化及如何修复
16.子域名枚举用过那些工具，原理是什么，如果出现了任意子域名都返回200是什么原因？
17.Java学到哪种程度了？

```
##### 2022校招 安全研究员(SAST方向)

```
## 一面
# 问题
1. 自我介绍
2. 根据简历问(主要是挖洞方面)
3. 对SAST的理解
4. 对IAST的理解
5. 污点分析
6. 对DevSecOps的理解
7. 对SDL的理解
8. 后面的发展规划(学习方向)
9. 目前掌握的语言栈怎么样？愿意去学习新的语言吗？
10. 对SAST和IAST中哪个更感兴趣
11. 讲讲白盒审计的思路
12. 有写过相关的自动挖掘工具吗

# 小结
体验很好，感觉双方更像是在探讨。

## 二面
# 问题
1. Java反序列化
2. 了解哪些白盒审计的工具，知道原理吗
3. 域控的攻击方式
4. MS14-068的原理
5. 黄金和白银票据的利用及其效果，原理层面
6. IAST
7. 污点跟踪
8. 候选人的语言栈：java和go

# 小结 
估计凉凉，说让我去提前实习，我说想拿正式Offer
```

##### 2022校招 高级安全工程师(代码审计/安全评估)

```
## 渗透基础
0.自我介绍
1. SQL注入 写 Shell
   mysql & mssql & oracle
2. 登录框攻击面
3. getshell的姿势
4. 文件上传点，黑名单限制，如何利用
5. SQL注入后利用
6. 讲一个你觉得有趣的漏洞案例
7. 前段时间蓝凌OA的洞
8. DNS 重绑定，利用
9. Php和Java的文件包含区别
10. Redis的利用

## PHP
1. 常见漏洞对应函数（挨个问）
- 命令执行
- 代码执行
- 文件包含
- 文件上传
- 文件删除
- SSRF
- ...
2. PHP安全特性有关注吗
3. 代码审计(mvc/非mvc)

## Java
1. Java执行命令的几种方式
2. Java反序列化的原理
3. 讲讲yso的链
4. Shiro 反序列化原理
5. 反射，代理，类加载这些熟悉吗
6. 代码审计

## Python
1. 是否写过非脚本的工具
2. Web框架(flask/django)
3. 代码审计

## 漏洞挖掘(重点关注)
1. 简历上的通用洞挨个问
2. 漏洞利用研究的理解
3. 漏洞利用研究的案例

## 内网(偏实战问题)
1. disable function bypass
2. webshell 提权(低权限 -> 高权限)
3. 已经拿到webshell,说说你的内网思路
4. 不允许扫描，如何横向
5. 存在杀软，不允许exe落地，怎么办
6. 常用的提权姿势
7. 内网代理，详细问了frp
```
#### 二、同行师傅们的实习 & 校招 & 社招
> 以下所有的面经来自于均互联网收纳整理、如果有侵权，请联系我订正。

##### 01套

> 1、常见的SQL注入类型有哪些？并写出sqlmap检测SQL注入的命令？SQLMAPAPI怎么使用
>
> 2、Mongodb、redis、websphere、rsync服务简介和默认运行端口
>
> 3、写出你知道的逻辑漏洞
>
> 4、列举Linux的反弹shell的一些方法
>
> 5、针对SQL注入，写出你所知道的Bypass WAF的可能的方式
>
> 6、写出任意一种漏洞检测代码，用python实现
>
> 7、简述XXE的基本原理，以及如何去检测或者判断Blind XXE的存在
>
> 8、简述针对一个网站的渗透测试思路
>
> 9、针对Web扫描器的爬虫，你怎么看
>
> 10、简述PHP中造成任意文件下载漏洞的常见函数，以及造成漏洞的原因

##### 02套

> 1、介绍一下自认为有趣的挖洞经历
>
> 2、你平时用的比较多的漏洞是哪些？相关漏洞的原理？以及对应漏洞的修复方案？
>
> 3、php/java反序列化漏洞的原理?解决方案?
>
> 4、如果一台服务器被入侵后,你会如何做应急响应
>
> 5、你平时使用哪些工具?以及对应工具的特点?
>
> 6、遇到waf如何进行sql注入/上传Webshell？请写出曾经绕过WAF的经过(SQLi，XSS，上传漏洞选一)
>
> 7、如何判断sql注入，有哪些方法
>
> 8、介绍 SQL 注入漏洞成因，如何防范？注入方式有哪些？除了数据库数据，利用方式还有哪些？
>
> 9、为什么有的时候没有错误回显
>
> 10、宽字符注入的原理？如何利用宽字符注入漏洞，payload如何构造
>
> 11、CRLF注入的原
>
> 12、mysql的网站注入，5.0以上和5.0以下有什么区别？
>
> 13、php.ini可以设置哪些安全特性
>
> 14、php的%00截断的原理是什么？
>
> 15、webshell检测，有哪些方法
>
> 16、php的LFI，本地包含漏洞原理是什么？
>
> 17、说说常见的中间件解析漏洞利用方式
>
> 18、mysql的用户名密码是存放在那张表里面？mysql密码采用哪种加密方式？
>
> 19、Windows、Linux、数据库的加固降权思路，任选其一
>
> 20、你使用什么工具来判断系统是否存在后门
>
> 21、如何绕过CDN获取目标网站真实IP，谈谈你的思路？
>
> 22、如果给你一个网站,你的渗透测试思路是什么? 在获取书面授权的前提下。
>
> 23、谈一谈Windows系统与Linux系统提权的思路？
>
> 24、列举出您所知道的所有开源组件高危漏洞(十个以上)
>
> 25、反弹 shell 的常用命令？一般常反弹哪一种 shell？为什么？
>
> 26、CMD命令行如何查询远程终端开放端口
>
> 27、服务器为IIS+PHP+MySQL，发现root权限注入漏洞，讲讲你的渗透思路
>
> 28、请写出Mysql5数据库中查询库’helloworld’中’users’表所有列名的语句
>
> 29、udf提权 
>
> 30、SQL头注入点
>
> 31、php中命令执行涉及到的函数
>
> 32.、SSRF漏洞的成因 防御 绕过
>
> 33、mysql写shell有几种方法
>
> 34、Metasploit 打开反向监听的命令
>
> 35、有哪些反向代理的工具?
>
> 36、有什么比较曲折的渗透经历
>
> 37、怎么查找域控 
>
> 38、PHP 作为弱类型语言，在底层它是怎么判断变量的类型的 
>
> 39、ARP 攻击的原理（讲出具体的流程），如何发现并防御 ARP 攻击 
>
> 40、渗透大企业简单还是小站点简单，为什么 
>
> 41、内网如何反弹 shell，反弹的 shell 流量如何隐蔽 
>
> 42、除了 TCPIP 协议，如何将内网数据传递出来（内网环境有着严格防御与审查） 

##### 03套

> 1、什么是同源策略
>
> 2、XSS 能用来做什么
>
> 3、XSS的三种类型，防御方法
>
> 4、存储型xss原理
>
> 5、你怎么理解xss攻击
>
> 6、如何快速发现xss位置
>
> 7、Dom xss 原理/防范
>
> 8、DOM型XSS与反射型XSS区别
>
> 9、如何使得前端 referer 为空
>
> 10、cookie参数，security干什么的
>
> 11、如果 SRC 上报了一个 XSS 漏洞，payload 已经写入页面，但未给出具体位置，如何快速介入
>
> 12、XSS， CSRF， CRLF比较容易弄混，说说三者的原理，防御方法
>
> 13、csrf 如何不带referer访问
>
> 14、CSRF 成因及防御措施；如果不用 token 如何做防御
>
> 15、Xss worm原理
>
> 16、Cookie的P3P性质
>
> 17、CSRF有何危害

#####  04套

> 1、渗透测试流程
>
> 2、描述渗透项目，做了什么
>
> 3、xss漏洞类型、详情、修复方案
>
> 4、SQL注入原理、类型，waf绕过，写shell，提权，修复方案
>
> 5、终端的渗透经验
>
> 6、了解什么比较新的漏洞
>
> 7、企业内部安全

#####  05套

> 1、算法？了解过什么排序？
>
> 2、爬虫
>
> 3、页面存在很多js的时候，用什么
>
> 4、爬虫的待爬取URL量级比较大的时候，如何对其去重
>
> 5、多线程 异步 协程 多路复用 用哪一个最快 为什么
>
> 6、浏览器的常用编码
>
> 7、web常用的加密算法有什么
>
> 8、有没有内网渗透的经验？怎么渗透？如果拿下了边界层的某一个机器，如何对内网其他进行探测？
>
> 9、mysql中like查询会会非常缓慢，如何进行优化
>
> 10、做了cdn的网站如何获取真实IP
>
> 11、渗透的时候如何隐藏自己的身份
>
> 12、主机疑似遭到入侵，要看哪里的日志
>
> 13、SQL注入漏洞怎么修复

##### 06套

> 1、病毒和蠕虫的区别
>
> 2、DNS欺骗
>
> 3、DDOS有哪些，CC攻击是什么，区别是什么，什么协议
>
> 4、land攻击
>
> 5、存储型的xss的危害和原理
>
> 6、渗透测试流程
>
> 7、移动端的调试经验 apk,ipa包分析
>
> 8、对于云安全的理解
>
> 9、虚拟机逃逸的理解

##### 07套

> 1、owasp top10漏洞
>
> 2、xss如何盗取cookie
>
> 3、渗透测试的流程
>
> 4、xss如何防御
>
> 5、xss有cookie一定可以无用户名密码登录吗？
>
> 6、SSL Strip(SSp)攻击到底是什么？
>
> 7、中间人攻击——ARP欺骗的原理、实战及防御
>
> 8、会话劫持原理
>
> 9、CC攻击
>
> 10、添加时间戳防止重放攻击
>
> 11、HTTPS中间人攻击与证书校验
>
> 12、什么是HttpOnly?
>
> 13、dll文件是什么意思，有什么用？DLL劫持原理
>
> 14、Rootkit是什么意思
>
> 15、手工查找后门木马的小技巧
>
> 16、SSRF漏洞

#####  08套

> 1、渗透测试简要流程
>
> 2、绕过WAF常用方法
>
> 3、SQL注入常见Payload
>
> 4、XSS种类、弹窗函数、绕过方法
>
> 5、XXE漏洞原理
>
> 6、列举OWASP TOP10
>
> 7、SQL注入常用函数
>
> 8、.XSS和CSRF的区别
>
> 9、常见的中间件
>
> 10、文件上传怎么绕过
>
> 11、反序列化的原理
>
> 12、数据库预处理怎么突破
>
> 13、httponly
>
> 14、SQL注入如何拿GetShel
>
> 15、oracle、mysql、sqlserver默认端口
>
> 16、SSRF
>
> 17、常见Web安全漏洞
>
> 18、MYSQL注入5.0以上和5.0以下有什么区别
>
> 19、get传参和post传参的区别

#####  09套

> 1、先做一下自我介绍
>
> 2、讲一下你所了解的web漏洞
>
> 3、你在SRC挖掘中遇到最多的漏洞是什么
>
> 4、SQL注入分为几种
>
> 5、详细讲一下SQL注入
>
> 6、XSS有几种，详细讲一下
>
> 7、XSS除了获取cookie，还有别的用处吗
>
> 8、讲一下渗透测试的流程
>
> 9、讲一下信息收集都收集那些信息
>
> 10、看你简历有写内网渗透，简单讲一下
>
> 11、获取shell之后，你是怎么提权的
>
> 12、怎么通过数据库获取shell
>
> 13、数据库的提权有接触过吗
>
> 14、进入到内网之后，怎么去维持权限
>
> 15、讲一下黄金票据
>
> 16、讲一下APP渗透
>
> 17、如果抓不到包，是因为什么
>
> 18、讲一下HTTP双向认证
>
> 19、了解APT吗

#####  10套

> 1、HTTP的请求方式
>
> 2、具体说说这些请求方式
>
> 3、sqlmap怎么跑post请求
>
> 4、SSRF的危害
>
> 5、怎么他测内网，怎么访问敏感文件文件
>
> 6、oracle数据库端口号
>
> 7、怎么防范CSRF
>
> 8、linux系统中etc/password文件和/shadow文件的区别
>
> 9、了解struct框架吗，说一说

#####  11套

> 1、SQL注入的防护方法有哪些？
>
> 2、永恒之蓝的漏洞原理是什么？怎么做到的？
>
> 3、命令注入有哪些？
>
> 4、给你一个目标网站，你该如何进行测试？
>
> 5、给你一个后台登陆地点的网站，你能从中发现那些问题？
>
> 6、给你一千台服务器和交换机，你会如何进行扫描？
>
> 7、内网渗透了解多少？
>
> 8、中间件有哪些？
>
> 9、中间件有哪些已知的漏洞？

##### 12套

> 1、自我介绍一下
>
> 2、SQL注入盲注的方法
>
> 3、如何防范SQL注入
>
> 4、xxs有哪些和绕过方式以及防护方式
>
> 5、同源性法制你了解吗
>
> 6、csrf可以干什么怎么防护
>
> 7、逻辑漏洞有哪些
>
> 8、文件包含以及变量覆盖
>
> 9、SQL注入如何写shell
>
> 10、内网渗透

#####  13套

> 1、简历上面写的几个漏洞，逐个问一遍
>
> 2、怎么判断目前是否是cms
>
> 3、后台扫描用什么工具
>
> 4、御剑有自己的包吗
>
> 5、burp会哪些模块，
>
> 6、越权以及逻辑漏洞问题
>
> 7、我听你上面说的都是小面积的测试，你有没有大面积测试过一个网站呢？
>
> 8、如果不能用awvs和appscan你还能怎么办
>
> 9、会哪些bypass的手法
>
> 10、SQL注入怎么拿到最高权限？
>
> 11、写shell需要什么权限吗？你怎么判断存在写入权限
>
> 12、如果没有写入权限，你还能有什么办法吗
>
> 13、怎么利用说SQL注入来读取文件吗
>
> 14、怎么获得绝对路径呢？没有报错呢？不能读取文件呢
>
> 15、xss里面的牛头你会用吗？xss你知道除了可以盗取cookie还能干什么，xss平台你用的是上面
>
> 16、msf用过吗？
>
> 17、msf的木马你知道吗？免杀是怎么做的？
>
> 18、内网提权方面你土豆你知道原理吗？
>
> 19、怎么找到域控机？
>
> 20、webshell你会利用哪些办法来写绕过
>
> 21、mssql的提权你能说一下吗？
>
> 22、那其他数据库的SQL注入呢？
>
> 23、怎么分辨数据库类型
>
> 24、做过黑产吗？

#####  14套

> 1、sql注入原理
>
> 2、xxe 攻击
>
> 3、sql注入都有哪些
>
> 4、Windows怎么提权
>
> 5、文件上传绕过
>
> 6、代码审计
>
> 7、逻辑漏洞有哪些
>
> 8、验证码绕过有哪些方法
>
> 9、csrf原理
>
> 10、不用工具的情况下 如何搜集子域名

#####  15套

> 1、有没有实习过？在哪实习的？
>
> 2、cnvd那的都是什么证书？
>
> 3、给你一个登录窗口你会怎么利用？
>
> 4、怎么去绕过验证码？
>
> 5、我看你简历上说会绕waf？
>
> 6、以后的发展？
>
> 7、多久能学会？
>
> 8、那你都复现过什么漏洞，在哪里跟进漏洞？

#####  16套

> 1、平时怎么做渗透，说一下渗透测试步骤
>
> 2、渗透测试过程中如何信息收集，说一下渗透测试信息收集方法
>
> 3、工作中用过那些扫描器，这些扫描器有那些优点缺点？
>
> 4、burp如何破解md5加密密码或base64加密密码
>
> 5、常见的http方法有那些，他们之间的区别是什么
>
> 6、常见状态码你知道吗？分别说一下200、201、301、302、500、503的含义？
>
> 7、常见请求消息头的作用，分 别说一下cookie、referer、user-Agent的作用
>
> 8、响应消息头的作用，分别说一下Location、Access-Control-Allow-Origin、WWW-Authenticate
>
> 9、Cookie响应消息头的secure和HttpOnly分别作用是什么？
>
> 10、在渗透过程中常用的编码有那些？
>
> 11、静态 动态语言区别
>
> 12、常用的脚本语言和数据库有那些
>
> 13、系统、脚本语言、中间件如何组合
>
> 14、渗透测试过程如何判断对方操作系统是什么操作系统
>
> 15、你是怎么知道对方网站使用了那些常用cms系统搭建的（指纹信息是什么）
>
> 16、给你一个网站你是如何信息收集的

##### 17套

> 1、注入攻击原理是什么？如何找注入点？如何判断注入点？
>
> 2、注入分为几类及提交方式是什么
>
> 3、注入攻击一般所支持的类型有那些
>
> 4、mysql数据库帐号和密码存放在那个库和表里面
>
> 5、如何寻找网站物理路径
>
> 6、分别写出mysql及mssql数据库写入webshell的方法
>
> 7、请说出mysql5.0以下与5.0以上的区别
>
> 8、sql注入对服务器文件读写操作需要那些条件
>
> 9、分别说出sqlmap -u -r -v -p —level —risk —tables —coiumns -T —tamper参数的含义
>
> 10、注入漏洞防范方法
>
> 11、xss攻击原理及出现的原因
>
> 12、xss分为那几类
>
> 13、xss的危害，可能存在的地方
>
> 14、xss漏洞测试方法
>
> 15、xss如何绕过安全防范
>
> 16、分别说出iis、apache、nginx解析漏洞原理
>
> 17、任意文件下载攻击原理及测试方法
>
> 18、任意文件上传漏洞分几类，说出每类突破方法
>
> 19、分别文件包含漏洞攻击原理及分类
>
> 20、如何快速挖包涵漏洞
>
> 21、包涵漏洞具体能做什么，怎么绕过你能说说吗
>
> 22、ssrf漏洞攻击原理、用途
>
> 23、说说你是如何挖掘ssrf漏洞
>
> 24、说说ssrf绕过及防范方法
>
> 25、csrf攻击原理是什么及一般你用什么工具进行检测
>
> 26、你是如何挖掘ssrf漏洞的及防范方法
>
> 27、说说xxe漏洞攻击原理是什么，如何找xxe漏洞及攻击方法
>
> 28、xxe攻击在无回显的时候你是如何突破的
>
> 29、你是如何防范xxe漏洞的
>
> 30、你挖洞影像最深的是什么？
>
> 31、你认为你的渗透水平在国内大概是什么水平，能给自己打多少分
>
> 32、说说你以前在你公司主要做什么安全工作？如每天、每月、每年做些什么安全工作
>
> 33、你在各大漏洞平台挖过漏洞吗，能说说吗？
>
> 34、你写过什么好的安全漏洞文章发布过吗，是否可以说说？

#####  18套

> 1、自我介绍
>
> 2、拿到一个待检测的站，你觉得应该先做什么（一个网站的渗透测试思路，流程
>
> 3、判断出网站的CMS对渗透有什么意义？
>
> 4、一个成熟并且相对安全的CMS，渗透时扫目录的意义？
>
> 5、常见的网站服务器容器。
>
> 6、目前已知哪些版本的容器有解析漏洞，具体举例。
>
> 7、简述SQL注入，XSS，CSRF漏洞的原理和渗透手法等
>
> 8、如何手工快速判断目标站是windows还是linux服务器？
>
> 9、为何一个mysql数据库的站，只有一个80端口开放？
>
> 10、3389无法连接的几种情况
>
> 11、如何突破注入时字符被转义？
>
> 12、拿到一个webshell发现网站根目录下有.htaccess文件，能做什么？
>
> 13、请写出突破Waf的方法
>
> 14、提权时选择可读写目录，为何尽量不用带空格的目录？
>
> 15、审查上传点的元素有什么意义？
>
> 16、目标站禁止注册用户，找回密码处随便输入用户名提示：“此用户不存在”，怎样利用？
>
> 17、目标站发现某txt的下载地址为.do?file=/upwdown/1.txt，有什么思路？
>
> 18、目标站，已知根目录下存在/abc/目录，并且此目录下存在编辑器和admin目录，思路
>
> 19、在有shell的情况下，如何使用xss实现对目标站的长久控制？
>
> 20、后台修改管理员密码处，原密码显示为*。你觉得该怎样实现读出这个用户的密码？
>
> 21、目标站无防护，上传图片可以正常访问，上传脚本格式访问则403.什么原因？
>
> 22、审查元素得知网站所使用的防护软件，你觉得怎样做到的？
>
> 23、以下链接存在 sql 注入漏洞，对于这个变形注入，你有什么思路？
> demo.do?DATA=AjAxNg==
>
> 24、发现 demo.jsp?uid=110 注入点，你有哪几种思路获取 webshell，哪种是优选？
>
> 25、CSRF 和 XSS 和 XXE和SSRF 有什么区别，以及修复方式？
>
> 26、说出至少三种业务逻辑漏洞，以及修复方式？
>
> 27、sqlmap，怎么对一个注入点注入？
>
> 28、nmap，扫描的几种方式
>
> 29、sql注入的几种类型？
>
> 30、报错注入的函数有哪些？
>
> 31、延时注入如何来判断？
>
> 32、盲注和延时注入的共同点？
>
> 33、如何拿一个网站的webshell？
>
> 34、sql注入写文件都有哪些函数？
>
> 35、owasp 漏洞都有哪些？
>
> 36、网络安全事件应急响应
>
> 37、你提交的漏油
>
> 38、说说你的其它优势（如：对安全新兴技术的研究、个人博客、比赛、在校经历等）

#####  19套

> 1、自我介绍
>
> 2、提交过什么漏洞
>
> 3、常用的漏洞扫描工具有哪些
>
> 4、owasp top10
>
> 5、mysql数据库，写入一句话木马所需权限
>
> 6、xss分类，区别
>
> 7、xxe漏洞
>
> 8、比较成功的渗透经历
>
> 9、app渗透测试吗？
>
> 10、宽字节注入的原理
>
> 11、写过工具没
>
> 12、mysql数据库的右向偏移

#####  20套

> 1、中间件
>
> 2、SQL注入怎么写入，用的什么函数
>
> 3、越权问题有哪些，实战
>
> 4、文件上传
>
> 5、mqsql提权有哪些
>
> 6、XSS（绕过）
>
> 7、CSRF与XSS的区别
>
> 8、SSRF
>
> 9、Java反序列化
>
> 10、URL跳转漏洞
>
> 11、平时怎么绕waf
>
> 12、Sqlsever利用思路
>
> 13、盲注

#####  21套

> 1、XSS的标签
>
> 2、说说大学这几年最自豪的事请
>
> 3、SQL注入
>
> 4、偏移注入
>
> 5、CTF你都做哪些题型
>
> 6、遇到的比较困难的web题型的ctf题目
>
> 7、XXE
>
> 8、反序列化 
>
> 9、Bypass说说
>
> 10、假如，让你设计一个Waf，你会怎么设计
>
> 11、内网渗透与提权
>
> 12、平常都挖掘哪些SRC
>
> 13、有没有写过一些脚本
>
> 14、说说SQL注入手工怎么爆出所有库名字

#####  22套

> 1、为什么做这一行
>
> 2、有哪些项目经验
>
> 3、会不会逆向APK，会不会嵌入式
>
> 4、正则能不能写
>
> 5、JAVA能不能上手
>
> 6、渗透测试的基本流程
>
> 7、如何创建一个用户并且提权
>
> 8、数据库表名test 字段名 user,password 写出查询语句
>
> 9、linux如何查看当前权限
>
> 10、Apach IIS Nginx 的解析漏洞
>
> 11、谷歌排行第一的CMS 有1000个旁站，问怎么日(面试题)
>
> 12、是否有在国外抓过肉鸡，有没有做黑产的朋友
>
> 13、使用谷歌语法查询指定域名的子域名 并且搜索他的后台登陆
>
> 14、能否接受驻场
>
> 15、最得意的一次渗透测试
>
> 16、是否有写过tamper

#####  23套

> 1、自我介绍
>
> 2、SQL注入原理、修复建议、如何彻底杜绝SQL注入
>
> 3、渗透流程
>
> 4、XSS的种类，修复建议
>
> 5、渗透过哪些网站，请举几个例子，印象最深的
>
> 6、漏洞平台的贡献是多少，排名是多少
>
> 7、代码审计的时候你比较关注的漏洞是哪些
>
> 8、对linux了解吗？linux内核漏洞有没有分析过？
> 
> 9、你说你对堆栈溢出有了解，那玩过pwn吗？
> 
> 10、说说在kali上，最常用的几个工具？
> 
> 11、ARP欺骗的方法有哪些？说说原理
> 
> 12、对https了解吗？讲一下加密和解密流程？
> 
> 13、都破解过哪些软件？如果给你一个产品，你能提出安全加固建议吗？

#####  24套

> 1、如何进行信息搜集，用过哪些工具
> 
> 2、对没有挂到DNS上的网站如何进行入侵
> 
> 3、有哪些常见的中间件，相关漏洞
> 
> 4、端口扫描时，都关注哪些端口，分别代表什么
> 
> 5、针对PHP的弱类型，有哪些漏洞
> 
> 6、代码审计方面，有过对大型CMS的审计吗，发现过哪些漏洞
> 
> 7、针对PHP的语言特点，说几个常见的漏洞
> 
> 8、SQL注入，如何写入文件
> 
> 9、SQL注入，如果注入点在union或order by之后，怎么办
> 
> 10、陈述一下缓冲区溢出
> 
> 11、如果对方开启了ASLR和DEP，要如何绕过

#####  25套

> 1、渗透测试流程
> 
> 2、SQL过滤单引号怎么注入
> 
> 3、宽字节原理
> 
> 4、CSRF和SSRF区别 和 作用
> 
> 5、如何绕waf
> 
> 6、命令执行有哪些函数
> 
> 7、OWASP TOP10
> 
> 8、隐藏马
> 
> 9、端口号及对应服务
> 
> 10、Java的反序列化漏洞
> 
> 11、有什么优势
> 
> 12、文件包含include()与require()的区别
> 
> 13、内网渗透相关问题

#####  26套

> 1、三分钟自我介绍
> 
> 2、Web安全，SQL注入安全修复建议/XSS form框限制长度的绕过
> 
> 3、说说白盒检测漏洞的思路
> 
> 4、说说静默挖矿行为检测
> 
> 5、说说webshell检测
> 
> 6、Python装饰器
> 
> 7、python类方法、静态方法、对象方法区别
> 
> 8、你的能力栈
> 
> 9、你的能力模型
> 
> 10、说一个你觉得做的比较好的项目？在项目上你比业界的优势在哪儿？
> 
> 11、期待做什么样的工作？宽度or广度？你对工作的选择？
> 
> 12、说说水平权限优化这块儿的工作
> 
> 13、怎么看待深度和广度的点
> 
> 14、你的职业规划
> 
> 15、工作意愿
> 
> 16、期望工作城市

#####  27套

> 1、order by注入 limit注入 后面跟的函数有什么不同
> 
> 2、order by 含义
> 
> 3、MYSQL注入
> 
> 4、基于css的XSS
> 
> 6、基于flash的XSS原理
> 
> 7、过滤了单引号、into outfile是否还能利用
> 
> 8、除了script ,html事件之外还有哪些存在XSS的地方
> 
> 9、IIS拒绝服务原理
> 
> 10、SSRF除了探测主机外如何进一步进行攻击
> 
> 11、uname -a 、 '-a'参数可控，如何执行多条指令
> 
> 12、MYSQL /MSSQL 注入原理，分类，盲注
> 
> 13、文件上传  & 文件包含、分类、原理
> 
> 14、CSRF 和 XSS 原理、分类
> 
> 15、SSRF & XXE 细节，绕waf ，渗透测试流程

#####  28套

> 1、SQL注入的成因、代码层防御方式
> 
> 2、XSS的成因、代码层防御方式、写出3条xsspayload
> 
> 3、Jsonp劫持漏洞的原理、利用方式、防御方法
> 
> 4、XXE漏洞的原理、危害、防御方法
> 
> 5、getshell的姿势（SQL注入、文件包含、文件上传、命令执行、后台getsehll等）
> 
> 6、在SRC、补天、盒子、乌云等都提交了哪些高中危漏洞，说说挖这些漏洞的方法。
> 
> 7、说明电商系统的加车、下单、支付过程中，常见的逻辑漏洞有哪些，如何挖掘
> 
> 8、APP常见任意密码重置漏洞的挖掘方法
> 
> 9、挖掘过哪些逻辑漏洞，请说明挖洞方法
> 
> 10、SSRF漏洞的成因、利用方法、防御方式
> 
> 11、挖掘过哪些APP的web漏洞（非逆向），如何挖掘的
> 
> 12、利用的过的通用漏洞有哪些？包括CMS、web中间件、操作系统、DB等
> 
> 13、同源策略，有什么作用？同源策略中Access-Control-Allow-Origin的作用是什么
> 
> 14、CSRF的成因、利用方式、哪些功能容易有CSRF，防御方法
> 
> 15、挖掘Web漏洞的流程和思路，是当完成信息收集之后，开始挖洞的思路
> 
> 16、获取Web shell后，是否做过内网渗透，你用哪些正向代理、反向代理工具，这些工具如何使用
> 
> 17、写出Mysql导出php一句话木马的命令

#####  29套

> 1、自我介绍
> 
> 2、渗透测试流程，有没有打过内网
> 
> 3、SQL注入，报错
> 
> 4、XSS，反射/DOM型，怎么利用
> 
> 5、Redis的利用
> 
> 6、应急响应能力怎么样，处置流程思路
> 
> 7、无态势感知，安全设备，怎样手动发现shiro反序列化漏洞进来都攻击
> 
> 8、平时有分析研究漏洞吗，编写exp，熟悉什么开发语言
> 
> 9、关于hook了解
> 
> 10、ATT&CK框架了解吗、到什么程度，是否有过应用

#####  30套

> 1、如何做的样本分析，思路是什么
> 
> 2、如何用linuxgdb分析一个简单样本
> 
> 3、再举一个你的其他应急的例子(我举的是挖矿病毒)
> 
> 4、日志你看的是什么日志，web服务器日志嘛
> 
> 5、某些命令被替换了，如何发现
> 
> 6、rpm有个参数就可以校验命令是否被替换，是什么
> 
> 7、是否做过APT相关的研究
> 
> 8、如何分析windows，linux，web一些常见的漏洞
> 
> 9、内网突破到内网漫游的思路
> 
> 10、如何横向、IPC了解过嘛，横向原理
> 
> 11、权限提升（windows，linux）

#####  31套

> 1、常见的端口问题
> 
> 2、SQL注入中的报错函数
> 
> 3、渗透测试的基本流程
> 
> 4、Redis数据库的利用手法
> 
> 5、CSRF的原理 & 利用
> 
> 6、对于webshell执行命令或者木马.exe被杀软拦截，如何bypass
> 
> 7、XSS的原理、最大化利用
> 
> 8、Fastjson的某个版本漏洞成因、漏洞的入口点在哪
> 
> 9、Java反序列化的原理

#####  32套

> 1、自我介绍
> 
> 2、渗透测试的流程
> 
> 3、熟悉什么语言，有无开发经历
> 
> 4、自动化挖洞了解过吗？曾经刷过什么漏洞？怎么刷的？
> 
> 5、前期信息搜集你是怎么做的
> 
> 6、印象深刻的一次漏洞挖掘？
> 
> 7、从浏览器输入 URL 到页面回显的过程中，经历了哪些协议
> 
> 8、HTTP和HTTPS网站的注入用sqlmap是否有区别，状态码为401或者其他时如何与成功的页面区分
> 
> 9、AWVS，比如如何防御对于类似工具的扫描，能否针对一个服务比如ASP.NET进行扫描
> 
> 10、CSRF和SSRF的区别
> 
> 11、SSRF对输入做了ipv4的正则过滤，有什么bypass方式？
> 
> 12、关于XSS的,一个场景，假如你找到一处接口，他返回的是json格式的信息，你能控制json里的内容并能造成xss，为什么浏览器会把他解析成html代码执行呢？
> 
> 13、一个ip可以有多个站点，服务器是怎么知道我们访问的是哪个站点的？

#####  33套

> 1、Dnslog的原理
> 
> 2、内网渗透如何判断tcp是否有出口限制
> 
> 3、iptables 的三张表分别的作用，如何查看详细登陆日志
> 
> 4、如何查看是否有进程调用敏感文件执行命令，例如：攻击者把木马注入到主进程里，如何发现木马所在的子进程的进程号并杀死木马进程?
> 
> 5、线程，协程的原理以及相关的效率问题
> 
> 6、你觉得你的优势是什么
> 
> 7、来到这里你想学到什么
> 
> 8、php反序列化
> 
> 9、你了解的redteam是什么
> 
> 10、未来的学习计划


