﻿#zogna cat mouse 

### 官方发布点   https://github.com/zogvm/zogcm
### 链接:	http://pan.baidu.com/s/1b0HXkq
### 链接:	https://yunpan.cn/cSHwWVmR4q2Ne （提取码：d487）
### 建议，QQ群：193585959

* 支持WIN,MAC，UBUNTU
* 如果您患有下载综合征，音视频囤积症。该软件就是您的福音！

## 声明
* 软件**无毒无广告无后台，也不插入任何的软件**。如果你下载的不是这样的，请务必小心。
* 软件**免费，也不接受任何捐款**，除非我特别特别的困难了。当然，有工作可以介绍给我，不爱加班。谢谢~
* 把软件嵌广告，流氓软件，收费，任意修改等行为。俺从内心深处鄙视你们,宁愿在三线城市工作也不去你们公司。

### 软件前身
* ZOGVM的扩展库 停止更新并维护。它将成为全新的软件，再也不是鸡肋了。
* 以后ZOGVM专注**（功能单一，技术太烂不会整合）**于本地视频的管理。
* 而ZOGCM专注**（功能单一，技术太烂不会整合）**于获取资源并下载视频。

### 最初的想法：（我有一个好的爱迪尔，就缺一个程序员了~）
* 本软件于2016.3.11日开工编写：
* 我在公司选择片，然后加到下载框，就会推送到我家的小电脑的RSS服务器上。然后NAS订阅我家的RSS，然后自动下片。

### 基本架构
* zogc.exe (zogna cat)是使用QT/C++ 编写的有界面的数据管理器（其本身运行不会联网）
* zogm.exe (zogna mouse)是PY写的命令行的采集器。（会联网）
* zogrs.exe (zogna rss)是PY写的RSS服务。（目前不提供）
* 流程：一只猫在“获取最新”的时候，在**2分钟之内**把游走在任务管理器里的**几十只**老鼠给抓起来。
*        请尽量不要中途强制停止，否则可能有漏抓之鼠。

### 关于LOGO
* 为啥zogc明明中文叫猫，却用猫头鹰的图？为啥zogm是老鼠，却是用兔子的图？
* 因为俺也喜欢兔兔。。。而且他们正好也是捕与被捕的关系。

### 关于界面
* 写这个软件就知道我有多懒了。。所以界面依然使用zogvm的界面。一如既往的丑
* 很多人觉得丑，如果你是美工，就快来帮帮我吧。。不然就别BB了。

##视频搜寻系统 zogcm 特性(1.0)
* 1.定时获取最新视频资源
* 2.支持自定义字符高亮标记和收藏
* 3.支持自定义的微博追踪
* 4.支持在线/本地搜索

### windows: 管理员权限运行 zogc.exe
### mac osx: 解压dmg，找到zogc进行运行
### ubuntu: 解压后，运行./zogcm.run

## 快速入门
* 1. 点击左下角的“获取最新”按钮，最多等待2分钟。
* 2. 点击左上角的矩形按钮（过滤项）自行添加高亮选项。

## 初级进阶(功能未完善，除非网站被封，或者你要出国，否则没啥用)
* 1. 将externdb的数据解压后拷贝到软件的目录下，形成以下结构：
*   zogcm/externdb/lyw.db
*   zogcm/externdb/cili.db
*   点击左上角的“本地存档”按钮，左侧列出本地库的选项，可以对进行搜索以及查看。

## 新知:
* 1. 任务管理器里出现几十个zogm.exe属于正常现象
* 2. 如果平常不经常挂着进行自动更新，最好以白天4小时/频率的手动刷新
*    (比如早上8点多一次，中午一次，傍晚一次)，才能保证采集的完整性。
*    (动漫网站更新非常迅速，所以有时效性)
* 3. 数据是直接从各个网站获取，中间无通过任何服务器。


# 免责声明
* 数据不在我电脑里，也不架设服务器。数据在哪？在GITHUB上，在你们使用者的电脑里。
* 关于这些网站，我只是懒，没别的想法。
* 我其实很喜欢这些网站，没什么流氓广告，也很新，所以我才会收录进来。大家没事可以多去点网站，支持下。谢谢。


### 扩展资源：
* 人人更新到2016.05.06日 第99601号
* TW版国家地理更新到2016.03.06日
* 蓝影网更新到2016.03.29日
* NHK更新到2015.11.26日
* MVG更新到2016.03.29日
* MP4吧更新到2016.03.29日
* HACG更新到2016.04.07日
* BT0更新到2016.04.18日
* MSDN更新到2016.04.19日
* 动漫花园更新到2016.04.20日


## 界面

 ![image](https://raw.githubusercontent.com/zogvm/zogcm/master/preview1.png)
 ![image](https://raw.githubusercontent.com/zogvm/zogcm/master/preview2.png)