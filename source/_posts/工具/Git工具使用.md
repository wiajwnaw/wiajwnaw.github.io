---
title: Git命令行工具使用
tags:
  - Git小乌龟
  - Sourcetree
  - 命令行
top_img: 'https://www.helloimg.com/i/2024/11/22/67400c7f035c2.jpg'
cover: 'https://www.helloimg.com/i/2024/11/22/67400c7f035c2.jpg'
abbrlink: f8ae98be
date: 2024-11-24 17:25:31
categories:
---

# 命令行方法

- 常用命令

  - 初始化Git仓库

    ```shell
    git init
    ```

  - Clone到本地

    需要在clone后面加上URL+本地git库

    示例：git clone <url> [directory]

    示例：git clone git://github.com/schacon/grit.git  newgit（本地文件夹）

    直接在当前文件夹使用端口打开输入拉取即可

    ```shell
    git clone
    ```

    

  - git clone支持不同的协议

    ```shell
    git clone git@github.com/schacon/grit.git         --SSH协议
    git clone git://github.com/schacon/grit.git          --GIT协议
    git clone https://github.com/schacon/grit.git      --HTTPS协议
    ```

    

  - 上传到本地（添加问价到缓存）

    - 尚未缓存的改动：**git diff**
    - 查看已缓存的改动： **git diff --cached**
    - 查看已缓存的与未缓存的所有改动：**git diff HEAD**
    - 显示摘要而非整个 diff：**git diff --stat**

    示例：git add <文件名>

    ```shell
    git add
    ```

    

  - 推送到远端Git库（提交命令）

    示例：git commit -m "第一次版本提交"

    ```shell
    git commit -m ""
    ```

  - 删除命令

    ```shell
    git rm
    ```

    

- 基础命令

  - 制定目录下生成Git仓库

    ```shell
    git init newDir
    ```

    

  - 配置信息

    ```shell
    git config
    ```

  

  - 查看文件的状态命令

    ```shell
    git status
    ```

    

  - 查看更新的详细信息命令

    ```shell
    git diff
    ```

    

  - 取消缓存命令

    ```shell
    git reset HEAD
    ```

    

  - 移动或重命名命令

    ```shell
    git mv
    ```

    

