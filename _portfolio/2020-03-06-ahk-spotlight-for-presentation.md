---
title: "同心抗疫--AHK Spotlight让在线教学/演示汇报更自如"
lang: zh
ref: portfolio/2020-03-06-ahk-spotlight-for-presentation
permalink: /portfolio/2020-03-06-ahk-spotlight-for-presentation
excerpt: "基于AHK模拟罗技Spotlight探照灯功能，让网络教学、演示汇报等更加自如<br/><img src='/images/spotlight.jfif'>"
collection: portfolio
date: 2020-03-06

category: portfolio
tags:
  - tool
  - spotlight
  - teaching
  - presentation
---

2020年是不平凡的一年，我们度过了不平凡的寒假，迎来了不平凡的开学。新冠肺炎疫情像阴霾一样笼罩全国，清华大学2月3日通过在线直播的形式师生同上一堂课，在全国率先提出“延期开学、如期开课”。网络授课给教师带来各种挑战，从课程内容、组织到交互方式、网络状况等等，不一而足。

AHK Spotlight小程序就是在这样的背景下产生的，它基于AutoHotKey（AHK）实现，通过AHK脚本模拟了罗技Spotlight功能，可以让你方便地基于探照灯效果高亮、突出PPT演示的关键内容，为你的网络教学、答辩汇报增光添彩。特共享给大家使用，点此[下载]({{ site.baseurl }}/files/AHK Spotlight-v1.5.zip)可节约几百大洋。具体安装及使用教程如下。



## A 安装（开机自启动）

1. 把压缩包解压到某个文件夹，右键点击SpotLightStarter.exe，选择“创建快捷方式”

2. 把创建的快捷方式文件，复制到如下路径即可`C:\ProgramData\Microsoft\Windows\StartMenu\Programs\StartUp`，可以直接复制前面的地址粘贴到文件管理器的地址栏打开相应的文件夹

3. 重启电脑后，右下角出现绿色框中间一个白色H的图标，表明小程序正常运行

4. 也可不安装，那么每次启动电脑后，需到对应文件夹双击SpotLightStarter.exe，启动小程序

<video poster="/images/2020-03-06-AHK-Spotlight-install.jpg" controls preload>
    <source src="/videos/2020-03-06-AHK-Spotlight-install.mp4" media="only screen and (min-device-width: 568px)"></source> 
    <source src="/videos/2020-03-06-AHK-Spotlight-install.iphone.mp4" media="only screen and (max-device-width: 568px)"></source> 
</video>



## B 使用

1. 运行PPT或其他程序时，点击两次`Shift`启动Spotlight效果

2. Spotlight效果中按`Esc`键可退出效果

3. Spotlight效果中，按住字母`S`键的同时按上下箭头可放大或缩小Spotlight的大小

<video poster="/images/2020-03-06-AHK-Spotlight-toturial.jpg" controls preload>
    <source src="/videos/2020-03-06-AHK-Spotlight-toturial.mp4" media="only screen and (min-device-width: 568px)"></source> 
    <source src="/videos/2020-03-06-AHK-Spotlight-toturial.iphone.mp4" media="only screen and (max-device-width: 568px)"></source> 
</video>

注：小程序实现过程参考了AHK论坛的帖子（地址为：https://autohotkey.com/board/topic/33038-mspot-mouse-spotlight-example-using-winset-region/），特此表示感谢。


春天不远，诸君努力！

**本文首发于微信公众号，扫码关注了解更多.**

![微信公众号二维码]({{ site.baseurl }}/images/wechat_qr_code.gif)
