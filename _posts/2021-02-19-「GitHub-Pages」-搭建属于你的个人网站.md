---
layouy:  post
title:  「GitHub Pages」 搭建属于你的个人博客
image:
date:   2021-02-19 15:18:30
tags: 	
categories: 
---

> 使用Github Pages搭建个人博客，一劳永逸，可以让我们更加专注于博客的撰写

# 前言

本教程使用[GitHub Pages](https://pages.github.com/) + [Jekyll](https://www.jekyll.com.cn/) 进行搭建

另还有[GitHub Pages](https://pages.github.com/) + [hexo](https://hexo.io/zh-cn/) 的方式搭建个人博客，小伙伴们可以另行搜索

<img src="https://gitee.com/tong9910/image/raw/master/img/blog" style="zoom: 50%;" />

---

# 搭建博客

## 注册GitHub账号

要使用 GitHub Pages，首先需注册一个[GitHub](https://github.com/)账号，GitHub 是全球最大的同性交友网站(狗头)，你值得拥有。

<img src="https://gitee.com/tong9910/image/raw/master/img/github" style="zoom: 50%;" />

---

## 搭建博客

### 新建仓库

<img src="https://gitee.com/tong9910/image/raw/master/img/image-20210219180138583.png" alt="image-20210219180138583" style="zoom: 50%;" />

---

### 仓库命名

<img src="https://gitee.com/tong9910/image/raw/master/img/image-20210219180938833.png" alt="image-20210219180938833" style="zoom:50%;" />

+ **以 `username.github.io` 作为仓库名字（需严格遵守）**，比如我的username为seasontong，那么我的仓库名为seasongtong.github.io
+ 仓库设置为public（公开）
+ 勾选 `Add a README file`选项
+ 完成以上三步便可创建仓库

---

### 选择主题

+ 创建仓库完成后，进入`Settings`

  <img src="https://gitee.com/tong9910/image/raw/master/img/image-20210219181659386.png" alt="image-20210219181659386" style="zoom:50%;" />

---

+ 进入后一直向下滑动，找到`Choose a theme`以选择主题

  ![image-20210219182000503](https://gitee.com/tong9910/image/raw/master/img/image-20210219182000503.png)
  
  ---

+ 选择好喜欢的主题后，记得`Select theme`保存主题

  ![image-20210219183302500](https://gitee.com/tong9910/image/raw/master/img/image-20210219183302500.png)

---

+ 到这里你便可以通过`username.github.io`来查看你的网站了

  <img src="https://gitee.com/tong9910/image/raw/master/img/image-20210219183419755.png" alt="image-20210219183419755" style="zoom: 50%;" />

---

## 远程部署

### 下载[GitHub 桌面版](https://desktop.github.com/)

为什么使用桌面版呢，因为简单，适合小白，没那么多命令行(文末附软件下载链接)

### Desktop登录

+ 账号登录后点击`File` ->`Clone repository`

![image-20210219184305949](https://gitee.com/tong9910/image/raw/master/img/image-20210219184305949.png)

---

+ 将仓库 clone 到本地，**记住仓库存放到本地的位置**

  <img src="https://gitee.com/tong9910/image/raw/master/img/image-20210219184437097.png" alt="image-20210219184437097" style="zoom:50%;" />

---

+ 前往仓库本地文件夹，除了`.git`文件夹，其他全部**删除**

  <img src="https://gitee.com/tong9910/image/raw/master/img/image-20210219184705430.png" alt="image-20210219184705430" style="zoom:50%;" />

---

+ 寻找喜欢的博客模版，推荐一个[Jekyll博客主题网站](http://jekyllthemes.org/)，将模板下载下来之后，将文件全部复制到仓库本地文件夹当中

  <img src="https://gitee.com/tong9910/image/raw/master/img/image-20210219185043324.png" alt="image-20210219185043324" style="zoom:50%;" />

---

+ 接下来打开GitHub桌面版，会发现出现许多`Changes`，在`Summary`随意输入一些内容，点击`Commit to main`便可远程部署

  <img src="https://gitee.com/tong9910/image/raw/master/img/image-20210219185506385.png" alt="image-20210219185506385" style="zoom: 67%;" />

