---
layouy:  post
title:  「GitHub Pages」 搭建属于你的个人博客
image:
date:   2021-02-19 15:18:30
tags: 	[DOCS]
---

> 使用Github Pages搭建个人博客，一劳永逸，可以让我们更加专注于博客的撰写

<!--more-->

# 前言

本教程使用[GitHub Pages](https://pages.github.com/) + [Jekyll](https://www.jekyll.com.cn/) 进行搭建

另还有[GitHub Pages](https://pages.github.com/) + [Hexo](https://hexo.io/zh-cn/) 的方式搭建个人博客，小伙伴们可以另行搜索

![image-20210219194423456](https://gitee.com/tong9910/image/raw/master/img/image-20210219194423456.png)

---

# 搭建博客

## 注册GitHub账号

要使用 GitHub Pages，首先需注册一个[GitHub](https://github.com/)账号，GitHub 是全球最大的同性交友网站(手动狗头)，你值得拥有。

![image-20210219194501599](https://gitee.com/tong9910/image/raw/master/img/image-20210219194501599.png)

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

为什么使用桌面版呢，因为简单，适合小白，没那么多命令行(官网可能下载较慢，文末附软件下载链接)

---

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

+ 寻找喜欢的博客模版，推荐一个[Jekyll博客主题网站](http://jekyllthemes.org/)，将模板下载解压之后，将文件全部复制到仓库本地文件夹中

  <img src="https://gitee.com/tong9910/image/raw/master/img/image-20210219185043324.png" alt="image-20210219185043324" style="zoom:50%;" />

---

+ 接下来打开GitHub桌面版，会发现出现许多`Changes`，在`Summary`随意输入一些内容，点击`Commit to main`进行push

  <img src="https://gitee.com/tong9910/image/raw/master/img/image-20210219185506385.png" alt="image-20210219185506385" style="zoom: 67%;" />

---

+ 接下来点击 **如图所示区域** 便可进行远程部署(可能会有某些网络问题导致上传失败，多尝试几次即可)

  <img src="https://gitee.com/tong9910/image/raw/master/img/image-20210219185810518.png" alt="image-20210219185810518" style="zoom:67%;" />

---

+ 回到GitHub主页上，也会发现该仓库更新了许多文件

  <img src="https://gitee.com/tong9910/image/raw/master/img/image-20210219190132732.png" alt="image-20210219190132732" style="zoom:50%;" />

---

# 博客优化

## 网站优化

在仓库本地文件夹中找到`_config.yml`文件，根据自己需求进行修改

<img src="https://gitee.com/tong9910/image/raw/master/img/image-20210219190611867.png" alt="image-20210219190611867" style="zoom:50%;" />

---

## 内容输出

发表博客时，需将文章保存在`_post`文件夹中，文章格式为`.md`文件，关于在撰写文章时的语法规则，可参考我之前的博客[Markdown基础语法入门](https://seasontong.github.io//Markdown/)

![image-20210219191010934](https://gitee.com/tong9910/image/raw/master/img/image-20210219191010934.png)

---

# 后言

到这里就结束了，没有涉及到命令行等其他复杂的知识，以下是搭建过程中需要的软件与网站,希望通过我的分享，大家都可以搭建好属于自己的网站

+ [GitHub桌面版](https://tih.lanzous.com/ilidzluxexg)
+ [Jekyll主题网站](http://jekyllthemes.org/)
+ [Markdown基础语法入门](https://seasontong.github.io//Markdown/)