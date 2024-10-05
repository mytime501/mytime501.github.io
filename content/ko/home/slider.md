---
# Leave the homepage title empty to use the site title
widget: slider
weight: 20
type: landing

content:
  slides:
  - title: WHO
    content: '미라클모닝 프로젝트'
    align: center
    background:
      image:
        url: /images/who.jpg  # 상대 경로로 수정
        filters:
          brightness: 0.5
      position: center
      color: '#333'

  - title: 랜덤 생성
    content: '무작위 키워드 및 문장 생성'
    align: center
    background:
      image:
        url: /images/who.jpg  # 상대 경로로 수정
        filters:
          brightness: 0.7
      position: right
      color: '#666'

  - title: 계산기
    content: '각종 계산을 위한 시스템'
    align: center
    background:
      image:
        url: images/who.jpg  # 상대 경로로 수정
        filters:
          brightness: 0.7
      position: center
      color: '#555'

  - title: 날씨 측정
    content: '지역별 기온과 날씨를 측정'
    align: center
    background:
      image:
        url: images/who.jpg  # 상대 경로로 수정
        filters:
          brightness: 0.5
      position: center
      color: '#333'

  - title: 에누링
    content: '중고거래를 위한 플랫폼'
    align: center
    background:
      image:
        url: images/who.jpg  # 상대 경로로 수정
        filters:
          brightness: 0.7
      position: right
      color: '#666'

  - title: POPDOG
    content: '밈을 이용한 게임'
    align: center
    background:
      image:
        url: who.jpg  # 상대 경로로 수정
        filters:
          brightness: 0.7
      position: center
      color: '#555'

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '350px'
  slide_width: '100%'  # 슬라이드 너비를 100%로 수정
  is_fullscreen: false
  # Automatically transition through slides?
  loop: true
  # Duration of transition between slides (in ms)
  interval: 3000
---
