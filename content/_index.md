---
# Leave the homepage title empty to use the site title
title: Mount Holyoke College Law Journal
date: 2022-10-24
type: landing

sections:

- block: hero
  content:
    title: |
      Mount Holyoke College 
      Law Review
    text: |
      <br>
      The Mount Holyoke College Undergraduate Law Journal seeks to elevate the voices of Mount Holyoke College students in the field of legal scholarship.
  design:
    columns: '1'
    background:
      image: 
        filename: background.jpg
        filters:
          brightness: 0.6
        parallax: false
        position: center
        size: cover
    text_color: white
    text_align: left
    spacing:
      padding: ['20px', '0', '20px', '0']
    css_class: fullscreen


  # - block: hero
  #   content:
  #     title: |
  #       Mount Holyoke College 
  #       Law Review
  #     text: |
  #       <br>
  #       The Mount Holyoke College Undergraduate Law Journal seeks to elevate the voices of Mount Holyoke College students in the field of legal scholarship.
  #     design:
  #       background:
  #         image:
  #           # Name of image in `assets/media/`.
  #           filename: background.jpg
  #           # Apply image filters?
  #           filters:
  #             # Darken the image? Range 0-1 where 1 is transparent and 0 is opaque.
  #             brightness: 0.6
  #           #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
  #           size: cover
  #           # Image focal point. Options include `left`, `center` (default), or `right`.
  #           position: center
  #           # Use a fun parallax-like fixed background effect on desktop? true/false
  #           parallax: true
  #           # Text color (true=light, false=dark, or remove for the dynamic theme color).
  #           text_color_light: true

  # - block: hero
  #   content:
  #     title: |
  #       Mount Holyoke College 
  #       Law Review
  #     image:
  #       filename: welcome.jpg
  #     text: |
  #       <br>
  #       The Mount Holyoke College Undergraduate Law Journal seeks to elevate the voices of Mount Holyoke College students in the field of legal scholarship.
  #     design:
  #       background:
  #       # Choose a color such as from https://html-color-codes.info
  #       color: 'navy'
  #       # Text color (true=light, false=dark, or remove for the dynamic theme color).
  #       text_color_light: true

  
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
  
  - block: hero
    content:
      title: |
        Mount Holyoke College 
        Law Review
      text: |
        <br>
        The Mount Holyoke College Undergraduate Law Journal seeks to elevate the voices of Mount Holyoke College students in the field of legal scholarship.
    design:
      columns: '1'
      background:
        image: 
          filename: background.jpg
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
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the Board →" %}}
    design:
      columns: '1'
---
