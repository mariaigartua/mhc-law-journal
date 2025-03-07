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
      text_color: white
      text_align: left
      background:
        image: 
          filename: background.jpg
          filters:
            brightness: 0.6
          parallax: false
          position: center
          size: cover
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest News
      subtitle: ""
      text: ""
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
      title: Latest Preprints
      subtitle: ""
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
      title: ""
      subtitle: ""
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the Board →" %}}
    design:
      columns: '1'
---
