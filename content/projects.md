---
title: 'Projects'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: collection
    content:
      title: Selected Projects
      text: ''
      filters:
        folders:
          - project
    design:
      view: article-grid
      fill_image: false
      columns: 3
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: true
      background:
          image:
            # Name of image in `assets/media/`.
            filename: background.jpeg
            # Apply image filters?
            filters:
              # Darken the image? Range 0-1 where 1 is transparent and 0 is opaque.
              brightness: 0.6
            #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
            size: cover
            # Image focal point. Options include `left`, `center` (default), or `right`.
            position: center
            # Use a fun parallax-like fixed background effect on desktop? true/false
            parallax: true
            # Text color (true=light, false=dark, or remove for the dynamic theme color).
            text_color_light: true
---
