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
    - title: Welcome to the group
      content: Take a look at what we're working on...
      align: right
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: welcome.jpg
    - title: Polygenic risk scores in disease prognosis
      content: 'Lead: PhD student Julian Wanner, in close collaboration with the INTERVENE project (funding: Horizon 2020)'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: julian_dhcparty.jpg
    - title: Rare Epilepsy Genomics
      content: 'Lead: PhD student Andrea Eoli (here: at the poster session of the Digital Health Center 5 year anniversary)'
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
    - title: We are located 
      content: 'at the Digital Health Center of the Hasso Plattner Institute in Potsdam (Germany)'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: dhc.jpeg
    - title: We are working with a network of (inter-)national collaborators
      content: 'such as FIMM, the FinnGen study, the INTERVENE project (in picture), the Hasso Plattner Institute at Mount Sinai (NY), the University of Leipzig etc.'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: intervene_pic.jpg
    - title: Get in contact!
      content: ''
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: join_us.jpg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Contact
        url: ../contact/
---
