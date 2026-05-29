---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        李思思
        课题组
      image:
        filename: welcome.jpg
      text: |
        <br>

        **李思思课题组**（深圳大学）专注于 RNA 稳态免疫研究。我们整合人工智能与结构生物学方法，致力于功能性 RNA 的工程化设计，并开发广谱抗病毒策略。
  
  - block: collection
    content:
      title: 最新动态
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text: |
        <h2 style="color:white; text-align:center;">
          解码 RNA 免疫。
        </h2>
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['80px', '0', '80px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: 最新发表
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: ''
    design:
      view: citation
      columns: '1'

  - block: collection
    content:
      title: 近期活动
      subtitle: ""
      text: ""
      count: 3
      filters:
        folders:
          - event
        exclude_featured: false
      offset: 0
      order: desc
      page_type: event
    design:
      view: compact
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="了解团队成员 →" %}}
    design:
      columns: '1'
---
