---
# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing

sections:

  - block: features
    content:
      title: <span style="font-size:70%">Medical AI & Computational Science (Macs) Lab </span>
      text: <br><span style="font-size:125%">전북대학교 의료 AI 및 계산 과학 연구실 홈페이지에 오신 것을 환영합니다.</span> <br><br>
        {{% cta cta_link="./field/" cta_text="See Research Field →" %}}

        👋 안녕하세요 저는 전북대학교 컴퓨터인공지능학부 21학번 이승준입니다. 👋

        
        본 페이지는 포트폴리오 소개를 위해 제작된 홈페이지입니다!
        전북대 이승준 - 본인의 전문성과 포트폴리오를 소개하는 페이지입니다.
        {style="font-size: 1.1rem; background: #FFB76B; background: linear-gradient(to right, #FFB76B 0%, #FFA73D 30%, #FF7C00 60%, #FF7F04 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent;"}

  - block: slider
    content:
      slides:

      - title: <span style="font-size:70%">Recruit</span>
        content: <span style="font-size:70%">Interested in MacsLAB?</span>
        align: center
        background:
          image:
            filename: who.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: user
          icon_pack: fas
          text: <span style="font-size:60%">Join Us</span>
          text-color: '#000'
          url: contact

      - title: <span style="font-size:70%">AI</span>
        content: <span style="font-size:70%">의료/항공우주/컨텐츠 등 특성화 분야에 적용 가능한 AI 기술 개발<span style="font-size:70%">
        align: center
        background:
          image:
            filename: who.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Healthcare</span>
        content: <span style="font-size:70%">의료 및 헬스케어 분야에 적용 가능한 AI 기술 개발</span>
        align: center
        background:
          image:
            filename: who.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Mathematics</span>
        content: <span style="font-size:70%">AI와 관련된 수학 및 최적화 이론 연구</span>
        align: center
        background:
          image:
            filename: who.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Development</span>
        content: <span style="font-size:70%">기반 기술을 활용한 Full-Stack 어플리케이션 개발</span>
        align: center
        background:
          image:
            filename: who.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      slide_width: '100px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000

  - block: portfolio
    content:
    # Page type to display. E.g. project.
    page_type: project

    # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
    filter_default: 0

    # Filter toolbar (optional).
    # Add or remove as many filters (`filter_button` instances) as you like.
    # To show all items, set `tag` to "*".
    # To filter by a specific tag, set `tag` to an existing tag name.
    # To remove the toolbar, delete the entire `filter_button` block.
    filter_button:
        - name: All
          tag: '*'
        - name: Web
          tag: Web
        - name: CShape
          tag: CShape
        - name: Unity
          tag: Unity

    design:
    columns: '1'
    view: masonry
    flip_alt_rows: true
    background: {}
    spacing: {padding: [40, 0, 0, 0]}
---

