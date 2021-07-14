---
title: 如何搭建Hexo个人博客
date: 2021-04-08 15:14:00
tags:
- Hexo
- Redis
- Java基础
categories:
- Hexo
- Redis
- Java基础
---

# Hexo介绍



# Hexo搭建



## 安装Hexo

``` 
npm install -g hexo-cli 
```



### 新建Blog文件夹

``` 
hexo init Blog
cd Blog
npm install
```



### Hexo基础操作

``` 
# 生成
hexo generate 或 hexo g
# 本地启动服务
hexo server 或 hexo s
# 发布到Github
hexo deploy 或 hexo d
```



## 配置Github

```yml
deploy:
  type: git
  repository: git@github.com:***/***.github.io.git
  branch: main
```



## 安装deployer-git

```
npm install hexo-deployer-git --save
```

