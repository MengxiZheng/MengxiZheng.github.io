---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Welcome to  <br>
        ZHENG Research Lab
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        Established in 2025, the Zheng Research Lab at Illinois Tech develops programmable nucleic acid nanotechnologies for molecular sensing and smart diagnostics.
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 2
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
      subtitle:
      text: |
        {{< cta cta_text="Explore Opportunities" cta_link="./oppor/" cta_new_tab="false" cta_alt_text="Meet with Mengxi" cta_alt_link="./people/" cta_alt_new_tab="false" >}}
    design:
      columns: '1'

  - block: markdown
    design:
      columns: '1'
      background:
        image: 
          filename: Fultonlab1.png
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen


  - block: collection
    content:
      title: Latest Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 
    design:
      view: citation
      columns: '1'
---
