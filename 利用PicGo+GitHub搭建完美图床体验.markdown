---
title: 利用PicGo+GitHub搭建完美图床体验
date: 2020-09-11 20:25
---
# 利用[PicGo](https://github.com/Molunerfinn/PicGo)与[GitHub](https://github.com)搭建完美图床体验
![](https://raw.githubusercontent.com/MaskBR/ImageHost/master/img/20200911203315.png)
> 所谓图床工具，就是自动把本地图片转换成链接的一款工具，网络上有很多图床工具，就目前使用种类而言，PicGo 算得上一款比较优秀的图床工具。它是一款用 Electron-vue 开发的软件，可以支持微博，七牛云，腾讯云COS，又拍云，GitHub，阿里云OSS，SM.MS，imgur 等8种常用图床，功能强大，简单易用
之前一直苦于Markdown的插入图床的图片不方便(当然其实也没写几篇文章🤦‍♂️)，文章内的图片多以本地的形式保存在文章相同路径下。这就导致每次写文章使用图片时，总要将复用的图片文件来回拷贝。大大影响写作心情和效率(~~当然不写文章的我其实没这么多烦恼🤣~~)。不过，这些借口与烦恼都在发现了[PicGo](https://github.com/Molunerfinn/PicGo)时迎刃而解。[PicGo](https://github.com/Molunerfinn/PicGo)真是一个让人相见恨晚的宝藏应用!
为了体现一下[Snipaste](https://www.snipaste.com)与[PicGo](https://github.com/Molunerfinn/PicGo)天衣无缝地配合，于是就有了这篇[PicGo](https://github.com/Molunerfinn/PicGo)使用指南。
- [PicGo](https://github.com/Molunerfinn/PicGo)下载与安装
- [GitHub](https://github.com)设置免费图床
- [PicGo](https://github.com/Molunerfinn/PicGo)配置
- [Snipaste](https://www.snipaste.com)与[PicGo](https://github.com/Molunerfinn/PicGo)配合
- 总结
## [PicGo](https://github.com/Molunerfinn/PicGo)下载与安装
打开[PicGo下载链接](https://github.com/Molunerfinn/PicGo/releases)后,按照对应系统下载后安装，非常简单!(~~这段纯属凑字数~~)
![](https://raw.githubusercontent.com/MaskBR/ImageHost/master/img/20200911210713.png)
## [GitHub](https://github.com)设置免费图床
1. 注册[世界最大同性交友平台](https://github.com)
    ![](https://raw.githubusercontent.com/MaskBR/ImageHost/master/img/20200911212338.png)
    整个过程和日常注册网络账号没啥区别，就不细写了……(此处省略1024个字)
2. 点击右上角Reposirories旁new按钮,创建图床仓库。
    ![](https://raw.githubusercontent.com/MaskBR/ImageHost/master/img/20200911224352.png)
    ![](https://raw.githubusercontent.com/MaskBR/ImageHost/master/img/20200912144337.png)
3. 生成新tocken，等会配置PicGo时会用到
     ![](https://raw.githubusercontent.com/MaskBR/ImageHost/master/img/20200911224131.png)
    ![](https://raw.githubusercontent.com/MaskBR/ImageHost/master/img/20200912164544.png)
    ![](https://raw.githubusercontent.com/MaskBR/ImageHost/master/img/20200912164641.png)
    ![](https://raw.githubusercontent.com/MaskBR/ImageHost/master/img/20200912164801.png)
    ![](https://raw.githubusercontent.com/MaskBR/ImageHost/master/img/20200912165148.png)
    ![](https://raw.githubusercontent.com/MaskBR/ImageHost/master/img/20200912165252.png)
    ![](https://raw.githubusercontent.com/MaskBR/ImageHost/master/img/20200912165811.png)
至此，我们的免费图床就设置好了。
## [PicGo](https://github.com/Molunerfinn/PicGo)配置
![](https://raw.githubusercontent.com/MaskBR/ImageHost/master/img/20200912171307.png)
自定义域名设置方式为:
***https://raw.githubusercontent.com/用户名/仓库名/分支名***，这样设置完毕后，每次上传完图片，就会将图片地址按照特定格式自动复制到剪贴板，大大方便后续插入使用。
点击确定后，[PicGo](https://github.com/Molunerfinn/PicGo)的[GitHub](https://github.com)图床就配置完毕了。
**补充说明**:
[PicGo](https://github.com/Molunerfinn/PicGo)可以使用默认快捷键``Command/Ctrl+shift+P``进行快速将剪贴板图片上传至默认图床，如果和其他软件存在快捷键冲突的话，可在[PicGo](https://github.com/Molunerfinn/PicGo)设置中进行更改。
[PicGo](https://github.com/Molunerfinn/PicGo)设置中还有许多其他人性化的设置，在此就不一一展开了，各位可以自行摸索修改。
## [Snipaste](https://www.snipaste.com)与[PicGo](https://github.com/Molunerfinn/PicGo)配合
引用官网内容简单介绍我心目中的**截图神器**[Snipaste](https://www.snipaste.com)
> Snipaste 是一个简单但强大的截图工具，也可以让你将截图贴回到屏幕上！下载并打开 Snipaste，按下 ``F1`` 来开始截图，再按 ``F3``，截图就在桌面置顶显示了。就这么简单！
>你还可以将剪贴板里的文字或者颜色信息转化为图片窗口，并且将它们进行缩放、旋转、翻转、设为半透明，甚至让鼠标能穿透它们！如果你是程序员、设计师，或者是大部分工作时间都在电脑前，贴图功能将改变你的工作方式、提升工作效率。
>Snipaste 使用很简单，但同时也有一些较高级的用法可以进一步提升你的工作效率。感兴趣的话，请抽空读一读[用户手册](https://docs.snipaste.com/zh-cn/)。
>Snipaste 是免费软件，它也很安全，没有广告、不会扫描你的硬盘、更不会上传用户数据，它只做它应该做的事。
日常使用[Snipaste](https://www.snipaste.com)的方式十分简单。只需要设定好开机启动程序，然后在你需要的时候直接按下``F1``键就可以随时随地的愉快截图了!而且[Snipaste](https://www.snipaste.com)内置的边界识别非常准确，不仅如此，还能以1像素为单位进行边界调整。保证每一次截图都能调整到最理想到的状态。至于自带许多其他实用的小功能在此就不一一列举，毕竟本篇文章还是以介绍PicGo为主。
![](https://raw.githubusercontent.com/MaskBR/ImageHost/master/img/%E4%BD%BF%E7%94%A8snipaste%E6%88%AA%E5%9B%BE.png)
截图并标注完毕后，直接``Command/Ctrl+C``复制截图至剪贴板，再``Command/Ctrl+shift+P``，瞬间截图就传入到图床了!而且此时切换到markdown``Command/Ctrl+V``，一副截图就完美地插入了文章，流畅的操作让人根本停不下来!
## 总结
其实除了[PicGo](https://github.com/Molunerfinn/PicGo)与[Snipaste](https://www.snipaste.com)外，日常学习工作中我还会用到许多其他优秀的软件，他们大大提高了我的办事效率。正是这些优秀的软件使我明白了如何优雅爽快地解决许多日常中未曾注意过的细节。开发者通过PDCA的循环模式，使软件被打磨的越发精致迷人。希望未来能出现越来越多的"宝藏"软件!真是让人期待啊!