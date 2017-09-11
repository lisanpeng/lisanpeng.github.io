---
title:  "欢迎来到我的github page"
categories: [github blog]
tags: [github pages]
---
折腾了两天，一切从零开始，总算有一个像样的主页了。

```环境：Ubuntu 16.04```

从安装*git*，熟悉*git命令*开始，再到上传到*github*，总的来说比较简单。可参考cnblogs上的 [git/github学习笔记](http://www.cnblogs.com/fnng/archive/2011/08/25/2153807.html)。

了解了下 [GitHub Pages](https://pages.github.com)，默认提供的几个主题过于简单，不喜欢。挑选了喜欢的*jekyll* 主题 [jekyll-uno](https://github.com/joshgerdes/jekyll-uno)。简略看了下*jekyll*语法，修改了*_config.yml*，自己的博客页面就出来了。有一点要注意的是，如果是你想创建的是用户页面，你需要新建一个名字为 *yourusername.github.io* 的 *repository*。

想着以后自己要修改主题，便在本地搭建了*jekyll* 环境。这里面会有坑。安装*bundler*，依赖于*ruby*和*rubygems*。由于国内网络原因（你懂的），导致rubygems.orgs间歇性连接失败或连接很慢，所以遇到了`bundle install`没有响应的情况。后来试过 [taobao](https://ruby.taobao.org) 的RubyGems镜像，还行。

最后简单看了下*markdown*，使用*atom* (*atom* 的 *markdown preview* 相当好用) 写了第一篇博文。
