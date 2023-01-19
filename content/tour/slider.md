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
      content: Take a look at what we're working on...
      align: right
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: welcome.jpg
    - title: Polygenic risk scores in disease progression
      content: 'PhD student Julian Wanner giving a talk at the ASHG 2022 annual meeting'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: julian_ashg.png
    - title: Rare Epilepsy Genomics
      content: 'PhD student Andrea Eoli at the poster session of the Digital Health Center 5 year anniversary'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: andrea_poster.jpg
    - title: VisGen - Master student project
      content: 'building a web application to visualize genetic influences on disease risk from personal genomic data'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: coders.jpg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: ../contact/
---
