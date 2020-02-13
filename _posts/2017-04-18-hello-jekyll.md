---
layout: post
title: 'Hello Jekyll'
date: 2017-04-18
author: Jekyll
cover: 'http://on2171g4d.bkt.clouddn.com/jekyll-banner.png'
tags: jekyll
---
**前言**
随着矿难的来临，迎来了爱折腾的极客们的狂欢。前有400元的GTX1060 5GB，后有300元的4盘位NAS，这不本人出于好奇也入了一台矿渣NAS。但回过头来理性想想也挺不靠谱的，NAS本来就是用于增强数据安全的产品，如今反而在这贪小便宜，早晚有一天会吃大亏。
PS：为了避免广告嫌疑，本文将隐去矿渣NAS的真实名称。
![教你怎么不用U盘引导直装SSD！矿渣NAS安装黑群晖与洗白全教程- Hao4K影音 ](https://data.hao4k.cn/forum/201903/20/142606bqe8emyj92gyj9em.jpg "教你怎么不用U盘引导直装SSD！矿渣NAS安装黑群晖与洗白全教程- Hao4K影音 ") 
既然买都买了，把玩一下还是可以的。尤其一直用惯了QNAP NAS的本人，素闻群晖的系统很好用，那就装个试试吧。目前网上的教程基本都是通过U盘引导的方式进行安装，张K友上也已经有几篇，重复的内容就不写了。将重点介绍，不需要U盘引导，直接通过板载MSATA SSD安装黑群晖及洗白的方法。
![教你怎么不用U盘引导直装SSD！矿渣NAS安装黑群晖与洗白全教程- Hao4K影音 ](https://data.hao4k.cn/forum/201903/20/142606flyw4hj4ijh4ri15.jpg "教你怎么不用U盘引导直装SSD！矿渣NAS安装黑群晖与洗白全教程- Hao4K影音 ") 
不得不说矿渣NAS真的是太便宜了，与它长相一毛一样的空机箱都不止这个价，以至于有人调侃是买机箱送配置。从外观上看这台矿渣NAS几乎为全新，仅仅只有上盖的轻微划伤。
![教你怎么不用U盘引导直装SSD！矿渣NAS安装黑群晖与洗白全教程- Hao4K影音 ](https://data.hao4k.cn/forum/201903/20/142606xvwdv221jlvdhhy5.jpg "教你怎么不用U盘引导直装SSD！矿渣NAS安装黑群晖与洗白全教程- Hao4K影音 ") 
![教你怎么不用U盘引导直装SSD！矿渣NAS安装黑群晖与洗白全教程- Hao4K影音 ](https://data.hao4k.cn/forum/201903/20/142606zb0eltk6tgsbrjr6.jpg "教你怎么不用U盘引导直装SSD！矿渣NAS安装黑群晖与洗白全教程- Hao4K影音 ") 
与NAS的结构相类似，前面板为4盘位抽取结构，托盘材质为金属。下方配有两个前置USB 2.0，开机键和重启键非常小，估计是为了防止误触。
![教你怎么不用U盘引导直装SSD！矿渣NAS安装黑群晖与洗白全教程- Hao4K影音 ](https://data.hao4k.cn/forum/201903/20/142606ghhnjjjasykkgujo.jpg "教你怎么不用U盘引导直装SSD！矿渣NAS安装黑群晖与洗白全教程- Hao4K影音 ") 
背部正中为散热风扇，左侧为电源，从风扇的洁净程度上来看，貌似是新的。IO接口包含3个USB 2.0、1个USB 3.0、2个RJ45、HDMI、VGA以及音频输出，看来除了做NAS之外，HTPC也是能够胜任的。