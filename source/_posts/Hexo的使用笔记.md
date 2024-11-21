---
title: Hexo的使用笔记
date: 2024-11-21 19:50:19
tags:
 - Hexo使用
 - 安知鱼主题
 - 博客技术笔记
categories:
 - Hexo
top_img: https://bu.dusays.com/2023/05/13/645fa3cf90d70.webp #文章顶部图片
cover: https://bu.dusays.com/2023/05/13/645fa3cf90d70.webp
---
# 一、安装一条龙（Git Hab + Vercel）

## 1、Hexo本地安装
- 需要会用一点cmd和windows PowerShell，鼠标选中指定文件右键打开终端（cmd/powerShell)
- 下方Hexo安装教程链接中，主题下载可以直接跳过，需要下主题可以直接跳到第三节。
- [Hexo安装（跟着输入就行）](https://sspai.com/post/62441)

## 2、SourceTree安装使用
- 不是唯一的方式，主要用于方便管理Git数据和上传。
- [官网下载（下载）](https://www.sourcetreeapp.com/)
- [Sourcetree安装详细（最新版本）](https://blog.csdn.net/zqd_java/article/details/123681302)
  
## 3、GitHub/GitLab/Gitee静态网页代理库准备
- 此步骤可以单独完成，和上文没有依赖关系
- GitHub
  （什么都好，就是国内访问有点小问题，下面有解决方案）
  [【利用github.io(githubPages)免费托管个人静态网站/个人博客】](ttps://blog.csdn.net/Amnesiac666/article/details/120428961)

- GitLab
  (该git平台在国内有中国有站点，访问快，部署后可以直接访问，就是目前比较小众)
  [【使用GitLab Pages托管静态网站】](https://blog.csdn.net/tongshuyang/article/details/125338130)
- Gitee
  （该平台目前下架了Gitee Pages，不能托管静态网站）
  
## 4、Vercel部署
- 该偏主要解决GitHub国内访问问题，选择其他git跳过此处
- Vercel+GitHub部署
  [【使用Vercel+Github搭建个人博客】](https://www.cnblogs.com/xuyiyang/p/13647069.html)

## 5、二级域名免费获取

- [【Freedns.Fun 永久免费二级域名 非盈利性网站】](https://freedns.fun/)

# 二、常用命令/方法
- 本地预览
  ```hexo s```
- 清除缓存
  ```hexo clean```
- npm依赖安装
  ```npm install```
- 文章创建
  ```hexo new name/hexo n name```
- 标签/分类创建和用法
- 本地获取图片/获取图片外链
  
# 三、开源好用的主题安装建议
- anzhiyu主题
- Solitude主题

# 四、各种主题配置心得
- anzhiyu主题
- Solitude主题