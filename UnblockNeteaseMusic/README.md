# UnblockNeteaseMusic灰色歌曲 整合版本 quanx and 3h0d0wr0cket 都可配置
**懒人配置：本[仓库](https://github.com/2k1bk/Rules/tree/1)只是为了我个人使用而创建的一个配置仓，没分享无动力，所以大家可以订阅来使用，不用到处去搜集这么麻烦。（内含18条线路）**
**提醒一下，节点已经集成一个通用订阅格式，quanx开启解析器解析(解析不成功请更新解析器或者直接用懒人配置)，小火箭直接就订阅，节点不会缺失，方便^.^**[解析器](https://raw.githubusercontent.com/KOP-XIAO/QuantumultX/master/Scripts/resource-parser.js)地址
ios quanx

1.打开Safari浏览器
  下载添加并信任
  [CA证书](https://raw.githubusercontent.com/2k1bk/UnblockNeteaseMusic/master/ca.crt)

以下请在quanx编辑中添加

2.订阅添加

 https://raw.githubusercontent.com/2k1bk/GeneralSubscribe/main/UnblockNeteaseMusic/UnblockNeteaseMusic.txt, tag=网易云, update-interval=86400, opt-parser=true, enabled=true
 
 3.策略添加

  [policy]

  static=🎧𝐍𝐞𝐭𝐞𝐚𝐬𝐞𝐌𝐮𝐬𝐢𝐜, proxy, direct, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/neteasemusic.png
  
  4.远程分流添加

  [filter_remote]
  https://raw.githubusercontent.com/2k1bk/GeneralSubscribe/main/UnblockNeteaseMusic/QXNetEaseCloudMusic.list, force-policy=🎧𝐍𝐞𝐭𝐞𝐚𝐬𝐞𝐌𝐮𝐬𝐢𝐜, tag=𝐍𝐞𝐭𝐞𝐚𝐬𝐞𝐌𝐮𝐬𝐢𝐜, enabled=true, opt-parser=true

ios quanx[NeteaseMusic]Rules.conf使用说明（这个很重要且简单）

  如果你都使用RULES.CONF配置了就不用跟着上面步骤了，直接下载[CA]证书用就完事了┗|｀O′|┛ 嗷~~ 
  
  简单又方便，能去掉只能听15秒还能下载VIP歌曲

1.打开Safari浏览器下载
  [CA证书](https://raw.githubusercontent.com/2k1bk/UnblockNeteaseMusic/master/ca.crt)

  进入苹果设置-通用-描述文件-UnblockNeteaseMusic Root（点击安装）-回到关于本机-证书信任-把刚刚添加的[CA]文件开启信任 
  
  解锁不了换就节点,并关掉[NeteaseMusic]再开一次再找歌曲测试能否下载和播放。


ios 3h0d0wr0cket

1.添加并使用配置文件

	链接:https://raw.githubusercontent.com/2k1bk/GeneralSubscribe/main/UnblockNeteaseMusic/SSUnblockNeteaseMusic.conf

2.添加订阅

	链接:https://raw.githubusercontent.com/2k1bk/GeneralSubscribe/main/UnblockNeteaseMusic/UnblockNeteaseMusic.txt
	
3.开启连接选择节点就可以使用

4.温馨提醒，

	如果不想添加两个.conf(.conf就是配置文件的意思，即使名字不同后看后缀内容就知道了)的配置文件来不停切换，可以选择文件夹里的”SSUnblockNeteaseMusic.conf“来使用。集成 Apple服务加速/国外常用网站加速等。

就是这么简单，快使用起来吧。
