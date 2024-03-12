---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: Contact
    content:
      title: Contact
      text: |-
             What we know is a drop, what we don't know is an ocean.
             May the road rise up to meet you, may the wind be ever at your back. May the sun shine warm upon your face and the rain fall softly on your fields.


      email: ysuk@tc.columbia.edu
      phone: 212-678-4030
      address:
        street: 525west 120st
        city: New York
        region: NY
        postcode: '10027'
        country: United States
        country_code: US
      coordinates:
        latitude: '40.810053'
        longitude: '-73.959424'
      directions: Enter Grace Dorge Hall Building and take the stairs to Office 552 GDodge on Floor 5
      
      
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
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
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
