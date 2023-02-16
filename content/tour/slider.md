---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: 👋 Welcome to the group
      content: Take a look at our event...
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: 青年漫游.jpg
    - title: Free job posting services for Research positions
      content: 'Promoting Academic Exchanges and Collaboration, Supporting the Development of Biotech Personnel！'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: free-recrut.png
    - title: World-Class Semiconductor Lab
      content: 'Just opened last month!'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: welcome.jpg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: ../contact/
---
