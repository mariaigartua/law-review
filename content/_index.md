---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      # title: |
      #   <span style="color: white;">Mount Holyoke College Law Journal</span>

      text: |
        <br>
        <span style="color: white;">
          The Mount Holyoke College Undergraduate Law Journal seeks to <b style="color: white; background-color: #002D62">elevate the voices of Mount Holyoke College students in the field of legal scholarship. </b>        
        </span>

    design:
      background:
        image:
        
          # Name of image in `assets/media/`.
          filename: welcome.jpg
          # Apply image filters?
          filters:
            # Darken the image? Range 0-1 where 1 is transparent and 0 is opaque.
            brightness: 0.8
          #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
          size: cover
          # Image focal point. Options include `left`, `center` (default), or `right`.
          position: center
          # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: true
          # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: true

      # background:
      #   # Choose colors such as from https://html-color-codes.info
      #   gradient_start: '#4bb4e3'
      #   gradient_end: '#2b94c3'
      #   # The gradient angle from 0-360 degrees
      #   gradient_angle: 180
      #   # Text color (true=light, false=dark, or remove for the dynamic theme color).
      #   text_color_light: true

  - block: collection
    content:
      title:  Latest Articles
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
      css_class: "mtholyoke-articles"
      view: showcase
      columns: '1'


  # - block: collection
  #   content:
  #     title: Latest Articles
  #     text: ""
  #     count: 5
  #     filters:
  #       folders:
  #         - publication
  #       publication_type: 'conference-paper'
  #   design:
  #     css_class: "mtholyoke-articles"
  #     view: showcase
  #     columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the Team →" %}}

    design:
      css_class: "mtholyoke-meetboard"
      columns: '1'
      view: card
      # background:
      #   color: 'navy'

---
