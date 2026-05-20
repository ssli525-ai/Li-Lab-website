---
title: Tour
date: 2022-10-24
type: landing
sections:
  - block: slider
    content:
      slides:

      # ============ Slide 1: Welcome ============
      - title: Welcome to the Li Laboratory
        content: 'Structural biology of RNA–protein recognition at Shenzhen University.'
        align: center
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.45
          position: center
          color: '#0B2545'

      # ============ Slide 2: Research Focus ============
      - title: How Proteins Read the Language of RNA
        content: |
          We combine cryo-EM, biochemistry, and cellular assays to dissect how
          RNA-binding proteins recognize specific transcripts and shape gene expression.
        align: left
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.35
          position: center
          color: '#1E3A66'

      # ============ Slide 3: Lab Culture ============
      - title: A Collaborative Scientific Community
        content: |
          We value curiosity, rigor, and mentorship — bringing together students,
          postdocs, and visiting scholars from biology, chemistry, and computation.
        align: right
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#3D4A6B'

      # ============ Slide 4: Join Us (with CTA button) ============
      - title: Join the Lab
        content: |
          We welcome motivated graduate students, postdoctoral fellows, and undergraduates
          interested in RNA biology and structural mechanism.
        align: center
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#0B2545'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Contact Us
          url: ../contact/

    design:
      slide_height: ''
      is_fullscreen: true
      loop: false           # true 会自动循环播放
      interval: 5000        # 切换间隔，5000 毫秒 = 5 秒，比模板默认 2 秒慢一些更适合阅读
---
