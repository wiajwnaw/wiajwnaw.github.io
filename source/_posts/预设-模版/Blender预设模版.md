---
title: Blender预设/模版
tags:
  - Blender
  - 预设
  - 美术向
categories:
  - - 预设/模版
  - - DCC
    - Blender
abbrlink: 85af305e
date: 2024-11-23 15:09:04
top_img: /tex/Blender.png
cover: /tex/Blender.png
---

---

**注意：**	

本章是我自己设计给自己使用的一套**饼菜单方案**，避免了记背快捷键和命令的问题，这套方案是以3ds Max快捷键习惯为基础设计的，也可以设置成Maya、C4D等其他软件。

---

Blender饼菜单插件：

正版：[Pie Menu Editor （12$）](https://roaoao.gumroad.com/l/pie_menu_editor)

龋齿一号：[Blender饼状菜单对话框工具栏插件 Pie Menu Editor V1.18.7 | 龋齿一号GFXCamp](https://www.gfxcamp.com/pie-menu-editor/)

BlenderM3工具插件（理论免费）：

官网：[Premium Game Assets - MACHIN3.io](https://machin3.io/)

下载：[[Addon\]MACHIN3tools](https://machin3.gumroad.com/l/MACHIN3tools)

![](https://www.gfxcamp.com/wp-content/uploads/2022/09/Pie-Menu-Editor.jpg)

# 一、键位设计

键位设计一般以左手设计为主，围绕着左右键位习惯进行设计。下面展示键位涉及到的内容。

![Snipaste_2024-11-24_19-35-30.png](https://www.helloimg.com/i/2024/11/24/67430e787fd98.png)

- 配置键5个

  **~；1；2；3；4；5**

- 占位符键1个

  **Tab**

- 换挡键3个（默认左侧L）

  **Shift；Ctrl；Alt**

- 空格键

  **Space**

- 按键组合

  **首选：**

  Alt + [**~；1；2；3；4**]

  **次选：**

  Ctrl + [**'~'；1；2；3；4**]

  **其其次选：**

  Shift + [**~；1；2；3；4**]

- 特别说明

  **推荐只使用单Alt或者单Ctrl的形式，更贴合左手手势。不推荐组合换挡键+配置键，手小的人不好驾驭。**

  因为Blender预设设计到层级管理，这边是层级窗口代码的链接：

  [插件百科-各类插件测评，帮你远离劣质插件](https://www.blendermagic.cn/#/article/ee79c207-3118-11eb-95ed-0242ac110004)（该代码可以做到Blender局部限制效果）

  

# 二、创建菜单集

- Alt + 1（或者Ctrl+1）

  主创建方式，对于模型基本体，曲线等基本对象的创建方式

- Alt + ~（或者Ctrl+~）

  副创建方式，对于声音，空物体，相机灯光等对象创建方式

- Alt+[2;3;4]（或者Ctrl+2；3；4）

  增量创建方式，主要对于Alt+1之后饼菜单栏不够的情况空出来的额外菜单空余。

- 特别说明

  包括但不限于，shader节点、几何节点、材质绘制面板等基本创建内容的使用，只需要调整层级面板即可

  例如：

  - 物体对象层级（只会对在于物体模式下的生效）
  - 点、线、面层级（只会出现于点、线、面层级下生效）
  - Node窗口层级（部分shader和Geometry节点会产生冲突，这边的节点窗口只能作用于node层级下）
  - 其他的同理，如（UV，材质绘制，后期剪辑等）

  

# 三、编辑对象菜单集（万能的空格键）

- 物体菜单空格
- 点菜单空格
- 线菜单空格
- 面菜单空格
- UV菜单空格
- ShaderNode菜单空格
- GeometryNode菜单空格
- VideoRender菜单空格
- 渲染空格

# 四、M3插件+特殊编辑菜单（供喜好自行配置）

