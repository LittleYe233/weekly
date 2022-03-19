---
title: "Week 2"
date: 2022-03-18T21:28:16+08:00
---

## 本周群聊

### 群名怎么还是 `*` ？

为了表示对腾讯强制修改我们群群资料的抗议，我们决定将群名改为 `*`，群资料改为 `-` ，~~绝对不是我们修改不了~~。并且为了表面我们态度的坚决，我们解散了 LUG Core 的 QQ 群。

并且因腾讯加大了对群聊资料的审查，出现群友群昵称变成 `*` 的情况。虽然是群友自己改的但还是要谴责腾讯的恶劣行径。

<!--more-->

### Dragonwell 的黑魔法

某群友发现 Dragonwell JRE 的黑科技 Wisp ，可直接处理多线程程序的字节码转换成 JVM 级别的协程。

### 群友锐评 Java

“我觉得……不如……kotlin。”群 kotlin 们吹如是说。

### 群友锐评咸鱼 8G RAM 树莓派标价 1200 CNY

“什么理财产品。”

> 原价 75 USD

### Markdown shebang

![markdown shebang](https://user-images.githubusercontent.com/73573254/158622078-0b426747-fa6a-4e2d-968a-4a0d8cf418c3.jpg)

### OOP 实验代码模板 belike

![OOP](https://user-images.githubusercontent.com/73573254/158622766-39ecd266-76b3-41da-a86b-b22881f53873.png)

### 10999 CNY 的主机 belike

![主机](https://user-images.githubusercontent.com/73573254/158624067-56209b6a-9fc2-482b-9ede-5eb4a150281f.jpg)

### 群机器人/群史官上线啦

结果光速被风控。

### 小说防沉迷推送系统

某群友设想，开发一个小工具，把小说文本切开几份定期推送 RSS，既能满足每日送饭需求，又可以防沉迷。

> “有没有一种可能，我是说如果，网络小说本来就是作者一天更个几章推到你面前。”

### 越共探头

某群友表示想将 OOP 实验的飞机大战替换素材做成东方。

### JetBrains 的缩写与译名

JetBrains 官方似乎考虑把 JB 作为其官方缩写——火星旧闻

JetBrains 在 Youtube 的广告中译名为 “喷射大脑”。

### B 站某些视频视频码率比音频还低

![截图](https://user-images.githubusercontent.com/17264509/158553639-3a0d0250-11ac-450e-a2eb-6a5962c44d7a.png)

### 群友新活

某群友整了个新活，用 bash 脚本实现了自动上报。[仓库](https://github.com/CH3CHOHCH3/HITSZ-DailyReport)

某群友整了个活上活，基于前者脚本与 GitHub Action 实现了自动上报。[仓库](https://github.com/SoraShu/HITSZ-DailyReportAction)

### Windows 的幸福工作生活

群友表示羡慕 Windows 的幸福工作生活。

>  “它想什么时候停止工作就什么时候停止工作”

Linux user 羡慕 Windows，这是否是一种 ntr。

### 安卓内核版本之谜

原来 Android 的 Linux kernel 版本是跟 SoC 绑定的。比如 855 就是 4.14, 865 就是 4.19.

### 群友锐评 IM

> 真正的聊天软件要做减法。
> 
> 我觉得 Socket 就非常适合做 IM，它非常地通用，并且可以传递任何信息，还是即时的。
> 
> IM 不是即时通讯吗，那能即时通讯的就是 IM.

### 群友锐评 GitHub Action

这玩意就是一个写起来很奇怪的服务器

## 本周旧闻慢递

### 本刊创办的艰辛历程

本社~~或者应该说本兴趣小组，毕竟是连官方身份都拿不到的屑 lug~~ 在上周由某萝姓管理 (诶，好像怪怪的) 的发起下，本社周刊，即 HITsz LUG weekly 正式创办。以下简要介绍本刊创办历程。

1. 萝姓发起者撰写周刊初稿后将仓库丢给管理 Sora ，Sora 一边看番一边把 weekly 框架架好，在发布 demo 时二度将 `baseURL` 填错，且 `page` 页的 `url` 还是错的直到萝姓管理发现并修改了这一错误。萝 锐评：“我怀疑你是在晕车状态做的 repo。”
2. 管理 yukko 接下了写主题 css 的重任，并且更新了网站。但与此同时 LUG 资深前端——管理 launchd 直接调整了主题，该工作惨遭丢弃。“所以我重复劳动了是吧。”
3. weekly 的主题采用了 git submodule 的模式引用，为 lauchd 的工作带来很大的麻烦。“是 git submodule 的锅。” 每次出现问题时 launchd 总是气愤地说。
4. 由于网站架设时，域名持有者 Lu 正在与 LaTex 进行斗争，于是产生了 github pages、launchd fork 的仓库，以及后来 Lu 在 cloudflare pages 上部署的网页三个站，~~史称三家分 weekly~~(什么分布式周刊)，后由 群主 进行了大一统。
5. 经过多日斗争，管理 Shiroki 完成了图片版周刊的自动化生成。
6. launchd 表示这个主题写得真烂，并向该主题的仓库提交了多个 issue 与一个 pr 。

### 微软开始在 Win11 文件资源管理器测试“广告”

“呸！”  ——by 萝，于第一周周刊

### 腾讯云免费领一个月 4C4G8M

晚了，已经领完了 😂 ——真·旧闻慢递

### 流氓高速下载器公司被 315 曝光

> 马鞍山百助网络科技有限公司

正道的光。

### Golang 1.18 正式发布，支持泛型

> 小而美（不是  
> 大道至简  
> —— by 某群友

### Apple 推出 "格局打开" Emoji

然而在 安卓/win 上都是 口口口。

![图片](https://user-images.githubusercontent.com/29816865/158721096-3a104371-e607-4db3-8883-3353412cd74c.png)

### LUG Sticker 上新

越发离谱的 LGTM.

> LGTM: Look Good To Me，一般用在 GitHub 的 PR 请求评论里，表示 approve 别人的 PR

![离谱](https://camo.githubusercontent.com/cc4b927ac1201bacf600a3db76ff7f2541253080f554fdc2f525a1919e915643/68747470733a2f2f6e2e686f70702e746f702f6c67746d2d732e737667)

### Wiki 上新

新增了一篇介绍域名与 HTTPS 与服务管理的文章：[域名与 HTTPS](https://wiki.hitsz.org/popular-science/domain-and-https/)

### 喜报：你校数据结构课程有 OJ 🌶️

好。~~然而考试还是要手写代码~~

### OpenSSL 远程执行漏洞

计算模平方根的 `BN_mod_sqrt()` 包含 bug 会导致无限循环，它能用于发动拒绝服务攻击。

OpenSSL 3.0.2 跟 1.1.1n 修复了该漏洞。

### ctags 还在

![ctag](https://user-images.githubusercontent.com/19954398/158769580-c209065e-60b5-4139-b757-8804108e2a11.png)

> 什么旧时代（

## 奇奇怪怪的 Bug

### error success !

某群友表示遇到了 `error success` 的 log ，并表示希望入选今年茅盾文学奖。

### AutoCorrrect 误杀

![截图](https://user-images.githubusercontent.com/73573254/158619762-cb2541c4-8efc-49ba-b529-cf5acec34ba0.jpg)

### JVM 🍎专有 bug ？

某群友在做 OOP 实验时遇到了 `java.lang.NoSuchMethodError: accessibilityHitTest` 报错。

### WSL 里的 Hugo 预览不了？

试试把端口改成一万以上。

### 雨课堂比油管耗电

在某群友的 Chromebook 上，虽然都是开网页放视频，但雨课堂耗电的速度不知道为什么快了一些。

### Miniflux 配 Wallabag 的奇妙行为

> Miniflux 是一个可以自建的 RSS 拉取服务器，Go 编写，极简主义
> 
> Wallabag 是一个可以自建的书签管理与网页保存器，可以作为 Pocket 的替代品

在 Miniflux 里填了自建 Wallabag 的 URL 后，Miniflux 会 **先做 DNS** 得到 IP 地址，然后直接往 IP 地址发包，导致基于子域名的反代无法工作。最后直接给 Miniflux 填了处在同一个 Docker Network 里 Wallabag 容器的地址完事。

### Firefox 又有 Bug

某群友：

> Firefox 不支持 woff2，而且在 Linux 下对于中文的 fallback 有问题。
> 
> 准确来说是非 open type 的 woff2

### python 3.10.0 版本识别错误

VS Code 识别 Python 版本出错，Pylance 拓展报错。

某群友：成功浪费了我半个晚上的时间

## 这周看了啥

### 代码优化卷翻天：莫队交易赛复盘

是的，就是 OI 里的 "莫队", 莫涛，曾经的国家队队长，举行了一场模拟高频交易的比赛。[这篇知乎文章](https://zhuanlan.zhihu.com/p/470766162)介绍了作者，一位系统工程师的参赛经历与赛后思考。

### 原来这才是 Socket!

一篇介绍 Socket 的[微信文章](https://mp.weixin.qq.com/s/Syee1T7JcnqACs5TJf-cLA).

### 如何有理有据地说服其他程序员

[这篇博客](https://chinese.catchen.me/2021/06/how-to-argue-with-another-programmer.html)介绍了程序员开发工作中沟通的常见问题与解决方案。

> **TL;DR** 当两个相对聪明和胜任的程序员对同一个问题持有截然不同的观点时，往往问题出现在大家对问题的定义不一样。争辩观点对错的往往并不能达成一致，这时候必须先确认大家在讨论的是同一个问题。如果没办法对齐（align）问题，尤其是当双方的优先级（priority）不一致时，争辩问题的解决方案是不可能有结果的。

### 开源社区的暗面

最近被广泛使用的前端包 `node-ipc` 被发现加入了疑似恶意的功能：当检测到用户 IP 地址在俄罗斯/白俄罗斯时，有概率覆写用户的文件。在正常情况还会在用户的桌面/OneDrive 创建特殊的文件，[详情可见 v2ex](https://www.v2ex.com/t/840562).

之前，著名前端包 faker.js 作者愤然删库，抗议大公司白嫖其项目。该项目也有投毒行为。

世界上没有绝对好的东西，这篇[博客](http://qingbob.com/darkside-of-the-opensource/)里作者反思了目前开源的各种问题。

> 某群友：所以还是 **自由软件** 香

### 如何使用 Shell

这篇[博客](https://a-wing.top/shell/2021/05/01/sh-compatibles-history.html)介绍了 \*nix 上各种各样的 Shell 的历史跟特性，并且在最后简介了他自己的 Shell 配置。

### 群主推荐

- [Systemd service hardening](https://www.ctrl.blog/entry/systemd-service-hardening.html)
- [Best practice to deply Minio](https://blog.min.io/best-practices-minio-virtualized/)
- [A C compiler written in Zig](https://github.com/Vexu/arocc)

## 征稿

weekly 开放征稿。欢迎投稿每周奇闻轶事。[投递窗口](https://github.com/hitszlug/weekly/issues)
