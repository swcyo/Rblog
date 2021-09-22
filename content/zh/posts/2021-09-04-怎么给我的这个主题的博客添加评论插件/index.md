---
title: 怎么给我的这个主题的博客添加评论插件
author: 欧阳松
date: '2021-09-04'
slug: comment-plugin
categories:
  - 教程
  - Disqus
  - Utterances
tags:
  - 评论
---

   hugo-prose主题是支持评论插件的，但是yihui老师的示例教程只写了Disqus和Utterances两个单词，那么应该如何添加上呢？

## Disqus

   先去Disqus官网申请一个账号，然后直接在根文件夹（Blogdowm）或主题文件夹（hugo）的config.yaml上的disqusShortname: ""那行里面，写上你注册的ID就可以了，然后在所有的页面底下都可以显示出来。

   但是，这里有个最大的Bug，那就是被墙了，所以基本上都只会显示大陆用户需要翻墙才能评论。。。

## Utterances

   Utterances是Github上的一个轻量级评论插件，不担心倒闭问题，Github上有gitment、Gitalk和Utterances三个评论插件，只要申请开通即可，大神没有说太多怎么安装，不过搜索一个"hugo Utterances"也可以得到答案，这里讲一个简单的办法。

1.  链接一个Github仓库。可以自己新建一个，也可以随便选择一个仓库，比如你站点的仓库

2.  在Github上安装 [utterances app](https://github.com/apps/utterances)。打开这个链接，点install，填上基本的信息就行，然后基本配置一下，底下还给你提供代码，比如我的

<!-- -->

    <script src="https://utteranc.es/client.js"
            repo="swcyo/Rblog"
            issue-term="pathname"
            label="评论"
            theme="github-light"
            crossorigin="anonymous"
            async>
    </script>

3.  然后把这段代码嵌入到footer.html里面就可以了

   在themes-hugo-prose-layouts-partials里，可以用RStudio可以编辑（Open in editor），直接把上面那个代码复制在最上面即可，然后就可以在每个页面下面看到评论插件安装好了
