---
# Leave the homepage title empty to use the site title
title: ""
date: 2024-03-25
type: landing

sections:
  - block: features
    content:
      title: "<span style='font-size:70%'>Medical AI & Computational Science (Macs) Lab </span>"
      text: "<br><span style='font-size:125%'>전북대학교 의료 AI 및 계산 과학 연구실 홈페이지에 오신 것을 환영합니다.</span> <br><br>"
      cta: 
        cta_link: "./field/"
        cta_text: "See Research Field →"
      introduction: "👋 안녕하세요 저는 전북대학교 컴퓨터인공지능학부 21학번 이승준입니다. 👋 본 페이지는 포트폴리오 소개를 위해 제작된 홈페이지입니다! 전북대 이승준 - 본인의 전문성과 포트폴리오를 소개하는 페이지입니다."

  - block: slider
    content:
      slides:
        - title: "<span style='font-size:70%'>Recruit</span>"
          content: "<span style='font-size:70%'>Interested in MacsLAB?</span>"
          align: center
          background:
            image:
              filename: avatar.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'
          link:
            icon: user
            icon_pack: fas
            text: "<span style='font-size:60%'>Join Us</span>"
            text-color: '#000'
            url: contact

        - title: "<span style='font-size:70%'>AI</span>"
          content: "<span style='font-size:70%'>의료/항공우주/컨텐츠 등 특성화 분야에 적용 가능한 AI 기술 개발</span>"
          align: center
          background:
            image:
              filename: who.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'

        - title: "<span style='font-size:70%'>Healthcare</span>"
          content: "<span style='font-size:70%'>의료 및 헬스케어 분야에 적용 가능한 AI 기술 개발</span>"
          align: center
          background:
            image:
              filename: who.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'

        - title: "<span style='font-size:70%'>Mathematics</span>"
          content: "<span style='font-size:70%'>AI와 관련된 수학 및 최적화 이론 연구</span>"
          align: center
          background:
            image:
              filename: who.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'

        - title: "<span style='font-size:70%'>Development</span>"
          content: "<span style='font-size:70%'>기반 기술을 활용한 Full-Stack 어플리케이션 개발</span>"
          align: center
          background:
            image:
              filename: who.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'

    design:
      slide_height: '350px'
      slide_width: '100%'  # 수정: 슬라이드 너비를 100%로 변경
      is_fullscreen: false
      loop: true
      interval: 3000

---
