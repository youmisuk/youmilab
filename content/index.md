---
# Leave the homepage title empty to use the site title
title: 
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Youmi
        Research Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **Youmi Research Group** has been a center of excellence for Causal Machine Learning and Optimal Treatment Regimes research, teaching, and practice since its founding in 2022.
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      # <a href="https://www.freepik.com/free-ai-image/glowing-blue-wave-pattern-ignites-futuristic-technology-generated-by-ai_41327962.htm#fromView=search&page=1&position=50&uuid=8359d31e-6bdd-4d74-8266-7c363ea63294">Image by vecstock on Freepik</a>  #for image AI1, power by author

      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
---