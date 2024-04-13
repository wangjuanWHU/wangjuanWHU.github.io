---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: markdown
    content:
      title:  
      subtitle: ''
      text: |
        # 实验室项目:

        ## 异构语言沙箱防护隔离系统
         - 基于开源编译框架LLVM的自动化库隔离沙箱系统，将第三方库从主程序中分离出来，利用Linux内核的namespace、seccomp和capability等机制，结合最小特权原则，对库的权限和资源进行限制。与已有的库隔离沙箱相比，本系统能够自动化实施库隔离，最大程度减少了人工开支。经过本系统隔离的程序，其性能损失不超过5%。
        
        ## 基于国产TPCM的工控云平台可信改造
         - 在OpenStack基础上实现定制化的云平台，基于TPCM进行简单的功能拓展；为工业SDN中的各类可信主机适配TPCM 软件栈，实现本地可信 Web 的代理功能，集成了开源的监控工具。
          为工控SDN网络中的网关、交换机、云服务器和Windows上位机进行可信改造，基于国产TPCM实现支持国密算法的可信软件栈。
  
        ## 基于智能渗透的风险隐患排査技术研究
         - 本课题研究电力行业关键信息资产指纹提取、漏洞扫描、智能漏洞挖掘及漏洞智能组合利用关键技术，形成一体化安全隐患排查方案，实现面向电力行业关键信息资产的智能化漏洞挖掘及利用，全面提升重大风险隐患识别能力。原型已在上海市电科院、湖北省电科院完成实战化电力网络安全攻防渗透工具原型的试点应用。

         ## 物联网国产自主可控安全关键技术研究
         - 提出了一种基于人工智能的物联网设备行为自动化建模和异常检测方法，基于深度神经网络自动提取物联网设备通信数据的隐藏特征，实现物联网设备行为的精准建模。提出了一种新的设备使用描述模型，该模型可以描述和构建包括通信和交互行为的物联网设备行为规范。



 

  # - block: contact
  #   content:
      # title: Contact
      # text: |-
      #   Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer tempus augue non tempor egestas. Proin nisl nunc, dignissim in accumsan dapibus, auctor ullamcorper neque. Quisque at elit felis. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Aenean eget elementum odio. Cras interdum eget risus sit amet aliquet. In volutpat, nisl ut fringilla dignissim, arcu nisl suscipit ante, at accumsan sapien nisl eu eros.
      # email: test@example.org
      # phone: 888 888 88 88
      # address:
        # street: 450 Serra Mall
        # city: Wuhan
        # region: CA
        # postcode: '94305'
        # country: China
        # country_code: CN
      # coordinates:
      #   latitude: '114.14'
      #   longitude: '30.67'
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      # autolink: true
    
      # Email form provider
    #   form:
    #     provider: netlify
    #     formspree:
    #       id:
    #     netlify:
    #       # Enable CAPTCHA challenge to reduce spam?
    #       captcha: false
    # design:
    #   columns: '1'

  # - block: markdown
  #   content:
  #     title:  
  #     subtitle: ''
  #     text: Email jwang@whu.edu.cn
    # design:
    #   columns: '1'
    #   background:
    #     image: 
    #       filename: contact.jpg
    #       filters:
    #         brightness: 1
    #       parallax: false
    #       position: center
    #       size: cover
    #       text_color_light: true
    #   spacing:
    #     padding: ['20px', '0', '20px', '0']
    #   css_class: fullscreen
---
