---
title: 你好 CODING
---

欢迎使用 [CODING DevOps 静态网站](https://help.coding.net/docs/cd/static-website-v2.html) 部署 [Hexo](https://hexo.io/zh-cn/) 应用！
您可以到这里查看更多的 Hexo 的 [文档](https://hexo.io/zh-cn/docs/)。

这是你的第一篇文章。

## 快速开始

网站类型选择“Hexo”类型。

### 新建文章

``` bash
$ hexo new "My New Post"
```

相关帮助: [写作](https://hexo.io/zh-cn/docs/writing.html)

### 本地运行

``` bash
$ hexo server
```

相关帮助: [服务器](https://hexo.io/zh-cn/docs/server.html)

### 部署到线上

``` bash
$ git add . && git commit -m 'new post' && git push
```

## 进阶使用

网站类型选择“静态网站”类型，目录选择 public 目录。

### 本地编译

主要生成 public 目录，需要将该目录提交到 Git 仓库。

``` bash
$ npm install
$ hexo generate
```
