---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing
sections:
  - block: hero
    content:
      title: |
        Sisi Li
        Research Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        The **Sisi Li Research Group** at Shenzhen University focuses on RNA homeostasis immunity. We integrate AI and structural biology to engineer functional RNAs and develop broad-spectrum antiviral strategies.

  - block: collection
    content:
      title: Latest News
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
        <h2 style="color:white; text-align:center; font-weight:bold; font-size:36px;">
          Decoding RNA immunity
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
        padding: ['300px', '0', '300px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Recent Publications
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
      title: Recent Events
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
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---