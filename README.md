# 哈工大网络资源一览

## 注意

**本文灵感来源于 <https://github.com/zzh1996/USTC-Network-Resources>，希望大家可以通过 Issue 和 PR 的形式一起帮助维护这份文档。**

## 〇、前言

我们学校有丰富的网络资源供我们学生使用，仅仅以 hit.edu.cn 结尾的域名就有数百个<!-- 至少曾经有，见 https://github.com/cvkki/src/blob/master/edu-src.txt 现在也有将近五百个） -->，但我们大多数人对这些资源知之甚少。我经常看到同学在得知某个网站或者听说一种让下载速度更快的方法时，心想如果大一的时候就知道该多好啊！同时，学校官方辛辛苦苦搭建的网站或者花很多钱购买的服务，没有几个学生去用，也是一笔很大的浪费。于是我决定建立这样一个仓库来总结一下我所知道的资源和相应的使用方法，如果有没提到的或者错误的地方，欢迎提出 Issue 和 Pull request。

## 一、网络接入

接入校园网的方式很多，包括：

* 校园网

校园网包括有线与无线接入两种，有线又包括锐捷（多见于宿舍）与 PPPoE（多见于教室）两种。

> 注：部分教室电脑登陆方式与无线相同，打开浏览器即可登录

开户方式：微信服务号“哈尔滨工业大学服务号” -> 服务大厅 -> 学生网络自助 -> 网络开户；

缴费方式：公寓一楼机器交费 或 服务大厅->交网费；

无线使用方式：在搜索到 HIT-WLAN 的地方连接后，等待自动跳转登陆界面；

