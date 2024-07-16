---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
     title:
     subtitle: ''
    design:
      columns: '1'
      background:
        image: 
          filename: 2.jpg
          # parallax: false
          position: top
          size: 84%
          # text_color_light: true
      spacing:
        padding: ['40px', '0', '40px', '0']
  #     css_class: fullscreen
  - block: hero
    content:
      <!-- title: |
        <span style="font-family: Arial; font-size: 38px;"><span style="color: rgb(175, 22, 22); font-size: 45px;">T</span>rusted <span style="color: rgb(175, 22, 22); font-size: 45px;">C</span>omputing & <span style="color: rgb(175, 22, 22); font-size: 45px;">S</span>ecurity Lab</span> -->
      image: 
        filename: a402_1.jpg

      text: |
        <div style="display: flex; align-items: center; margin-top: -45px; margin-bottom: 15px;">  <!-- 调整 margin-top 为负值减小间距 -->
          <img src="./whu.png" alt="whu logo" style="width: 12%; height: auto; margin-right: 10px;">
          <img src="./cyber.png" alt="cyber logo" style="width: 57%; height: auto;">
        </div>
        <span style="font-family: Arial; font-size: 38px; line-height: 0.15; margin-bottom: 13px;"><span style="color: rgb(175, 22, 22); font-size: 45px;">T</span>rusted <span style="color: rgb(175, 22, 22); font-size: 45px;">C</span>omputing & <span style="color: rgb(175, 22, 22); font-size: 45px;">S</span>ecurity Lab</span>
        <div style="text-align: center;">
          <span style="font-family: Arial; font-size: 34px; line-height: 0.15; margin-bottom: 13px;">
              <span style="color: rgb(175, 22, 22); font-size: 34px;">可信计算</span>与<span style="color: rgb(175, 22, 22); font-size: 34px;">安全</span>实验室
          </span>
        </div>
      
        <p style="text-align: left; float: left; line-height: 0.69; margin-top: 7px;">
        <span style=" font-size: 16px;">
        <span style="font-style: italic; font-weight: bold; font-size: 1.3em;">
        System Security<br>
        </span>
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  We are committed to the research of trusted computing represented by <span style="color: rgb(175, 22, 22); font-size: 16px;"><strong>TPM</strong></span> aiming to build secure and reliable trusted systems. We aim to provide secure foundations for <u>cloud security, big data, blockchain, SDN</u>, and other technologies. In recent years, building on the foundation of trusted computing research, we have expanded our scope to <span style="color: rgb(175, 22, 22); font-size: 16px;"><strong>Confidential Computing</strong></span> and are dedicated to research in the design and application of trusted execution environment architectures. 
        <br>
        <br>
        <span style="font-style: italic; font-weight: bold; font-size: 1.3em;">
        AI Security<br>
        </span>
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  We are focused on exploring and developing efficient solutions to address critical issues surrounding <span style="color: rgb(175, 22, 22); font-size: 16px;"><strong>Privacy</strong></span>. We particularly emphasize the formulation of flexible and robust <u>attack/defense strategies</u> throughout the entire lifecycle of deep learning models, including data collection, model training/inference, and deployment. Additionally, we actively integrate AI technologies with <span style="color: rgb(175, 22, 22); font-size: 16px;"><strong>Traditional Security Domains</strong></span> such as confidential computing, binary analysis, and vulnerability discovery, aiming to contribute to a wider range of security.
        </span>
        </p>

  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text: 
      count: 20
      #filters:
      #  author: ''
      #  category: ''
      #  exclude_featured: false
      #  publication_type: ''
      #  tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '1'
---
