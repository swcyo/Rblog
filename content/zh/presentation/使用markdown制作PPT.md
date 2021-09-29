---
categories:
- null
date: "2019-10-30T20:48:10+09:00"
description: 使用zoo主题制作PPT
highlightTheme: monokai
plugins:
- highlight
- zoom
- notes
- math
reveal:
- main:
  - sub:
    - |
      # Markdown
      ## 使用zoo主题制作PPT
  - sub:
    - |
      - **Markdown**是一个轻量级的语言，起初主要用于网络写作，之后慢慢发展到更多的领域，比如写书、记笔记、写文档、写幻灯片等。
      - 然而，由于**Markdown**本身功能有限，一些特定的需求和场景无法被完全满足，因此产生了许多衍生语法，在这些语法的基础上新增了表格、任务列表、围栏代码等功能。
      - 当然**Markdown**直接是不能写PPT的，我们需要一些专门的工具去渲染，本文用的就是**reveal.js**。
- main:
  - sub:
    - |
      ## Mrrkdown写幻灯片的开源工具
      - nodeppt
      - shower
      - remark
      - inpress.js
      - **reveal.js**
- main:
  - sub:
    - |
      # Reveal.js
      ### **reveal.js**是一个使用HTML和Markdown快速创建和演示幻灯片的工具
      ### 主要功能如下：
  - sub:
    - |
      1. 创建水平和垂直幻灯片，支持幻灯片链接
      2. 可使用Markdown和HTML编写内容，也支持引用独立的Markdown文件
      3. 可使用颜色、图片、视频和网页作为背景
      4. 可添加演讲者注释、支持一键打开
      5. 可配置幻灯片的主题和过渡工会，有多种方案可供选择
      6. 可在手机或平板电脑打开和演示幻灯片
      7. 可打印和到处PDF格式的问答
      8. 可以安装实用的插件来增强幻灯片的功能和演示效果
      9. 自由度大，自自由定妆
      10. 支持快捷键使用，操作方便
- main:
  - sub:
    - |
      ## **zzo**主题自带支持幻灯特效 
      - 无需安装**reveal.js**
      - 支持Markdown语句和HTML语句
      - 支持垂直和水平幻灯片，比**Power Point**更强大
- main:
  - sub:
    - |
      ## reveal.js的主题样式
      - 共有11种主题，具体见垂直幻灯
      - 在`revealTheme:`中输入主题样式
  - sub:
    - |
      1. black
      2. white
      3. league
      4. sky
      5. beige（HUGO默认）
      6. simple
      7. serif
      8. blood
      9. night
      10. moon
      11. solarized
- main:
  - sub:
    - |
      ## 如何添加新的一页幻灯
      ```
      - main:
        - sub:
          - |
          ## 如何添加新的一页幻灯
        - sub:
          - |
           垂直幻灯就再写一句 -sub：
      
      ```
  - sub:
    - |
       垂直幻灯就再写一句 -sub：
- fragment:
  - sub:
    - |
      ## 如何添加幻灯中的片段效果
  - sub:
    - |
      #### 点垂直和水平都可以
  - sub:
    - |
      #### 点击一下出现一段文字
  - sub:
    - |
      #### 点击一下出现另一段文字
  - sub:
    - |
      #### 运用的是
      ```
       - fragment:
         - sub:
           - |
            ## 如何添加幻灯中的片段效果
         - sub:
           - |
           #### 点垂直和水平都可以
         - sub:
           - |
           #### 点击一下出现一段文字
         - sub:
           - |
          #### 点击一下出现另一段文字
      ```

revealBackgroundColor: ""
revealBackgroundImage: ""
revealBackgroundOpacity: ""
revealBackgroundPosition: ""
revealBackgroundRepeat: ""
revealBackgroundSize: ""
revealBackgroundVideo: ""
revealBackgroundVideoLoop: false
revealBackgroundVideoMuted: false
revealTheme: blood
series:
- null
tags:
- null
title: 使用markdown制作PPT
---
