为了减少服务器的压力不少站长还是选择图床存放图片的。所以就搜集一些比较好用的免费的图床（收费的在最后标出）以及yama目前在用的图床。部分搜集于[Nelhelz](https://blog.nfz.moe/)。

### 1.微博图床

堪称国内图床的中流砥柱，很多站长都在用。各种插件和在线上传都层出不穷，使用起来很方便。

- 速度：国内国外都非常快
- CDN：国内分别接入使用了蓝汛、网宿、阿里云 CDN、加速乐等，在国外使用了 Akamai CDN、http://Tierra.Net 的 CDN 等
- HTTPS：支持（不完全支持 HTTP2，得看你被解析到了哪个服务商的节点）
- 域名：
- `ww1.sinaimg.cn` `ww2.sinaimg.cn` `ww3.sinaimg.cn` `ww4.sinaimg.cn`
- `wx1.sinaimg.cn` `wx2.sinaimg.cn` `wx3.sinaimg.cn` `wx4.sinaimg.cn`
- `ws1.sinaimg.cn` `ws2.sinaimg.cn` `ws3.sinaimg.cn` `ws4.sinaimg.cn`
- 等等等等。。。
- [上传地址](http://photo.weibo.com/photos/upload)
- [Chrome 插件](https://chrome.google.com/webstore/detail/新浪微博图床/fdfdnfpdplfbbnemmmoklbfjbhecpnhf/related) 

### 现在限制外链了

### 2.imgur

著名的老牌国外图床，2009 年就开始运行了。图片存储稳定可靠。

- 速度：国外真的挺快，不过国内半墙
- CDN：FastlyCDN（这家 CDN 的很多节点都被墙了）
- HTTPS：支持（不支持 HTTP2）
- 域名： `i.imgur.com`
- [上传地址](https://imgur.com/)

追求国内访问速度的还是别用了吧，不过这家图床是真的足够稳定可靠。开放有 API（还有支持免费匿名上传图片的 ClientKey 可以申请），也有很多第三方插件可以用。

### 3.sm.ms

@showfarm 建的图床，2015 年开始正式运营。

- 速度：现在估计是被滥用了没那么快了 购买了更多节点、修改了服务架构，现在全球速度还是不错的。
- CDN：烧风自建的 CDN，有中国香港阿里云、DigitalOcean 欧洲和 Linode 北美等节点
- HTTPS：HTTP 会被 301 跳转 HTTPS（支持 HTTP2）
- 域名： `ooo.0o0.ooo` `i.loli.net`
- [上传地址](https://sm.ms/)

支持 API 操作，图片存储非常可靠，V2EX 钦点的图床。iOS 和 Android 应用已经分别上架 [iTunes](https://itunes.apple.com/app/sm-ms/id1268411917) 和 [Play Store](https://play.google.com/store/apps/details?id=sm.ms)，甚至有第三方做的 Telegram Bot。在众多公共图床中最看好它和 imgur。

### 4.ooxx

V2EX 上找到的一家老牌图床，2013 年就开始运营了，不过 2017 年年初才在 V2EX 上发帖。

- 速度：CloudFlare 的网络特点，大家都懂
- CDN：CloudFlare
- HTTPS：支持（支持 HTTP2）
- 域名： `i.ooxx.ooo`
- [上传地址](https://ooxx.ooo/)

V2EX 上的介绍说最早是为了收集一些网络图片作为大数据分析和机器学习用的，所以借用机器闲置的带宽搞了这个图床。运营了四年，看起来还会继续运营下去。

### 5.PostImage

- 速度：国外速度杠杠的，国内别被墙就好
- CDN：AdvancedHosted CDN
- HTTPS：支持
- 域名： `s1.postimg.org` `s2.postimg.org`  等。
- [上传地址](https://postimages.org/)

PostImage 图床的介绍说是为了方便用户在 Facebook 和 Twitter 上传图。这个图床用的 CDN 服务商不太有名。

### http://6.UPLOAD.CC

- 速度：看下面一条用的 CDN
- CDN：CloudFlare
- HTTPS：支持
- 域名： `upload.cc` 。
- [上传地址](https://upload.cc/)

这个图床是中国香港人开的，TOS 写的挺详细的。提供了 Android 版 APP（Google Play 上可下载），还提供有 Chrome 和 Firefox 的插件，挺方便的。

### 7.ImgSafe

- 速度：看下面一条用的 CDN
- CDN：CloudFlare
- HTTPS：支持
- 域名： `i.imgsafe.org` 。
- [上传地址](https://imgsafe.org/)

国外一家图床，网站首页有写着累计有图片托管在这个图床。不过  *据说*  偶尔会发生图片丢失的情况；自己权衡。还有要注意的就是这个图床仅能通过拖动的方式上传图片，所以手机上就没法传图了。

### 8.ImgBox

- 速度：实在不敢恭维，估计只有在北美地区的访客才能保证最快的速度
- CDN：两台位于美国的 Leaseweb 的服务器
- HTTPS：支持
- 域名： `i.imgbox.com` 。
- [上传地址](https://imgbox.com/)

虽然用的服务器挺一般，但是毕竟也是一家国外老牌图床了。自 2010 年起开始运营以来，已经托管了上百万张图片，看起来还是令人放心的。

### 9. **免费多图床**

- 速度：图片存储在大平台访问速度非常速度快
- HTTPS：支持
- [上传地址](https://share1223.com/free.html)

### 10. **小贱贱图床**

- 速度：一般般~获取一个简单的外链，图床用的是微博空间，速度很快，但是图片清晰度会变低。
- 每日可以上传图片20张，上传后可以
- [上传地址](http://pic.xiaojianjian.net/)

### 11.聚合图床

- 速度：集合多家图床，速度还是可以的~
- 上传时一张图片会分发至多个图床，同时图片会保存在本站服务器上
- [上传地址](https://www.superbed.cn/)

### 12. **偶流社区图床**

- 免注册，有一定历史，比较可靠
- 限制：图片最大10M，不定期会清理垃圾文件
- [上传地址](https://upload.ouliu.net/)

### 13. **路过图床**

- 支持免注册上传图片，永久存储，支持HTTPS加密访问和调用图片，提供多种图片链接格式
- 限制：最大10M
- [上传地址](https://imgchr.com/)

### 14. **极简图床**

- 主要提供图片上传和管理界面，需要用户自己设置微博、七牛云或者阿里云OSS信息
- 目前站点维护，原因不详
- [上传地址](http://jiantuku.com/)

### 15. **postimg**

- 国外的图床，速度也很快。永久存储免注册，图片链接支持https，可以删除上传的图片，提供多种图片链接格式
- 限制：匿名上传和免费帐户上传的图片仅限于12Mb和10k x 10k像素。高级帐户仅限于24Mb和10k x 10k像素。每批最多限制为1000张图像，如果不够可以创建一个帐户并将多批图像上传到同一个图库中
- [上传地址](https://postimages.org/)

### 16.GitHub

GitHub 一直拥有各种奇怪的用途，被发掘出来当图床也见怪不怪了。

- 速度：国内可以接受，海外速度很快
- CDN：Fastly CDN，几个节点在国内都解禁了的
- HTTPS：支持（似乎不支持 HTTP2）
- 域名： `user-images.githubusercontent.com`

上传方式是新建一个 Repo，然后在 Issue 中传图（直接将图片拖动到 issue 输入框即可），GitHub 会将你的图片分发到 GitHub 用的 CDN 中。

这和使用 GitHub Raw 需要 GitHub 的服务器动态生成文件不同，user-image 这个子域名是 GitHub 专门为静态文件准备的，不会让当年某某抢票助手 CC GitHub 的事情重现的。 当然，这个接口不是公开的。善待 GitHub。

### 17.奇虎图床（360旗下）

- 速度：全球的速度都很好
- CDN：奇虎自己的 CDN，部分节点和网宿合作
- HTTPS：支持（支持 HTTP2）
- 域名：
- `p1.qhimg.com` `p2.qhimg.com` `p3.qhimg.com`  等等
- `p1.qhmsg.com` `p2.qhmsg.com` `p3.qhmsg.com`  等等

在这些域名的前端散列符和根域名之间加上  `ssl` ，如  `p1.ssl.qhmsg.com` ，即可支持 HTTPS 和 HTTP2。

公开上传接口：位于  `wenda.so.com` `bbs.360.cn` 。建议通过后者上传图片，一天只能上传 20 张图片，上传图片的方法就是在 360 论坛（Discuz 驱动）的发帖页面上传图片并插入帖子中，然后右键获得图片地址。图片托管在奇虎图床的风险相比微博图床是要低的，也没有发生过图片丢失的情况。

### 18.boin_space

- 速度：国外速度还行，国内就有点鸡肋
- CDN：阿里云和cloudfare
- [上传地址](https://boin.space/)

### 19.Qchan图床

- 由贴图库提供服务
- [上传地址](http://tuchuang.org/)

### 20.Imgbb

- 最大 16 MB 图片大小. 直接的源图片链接, BBCode代码和HTML缩略图显示
- [上传地址](https://zh-cn.imgbb.com/)

### 21.imggmi

- 速度：国内别用
- 上传后支持图片调整—旋转、长宽缩略图
- [上传地址](https://imggmi.com/)

### 22.Tinypic

- 速度：国内别用
- 这个是很少见的除了图片还能支持视频的
- [上传地址](http://tinypic.com/)

### 现在关门了

### 23.ctrlq

- 速度：国内别用,国外速度也不是很快~
- [上传地址](https://ctrlq.org/images/)

### 24.谷歌图片

- 速度：国内别用
- [ 上传地址](http://photos.google.com/)

### 25.Flickr

- 目前最古老的共享社交网络之一，除了非常适合免费图像托管之外，它还具有编辑工具，可以使用它们来完善图片，然后再将它们组织到相册中，然后也开业生成链接
- 速度：国内别用
- [官网](https://www.flickr.com/)

### 26.imageshack

- 速度：国内别用
- [上传地址](http://imageshack.us/)

### 27.imagevenue

- 速度：国内别用
- [上传地址](http://www.imagevenue.com/hostflash.php)

### 28.freeimagehosting

- 速度：国内别用
- [上传地址](http://www.freeimagehosting.net/)

### 29.Pasteboard

- 速度：国内别用
- 支持剪贴板，用起来很是舒爽~
- [上传地址](https://pasteboard.co/)

### 30.hostpic

- 速度：国内别用
- [上传地址](http://www.hostpic.org/)

### 31.Unsee

- 速度：国内别用
- [上传地址](https://unsee.cc/)

### 32. photobucket

- 很老，不能访客模式上传图片，Tinypic的母公司，有点鸡肋，页面挺好看的 ~
- 速度：国内别用
- [ 上传地址](http://photobucket.com/)

### 33.lensdump

- 无限带宽，原始未压缩图像，保留Exif数据，注册用户更多功能免费使用，图片最大100MB
- 速度：国内别用
- [ 上传地址](https://lensdump.com/)

### 34.cubeupload

- 无限带宽，原始未压缩图像，免费使用，最大5MB图像文件大小
- 速度：国内别用
- [ 上传地址](http://photobucket.com/)

### 35.fb.pics

- 速度：国内可以使用，有点像那个imgbb，支持绝大部分社交平台分享链接，免费账号，25mb的限制，有时候yama会用
- [ 上传地址](http://photobucket.com/)
