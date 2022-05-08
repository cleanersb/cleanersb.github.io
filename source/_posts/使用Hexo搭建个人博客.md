---
title: 使用Hexo搭建个人博客
date: 2022-04-22 17:48:29
tags:
- 技术
- Hexo
---

最近一直漫无目的的在网上浏览文章，决定自己搭建一个博客，苦于太穷，买不起服务器，Hexo+GitHub Page简直就是我这种穷孩子的福音。

开始吧！

#### 搭建框架
搭建框架主要分以下几步：
1、安装NodeJs——直接去官网下载即可
2、安装Hexo基础框架
```js
npm install -g hexo
```
3、初始化Hexo框架——在电脑任意位置创建一个目录，例如：myBlog，执行以下命令
```js
hexo init
```
4、安装所需要的组件——在Hexo项目的根目录下执行
```js
npm install
```
5、编译生成静态页面
```js
hexo g
```
6、启动本地服务
```js
hexo s
```
7、若推倒了github上，则使用下面的命令进行发布
```js
hexo d
```

完成以上步骤，如果显示如下：
```js
xxxxx http://localhost:4000/. Press Ctrl+C to stop
```
则说明本地建站成功，访问本地地址就可以看到了～

#### 更换主题
默认的主题确实比较丑！Hexo是支持更换主题的
可以在[Hexo的主题官网](https://hexo.io/themes)寻找想要的主题
每个主题都有对应的使用方法


