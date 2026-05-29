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

      # ============ Slide 2: Mechanisms ============
      - title: Mechanisms of RNA Post-Transcriptional Homeostasis
        content: |
          Our laboratory is dedicated to understanding the fundamental mechanisms governing RNA post-transcriptional regulation and cellular homeostasis. We focus on the dynamic regulation of RNA processing, modification, degradation, and translation...
        align: left
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.35
          position: center
          color: '#1E3A66'
        link:
          icon: book-open
          icon_pack: fas
          text: Read More
          url: ../research/rna-homeostasis/

      # ============ Slide 3: Immunity ============
      - title: RNA Homeostasis and Immunity
        content: |
          We are particularly interested in the roles of RNA homeostasis in innate immunity and inflammatory responses, with an emphasis on host recognition and regulation of viral RNAs during infection. Our research focuses on interferon-stimulated genes (ISGs), RNA sensing pathways...
        align: right
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#3D4A6B'
        link:
          icon: book-open
          icon_pack: fas
          text: Read More
          url: ../research/rna-immunity/

      # ============ Slide 4: AI ============
      - title: AI-Driven RNA Synthetic Biology
        content: |
          Our laboratory is developing next-generation RNA synthetic biology platforms empowered by artificial intelligence (AI). By integrating large-scale computational modeling, structural prediction, high-throughput screening, and biological computing strategies...
        align: left
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#1E3A66'
        link:
          icon: book-open
          icon_pack: fas
          text: Read More
          url: ../research/ai-rna/

      # ============ Slide 5: Join Us (with CTA button) ============
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
