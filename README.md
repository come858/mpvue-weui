# [mpvue-weui](https://kuangpf.github.io/mpvue-weui/#/)

> 用 vue 写小程序，使用 mpvue 框架重写 WeUI。

![GitHub package version](https://img.shields.io/github/package-json/v/KuangPF/mpvue-weui.svg) ![node](https://img.shields.io/node/v/passport.svg) ![GitHub commit activity the past week, 4 weeks, year](https://img.shields.io/github/commit-activity/y/KuangPF/mpvue-weui.svg) ![GitHub last commit](https://img.shields.io/github/last-commit/KuangPF/mpvue-weui.svg) ![GitHub rep size](https://img.shields.io/github/languages/code-size/KuangPF/mpvue-weui.svg)

### 前言

今天早上打开电脑，像往常一样浏览一下 `github`，看到了一个很不错的框架，没错，就是 [mpvue](https://github.com/Meituan-Dianping/mpvue)。它是基于 `Vue.js` 的小程序开发框架，从底层支持 `Vue.js` 语法和构建工具体系。what，小程序可以用 `vue`写了？简直有点不太敢确定，花了[5分钟](http://mpvue.com/mpvue/quickstart/)看了一下简介，没错，真的可以用`vue`开发小程序。真的是**限制了我的想象力，明白又该学写了，于是就开始准备利用这个框架写一点项目，感受一下他的魅力(其实是踩坑)。


### 踩坑文档

[记录了踩的一些坑和一些组件在 `mpvue` 框架中的用法](https://kuangpf.github.io/mpvue-weui/#/)

tip: 文档还在完善中....

### WeUI

由于是小程序，所以首先想到了实现一下小程序的一些组件，包括 button、loading、picker 等等。总的效果就像[weui](https://weui.io/)，或者说用 vue 重写[weui](https://weui.io/)。

### 开发预览

``` bash
1. git clone
git clone https://github.com/KuangPF/wxapp-vue.git

2. 安装依赖
npm install (cnpm install)

3. 启动程序
npm run dev

4. 预览
打开微信开发者工具，新建项目，将目录指向 /dist 即可

```
### 效果

![mpvue-weui-demo01](https://github.com/KuangPF/mpvue-weui/blob/master/static/demo/mpvue-weui-demo01.png)
![mpvue-weui-demo02](https://github.com/KuangPF/mpvue-weui/blob/master/static/demo/mpvue-weui-demo02.png)
![mpvue-weui-demo03](https://github.com/KuangPF/mpvue-weui/blob/master/static/demo/mpvue-weui-demo03.png)
![mpvue-weui-demo01](https://github.com/KuangPF/mpvue-weui/blob/master/static/demo/mpvue-weui-demo04.png)

### 重写状态

#### 表单
- [x] Button
- [x] Input
- [x] List
- [x] Slider
- [x] Uploader

#### 基础组件
- [x] Article
- [x] Badge
- [x] Flex
- [x] Footer
- [x] Gallery
- [x] Grid
- [x] Icons
- [x] Loadmore
- [x] Panel
- [x] Preview
- [x] Progress

#### 操作反馈
- [x] Actionsheet
- [x] Dialog
- [x] Msg
- [x] Picker
- [x] Toast

#### 导航相关
- [x] Navbar
- [x] Tabbar

#### 搜索相关
- [x] Searchbar


### 踩坑文档编写中...
