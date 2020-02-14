---
layout: post
title: 'jellyfin安装ssl证书达到https访问'
subtitle: ''
date: 2020-02-09
categories: NAS
cover: 'http://on2171g4d.bkt.clouddn.com/jekyll-theme-h2o-postcover.jpg'
tags: jellyfin ssl https 影音 服务器
---
1、在梅林固件安装lets encrypt插件，插件中DNS服务商选择cloudflare，输入coudflare key（并非是zone key和api key）和email，申请ssl证书。

2、ssh连接梅林固件，打开/koolshare/acem/你的域名  文件夹，利用openssl将ssl证书转换成pfx证书：openssl pkcs12 -export -out ssl2_me.pfx -inkey ssl2_me.key -in ssl2_me.crt，然后输入密码。

3、用winscp连接梅林固件，取出刚才生成的.pfx文件

4、进入jellyfin控制台，在联网里的自定义ssl证书路径选择刚才的.pfx证书，并输入证书密码。

5、保存即可。