有线（锐捷）使用方式：登录[网络与信息中心](http://ito.hit.edu.cn/)，在网络信息资源处点击“锐捷客户端下载”，下载对应平台客户端登录；

有线（PPPoE）使用方式：打开 PPPoE 客户端，账号输入学号/教职工号，并输入密码登录。

相关链接：[校园网自助服务系统](http://202.118.224.24:8080/selfservice/)、[网络与信息中心](http://ito.hit.edu.cn/)

* VPN

哈工大 VPN 为 EasyConnect，由深信服科技股份有限公司提供服务。VPN 可以使用户在非校园网环境使用内网内容（如选课等）。有两种使用 VPN 的方式：

较为推荐的方式为直接登录 [ivpn.hit.edu.cn](https://ivpn.hit.edu.cn/)，经过统一身份认证登录后在“快速访问”处点击“更多”，输入要访问的校园网地址即可访问。

另一种方式为“VPN穿梭服务”，需要下载 [EasyConnect](http://static.hit.edu.cn/vpn/) SSLVPN 客户端。输入服务器地址 `ivpn.hit.edu.cn`，输入用户名和密码即可使用。

## 二、网站

### 信息类

* [www.hit.edu.cn](https://www.hit.edu.cn/)：
哈工大首页。

* [www.hit.edu.cn/xl/list.htm](https://www.hit.edu.cn/xl/list.htm)（校历）：
哈工大校历。

* [today.hit.edu.cn](http://today.hit.edu.cn/)（今日哈工大）：
今日哈工大，即哈尔滨工业大学校内综合信息网，整合了各个院系、部处的公告、快讯、活动预告、就业信息等。

* [map.hit.edu.cn](https://map.hit.edu.cn/)（校园地图）：
查看各校区地图与设施介绍等。

* [ito.hit.edu.cn](http://ito.hit.edu.cn/)（网络与信息中心）：
发布网络信息公告、维护通知。

* [homepage.hit.edu.cn](http://homepage.hit.edu.cn/)（教师个人主页）：
教师个人主页，可以在此系统查看部分教师个人信息。

* [jwc.hit.edu.cn](http://jwc.hit.edu.cn/)（本科生院教务处）：
本科生部分教务信息发布网站，如选课通知、放假安排等。

* [http://hitgs.hit.edu.cn/](http://hitgs.hit.edu.cn/)（研究生院）：
研究生部分培养与教务等信息发布网站。

### 服务类

* [i.hit.edu.cn](http://i.hit.edu.cn/)（校园门户（内网））：
校园门户包括了许多实用的服务，可以在登录后进行操作。[服务中心](http://i.hit.edu.cn/index#/app/service/list) 列出了许多业务的办理流程及办理页面入口（对于线上服务）；[应用中心](http://i.hit.edu.cn/index#/app/appCenter) 列出了许多服务系统的入口。
如果您在校外或没有使用校园网，可以登录 [ivpn.hit.edu.cn](https://ivpn.hit.edu.cn/) 进入校园门户。

* [wsfwzx.hit.edu.cn](http://wsfwzx.hit.edu.cn/)（网上服务中心（内网））：
用于查询线上服务的办理进度，主要配合校园门户使用。

* [mail.hit.edu.cn](https://mail.hit.edu.cn/)（电子邮件系统）：
每名学生可以拥有一个 `学号@stu.hit.edu.cn` 的邮箱，在开学迎新系统中激活；如果没有开通可以在微信“哈尔滨工业大学服务号——服务大厅——学生邮箱激活”激活。
由于该邮箱不具有辨识度，学生也可以为邮箱设置别名。学生可以在校园门户“服务”栏找到“E-mail用户开户/变更流程”，设置“变更别名”即可获得一个以 `@hit.edu.cn` 结尾的自定义前缀的邮箱。

* [lib.hit.edu.cn](http://www.lib.hit.edu.cn/)（图书馆）：
图书馆网站有[书目检索系统](http://opac.lib.hit.edu.cn/)、学术资源发现、[图书馆座位预约](http://ic.lib.hit.edu.cn/)等功能。登录书目检索系统后能够查询[当前借阅](http://opac.lib.hit.edu.cn/reader/book_lst.php)、[借阅历史](http://opac.lib.hit.edu.cn/reader/book_hist.php)等。
除此之外，图书馆还为学生购买了大量的线上数据库，可以在[资源/数据库导航](http://www.lib.hit.edu.cn/databasenav)查询。

* [pan.hit.edu.cn](https://pan.hit.edu.cn/)（云盘（内网））：
每名学生拥有 100GB 空间。需在校园门户右侧“个人中心”处开户后方可使用。

* [jwts.hit.edu.cn](http://jwts.hit.edu.cn)（本科教学与管理服务平台（内网））：
本科生最常访问的网站之一，本科教务相关如选课、成绩查询、学分绩查询、教学评价等都在这里完成。附有详细的使用手册，登录后点击首页下载图标，或在 [jwts.hit.edu.cn/pubtzgg/download](http://jwts.hit.edu.cn/pubtzgg/download) 下载。

* [jwts.hit.edu.cn/kjscx/queryKjs_wdl](http://jwts.hit.edu.cn/kjscx/queryKjs_wdl)（空教室查询系统（内网））：
可查找当前学期所有的空教室情况。

* [jwes.hit.edu.cn](http://jwes.hit.edu.cn/)（本科生网上服务系统）：
提供本科生成绩单、排名证明、在读证明等材料制作预约，学生证补办，成绩查询等服务。

* [yjsgl.hit.edu.cn](http://yjsgl.hit.edu.cn/)（研究生教育管理系统（内网））：

* [hqfw.hit.edu.cn](http://hqfw.hit.edu.cn/hqfwdt/hqfwdtsy)（后勤服务大厅）：
后勤报修与咨询（投诉、建议）平台，如有紧急报修推荐拨打[报修页面](http://hqfw.hit.edu.cn/wsbx/bxr/wybx)上的电话。活动中心场地申请也在这里完成。

* [202.118.224.24:8080/selfservice/](http://202.118.224.24:8080/selfservice/)（校园网自助服务系统（内网））：
校园网相关，如上网密码修改，设备管理，余额、套餐查询等。

* [ids.hit.edu.cn](http://ids.hit.edu.cn/authserver/)（统一身份认证设置）；
用于统一身份认证账号密码修改、账号绑定等。

* [ms.hit.edu.cn](http://ms.hit.edu.cn/)（正版软件管理与服务平台（内网））：
提供 Windows、Office 等正版软件的激活服务，需要下载客户端。[ms.hit.edu.cn/help/client](http://ms.hit.edu.cn/help/client) 提供了使用教程。校外激活需要挂 VPN。

* [xg.hit.edu.cn](https://xg.hit.edu.cn/)（学工平台）：
学工相关，如家庭经济困难认定、助学金申请、勤工俭学申请等，以及疫情期间的每日上报和出校（返校）申请。还可以在这里预约心理咨询辅导。

* [booking.hit.edu.cn](https://booking.hit.edu.cn/)（资源预约平台）：
用于部分场馆的参观/使用预约、体测预约等。

* [xyk.hit.edu.cn](https://xyk.hit.edu.cn/)（校园卡服务大厅）：
新版校园卡相关，如充值、修改密码、查询账单等。

* [cwc.hit.edu.cn](http://cwc.hit.edu.cn/WFManager/home3.jsp)（财务信息门户（内网））：
用于助学金（副食补助）发放、酬金发放等查询，绑定银行卡修改等。

* [payment.hit.edu.cn](http://payment.hit.edu.cn/payment/)（缴费平台）：
用于学费、住宿费等的缴费，其他系统发起的支付订单（如网费、校园卡充值等）也会跳转至此。

* [sse.hit.edu.cn/train](http://sse.hit.edu.cn/train/)（C）、[sse.hit.edu.cn/cpp](http://sse.hit.edu.cn/cpp/)（C++）（SSE - 高级语言程序设计能力训练平台）：
高级语言程序设计课程训练平台。

* [acm.hit.edu.cn](http://acm.hit.edu.cn/)（HIT Online Judge, HOJ）：
用于 XCPC 队伍训练，及部分班级高级语言程序设计课的作业与考试。

* [exam.hit.edu.cn](http://exam.hit.edu.cn/)（网络在线考试系统（内网））：
部分课程的考试、某些知识问答等在这里进行。

* [clop.hit.edu.cn](http://clop.hit.edu.cn/)（一区）、[clop2.hit.edu.cn](http://clop2.hit.edu.cn/)（二区）（物理实验中心（内网））
大物实验预约平台。

* [cloc.hit.edu.cn](http://cloc.hit.edu.cn/)（一区）、[cloc2.hit.edu.cn](http://cloc2.hit.edu.cn/)（二区）（化学实验中心选课平台）：
部分化学课程的实验课在这里选课。

* [yx.hit.edu.cn](http://yx.hit.edu.cn/)（迎新服务系统）：
新生报到相关，如信息完善，缴费，查询学号、班级、辅导员、寝室等。

* [git.hit.edu.cn](https://git.hit.edu.cn/)（GitLab 服务）：
校内代码托管平台 GitLab 服务，仅限哈工大邮箱注册。

* [mirrors.hit.edu.cn](https://mirrors.hit.edu.cn/)（开源镜像站）：
开源镜像站，提供各大主流 Linux 发行版的 ISO 文件下载、软件源镜像。

* [survey.hit.edu.cn](http://survey.hit.edu.cn/)（问卷调查管理系统）：
问卷调查系统，部分教师会选择此平台发布问卷。

* [ele.hit.edu.cn](http://ele.hit.edu.cn/)（电控查询系统）：
电控查询系统，可以查询寝室用电量、电费、电费缴费记录

> 如果您有 [Telegram Messenger](http://telegram.org/)，您也可以关注 [@hit_info_digest](https://t.me/hit_info_digest) 获取推送。
