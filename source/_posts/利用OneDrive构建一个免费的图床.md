---
title:  利用OneDrive构建一个免费的图床
abbrlink:  45739
date:  2022-05-31 21:47:13
tags: OneDrive,免费图床
---
## 前言：
有博客的人挺多，但是网站的图片都是占空间的，然后大家就利用网上分享的免费图床，调用图片链接，但是有个问题是免费的毕竟是免费的，存在怕跑路的风险，所以后面大家想了很多办法，这里演示好用的OneDrive挂图片外链，搞图床.
## 准备：
1.[OneDrive](https://onedrive.live.com/)
2.[OneDrive直链获取工具](https://onedrive.gimhoy.com/)
## 开搞：
首先得有OneDrive的5T账号，因为5T的空间足够大部分的图文博客使用了，怎么免费白嫖呢？
两个途径：
1.自己注册5T（可以带Office正版套件，缺点不能自定义生成账号，需要续期）
2.自己购买一个(可以带Office正版套件，自定义生成账号，但是也有后缀，但是要比自己注册的好看一些，自动续期)

这里肯定推荐自己[注册](https://www.bilibili.com/read/cv16735126?from=search&spm_id_from=333.337.0.0)，比较不会跑路，觉得麻烦的就可以买一个
接着我们准备一张图片作为演示：
![](https://link.jscdn.cn/sharepoint/aHR0cHM6Ly9kcXJ6cy1teS5zaGFyZXBvaW50LmNvbS86aTovZy9wZXJzb25hbC9saW5kYV9jZWR1X21lL0VVRVNHM1lhQzBaQW5uS01QNUlJeWg4QmNIZGpNbnBibzhwSUJxQWhZQmgweVE_ZT05c0tiU3g.png)
首先把它上传到OneDrive，然后分享：
![](https://link.jscdn.cn/sharepoint/aHR0cHM6Ly9kcXJ6cy1teS5zaGFyZXBvaW50LmNvbS86aTovZy9wZXJzb25hbC9saW5kYV9jZWR1X21lL0VZWEE4Q0VsRmFwRXRaWmFFVUhIWVdrQnFBRXBDamJLVFpKaWNPZ1p6YUtMTFE_ZT1DYTVrc2w.png)

接着把链接复制到[OneDrive直链获取工具](https://onedrive.gimhoy.com/)，选择对应的图片格式，一键转链接.
![](https://link.jscdn.cn/sharepoint/aHR0cHM6Ly9kcXJ6cy1teS5zaGFyZXBvaW50LmNvbS86aTovZy9wZXJzb25hbC9saW5kYV9jZWR1X21lL0VjT0szN25ZcnVWRHZmVG0tTjlmV2p3QmRfeVcxeG9FQUhSbzFSUGJKS2xnUUE_ZT1lV0xhblA.png)
得到我们需要的图床链接可以进行调用下面是演示的转成功的图床链接
``` bash
https://link.jscdn.cn/sharepoint/aHR0cHM6Ly9kcXJ6cy1teS5zaGFyZXBvaW50LmNvbS86aTovZy9wZXJzb25hbC9saW5kYV9jZWR1X21lL0VjT0szN25ZcnVWRHZmVG0tTjlmV2p3QmRfeVcxeG9FQUhSbzFSUGJKS2xnUUE_ZT1lV0xhblA.png
```
## 结尾：
市面上有很多免费的图床，有些需要登录，有些是直接上传转链接，但是都有可能某个图床挂掉，所以最方便的就是自己搭建图床，但是白嫖党又多，于是产生了：
1.github搭建图床（国内访问随机出图，因为本来就是半墙状态）
2.gitee搭建图床，在今年官方已经开启了防盗链模式（最好的方案失效了）
3.Google Drive搭建图床（这么更优秀，需要全墙状态才能显示图片）
4.OneDrive搭建图床（个人感觉是最优的方案了，毕竟微软在我们国内也是有生态链的，所以不存在不能访问的情况，而且5T空间也够一些图文博客用了）
## 再会！