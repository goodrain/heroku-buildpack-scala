Heroku Buildpack for Scala [![Build Status](https://travis-ci.org/heroku/heroku-buildpack-scala.svg?branch=master)](https://travis-ci.org/heroku/heroku-buildpack-scala)
=========================

云帮 Scala 语言项目的源码构建核心部分是基于[Heroku buildpack for Scala](https://github.com/heroku/heroku-buildpack-scala) 来实现的。您可以部署基于[play](https://github.com/goodrain/heroku-buildpack-play)框架的web程序。

## 工作原理

当buildpack检测您的代码存在如下情况，您的应用会被识别为Scala语言：

- 根目录包存在`<文件名>.sbt`文件
- 根目录下的`/project`目录下存在`<文件名>.scala`文件
- 根目录下的`/.sbt`目录下存在`<文件名>.scala`文件

## 文档

以下文章了解更多：

- [云帮支持Scala](http://www.rainbond.com/docs/stable/user-lang-docs/scala/lang-scala-overview.html)
- [云帮支持play框架](http://www.rainbond.com/docs/stable/user-lang-docs/scala/lang-scala-play.html)

## 授权

根据 MIT 授权获得许可。 请参阅LICENSE文件


