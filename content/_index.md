---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing
sections:
  - block: hero
    content:
      title: |
        SIM Lab
      text: |
        Semiconductor Integration Materials Laboratory, Hanyang University

        The SIM Lab at Hanyang University focuses on materials innovation to enable next-generation semiconductor integration technologies, ranging from novel 2D materials to monolithic 3D architectures.
      image:
        filename: Lab main.png
        filters:
          brightness: 0.55
      cta:
        url: ./people/
        label: Meet the Team
    design:
      is_fullscreen: true
      background:
        color: 'black'
        text_color_light: true

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
    
  - block: collection
    content:
      title: Selected Publications
      text: ""
      count: 12
      filters:
        folders:
          - publication
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: 'Selected'
    design:
      view: card
      columns: '3'
    
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image:
          filename: coders.png
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
