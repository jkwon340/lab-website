---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing
design:
  css_class: home
sections:
  - block: hero
    content:
      slides:
        - eyebrow: Kwon Group at Hanyang University
          title: |
            Semiconductor Integration<br>Materials Laboratory
          lead: |
            Materials innovation for next-generation semiconductor integration — from novel 2D materials to monolithic 3D architectures.
          accent: emerald
          cta_label: Meet the Team
          cta_url: ./people/
          cta_alt_label: Explore Research
          cta_alt_url: ./research/
        - eyebrow: Research Pillar 01
          title: |
            Future Logic<br>Devices
          lead: |
            Wafer-scale 2D GAAFETs and monolithically stacked CFETs, pushing logic scaling beyond the limits of silicon.
          accent: cyan
          cta_label: Explore Research
          cta_url: ./research/
        - eyebrow: Research Pillar 02
          title: |
            Future Memory<br>Devices
          lead: |
            Ferroelectric FeFETs and oxide memory cells, grown directly on top of logic for dense, low-power storage.
          accent: violet
          cta_label: Explore Research
          cta_url: ./research/
        - eyebrow: Research Pillar 03
          title: |
            Low-Temperature<br>Growth
          lead: |
            Single-crystal 2D materials grown below 400&deg;C — the enabling technology behind monolithic integration.
          accent: amber
          cta_label: Explore Research
          cta_url: ./research/
      image:
        filename: Lab main.png
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
      css_class: latest-news

  - block: collection
    content:
      title: Selected Publications
      text: ""
      count: 0
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
      columns: '2'
      css_class: selected-pubs
    
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
