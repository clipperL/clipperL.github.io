---
layout: post
title:  "【其他】Hexo博客（Next主题）放弃多说，接入网易云跟贴"
date:   2017/4/2 17:55:42
categories: other
---

大概是3月22号，收到“吴小龙同学”微信公众帐号推送的消息，说“多说”评论框即将关闭，心中不免有一丝失落，虽然自从搭建博客到现在没有一个人通过多说给我文章评论，但是难不保以后有人会给我评论，嘿嘿。

多说关闭的原因主要是一直没找到盈利的切入点，唉，多说，走好。

多说走了，但评论框还是要继续搞，“吴小龙同学”微信公众号那天推送的消息上简单地说了几款替代“多说”的产品，最后网易云跟贴（以下简称：云跟帖）胜出。

第二天，我就注册了云跟贴的帐户，其实用的还是网易的帐号，但是填了一些博客站点的信息。

简单地看了一下云跟帖的文档，详细说了Hexo博客如何接入云跟贴，但上面说的是默认的主题，我用的是Next主题，没法照搬文中的方法，只好搜索解决办法。

后来发现Next主题上已经写好了如何接入云跟帖的方法，真心觉得Next主题做的非常好，专门用一个网站来介绍Next的使用方法，还不定时更新内容，我上次看的时候有多说的使用方法，还没有云跟帖的介绍方法，现在已经更新了，加入云跟贴的介绍，点赞。

方法很简单，一行代码就设定，[方法地址](http://theme-next.iissnan.com/third-party-services.html#yungentie)。

> 登陆 [网易云跟帖](https://gentie.163.com/) 获取你的 Product Key。 编辑 主题配置文件， 编辑 gentie_productKey字段，设置如下：
gentie_productKey: #your-gentie-product-key
请注意，您在云跟帖管理后台设置的域名必须跟您站点的域名一致。

gentie_productKey的值要在云跟帖上找。


![](http://upload-images.jianshu.io/upload_images/782269-51a956901056497b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


当我把这些做完后，上传了代码，打开我的站点，却没在文章尾部看到云跟帖。

我把刚才做过的步骤过了一遍又一遍，都没有查到那里出错了。

我还在网上搜索关于云跟帖和Hexo、Next有关的帖子，但都没找的解决办法，眼看着别人的站点都有了令人羡慕的云跟帖，我好着急呀。

这种状态一直持续了将近十天，好挫败，最后我在Next主题的Issues上有人说，不显示云跟帖时请注意你的Next版本问题，我心里想，我的Next版本是V5.1.0，已经够新了，不过报着试试的心态去[Next官方github]()上一看，发现有了小小的更新。

那就更新吧，好久不用git了，手不点生了，用了个笨方法，把代码clone下来，然后修改其中与我有关的代码，然后上传代码，打开我的站点，终于看到了云跟帖了，好开心，看来确实是主题版本落后了，仔细一看Next现在的版本是V5.1.1啦。

最后，死皮赖脸地把我的站点放在这：[www.bigship.cc](http://www.bigship.cc)。