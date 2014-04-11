---
layout: post
title: "Starting octpress"
date: 2014-04-11 15:05:16 +0800
comments: true
categories: [blog,ruby]
---

######以前一直使用wordpress来作为blog的平台，今天尝试用OctPress. 还在不断的适应当中。


##安装

###### 从git clone git://github.com/imathis/octopress.git octopress pull 代码，使用gem install bundler 安装bundler依赖包。再使用 bundle install 安装 otcpress 所依赖到的第三方包。 使用命令 rake install 安装默认的主题。 (注意： 由于电脑上有不同的rake 版本，所以使用 bundle exec rake install 代替)


##发布

###### 我把Octpress 发布到 github上。在github上创建一个名为ziqew.github.info 的 repo，执行 rake setup_github_pages，再执行 rake generate ， 最后执行 rake deploy， 这样就把OctPress 发布到github上了。 