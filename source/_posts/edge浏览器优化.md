---
title: edge浏览器优化
tags:
  - 优化
  - blog
categories:
  - 实用
  - blog
keywords: 实用，优化，技巧，blog
cover: 'https://s1.ax1x.com/2023/07/30/pPpVW7Q.jpg'
abbrlink: 17714
---
# edge浏览器优化

    >每次打开Microsoft edge浏览器就发现它的资源占用率较高，这让我本不怎么样的电脑雪上加霜，下面提出几点方法优化该问题

![](https://cdn.jsdelivr.net/gh/GianYue/images-bed/img/2023%2F08%2F1690647379965-eda9b3.png)

## 方法一 浏览器性能设置

    过多的插件也会导致浏览器占用过多资源，即便是关闭了浏览器也会继续运行插件

在搜索栏输入 `edge://settings/system `

* 关闭 **启动增强**
* 关闭 **在 Microsoft Edge 关闭后继续运行后台扩展和应用**
* 关闭 **使用硬件加速(如可用)**
* 打开 **效率模式**
* 打开 **使用标签页休眠功能节约资源**
* 打开 **淡出睡眠标签页**
* 最后重启浏览器

![](https://cdn.jsdelivr.net/gh/GianYue/images-bed/img/2023%2F08%2F1690648407276-800c28.png)

![](https://cdn.jsdelivr.net/gh/GianYue/images-bed/img/2023%2F08%2F1690648562667-7a4633.png)

## 方法二 关闭图像渲染

    在搜索栏输入` edge://flags`跳转后输入GPU

* 关闭 **GPU rasterization**
* 关闭 **Accelerated 2D canvas**
* 重启浏览器即可

![](https://cdn.jsdelivr.net/gh/GianYue/images-bed/img/2023%2F08%2F1690649340376-0934ab.png)

## 方法三  禁用不常用的插件

    在搜索栏输入`edge://extensions/`

* 选择你需要关闭的插件
* 重启浏览器即可

![](https://cdn.jsdelivr.net/gh/GianYue/images-bed/img/2023%2F08%2F1690649775153-b21fb6.png)

## 方法四 清理浏览器缓存

    缓存过多也是造成卡顿的原因之一

* 在搜索栏输入 `edge://settings/privacy`
* 找到 **清理浏览数据** 选择即可

  ![](https://cdn.jsdelivr.net/gh/GianYue/images-bed/img/2023%2F08%2F1690652881759-d9b334.png)

## 方法五 关闭自启动

 Microsoft edge浏览器是默认开机自启动的，关掉自启动可以使得其在开机第一时间资源占用减少，更加丝滑

* 打开任务管理器
* 点击 **启动，找到edge浏览器，右键单击选择禁用即可**

![](https://cdn.jsdelivr.net/gh/GianYue/images-bed/img/2023%2F08%2F1690650755390-a29820.png)

## 方法六 关闭浏览器的自动更新

Microsoft edge浏览器也是默认自动更新的，即使你没有打开浏览器，他也会在后台占用资源，悄悄更新,造成卡顿

* 在任务栏点击**搜索**，输入**服务**，点击**最佳匹配**下的应用

![](https://cdn.jsdelivr.net/gh/GianYue/images-bed/img/2023%2F08%2F1690651089510-b2f7ae.png)

* 在弹出的页面往下拉，找到如下三个选项，右键单击，点击属性，将他们的启动类型改为手动即可

![](https://cdn.jsdelivr.net/gh/GianYue/images-bed/img/2023%2F08%2F1690651953004-63a438.png)

![](https://cdn.jsdelivr.net/gh/GianYue/images-bed/img/2023%2F08%2F1690652148145-870141.png)

当然，如果想要恢复更新也比较简单，打开edge浏览器，在搜索栏中输入 `edge://settings/help ` 就可以检查更新了

![](https://cdn.jsdelivr.net/gh/GianYue/images-bed/img/2023%2F08%2F1690652490681-cb3ade.png)

## 方法七 优化电脑硬件配置

    像作者这台远古神机，就是通过换机械硬盘为固态硬盘，加大内存来续命的，至于更古老的电脑我则无能为力了
