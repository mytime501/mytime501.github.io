---
# Leave the homepage title empty to use the site title
widget: slider
weight: 20
type: landing

content:
  slides:
  - title: WHO
    content: 'Miracle Morning Project'
    align: center
    background:
      image:
        url: who.jpg  # 상대 경로로 수정
        filters:
          brightness: 0.5
          opacity: 0.5
      position: center
      color: '#333'

  - title: Random Generation
    content: 'Generating random keywords and sentences'
    align: center
    background:
      image:
        url: keywords.jpg  # 상대 경로로 수정
        filters:
          brightness: 0.7
          opacity: 0.5
      position: right
      color: '#666'

  - title: Calculator
    content: 'A system for various calculations'
    align: center
    background:
      image:
        url: calulator.jpg  # 상대 경로로 수정
        filters:
          brightness: 0.7
          opacity: 0.5
      position: center
      color: '#555'

  - title: Weather measurement
    content: 'Measurement of temperature and weather by region'
    align: center
    background:
      image:
        url: weather.jpg  # 상대 경로로 수정
        filters:
          brightness: 0.5
          opacity: 0.5
      position: center
      color: '#333'

  - title: Enuring
    content: 'A platform for secondhand transactions'
    align: center
    background:
      image:
        url: enuring.jpg  # 상대 경로로 수정
        filters:
          brightness: 0.7
          opacity: 0.5
      position: right
      color: '#666'

  - title: POPDOG
    content: 'A meme-based game'
    align: center
    background:
      image:
        url: dog.jpg  # 상대 경로로 수정
        filters:
          brightness: 0.7
          opacity: 0.5
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
