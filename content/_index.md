---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: 'My Research'
      subtitle: ''
      text: |-
        I am interested in algebraic and nonarchimedean geometry, in particular I study D-modules in these settings. In my [Ph.D. thesis](https://sites.google.com/impan.pl/feliks-raczka/home/thesis?authuser=0) I studied de Rham cohomology of holonomic D-modules on rigid-analytic varieites. Recently, I also think a lot about D-affinity of flag varieties in positive characteristc and related problems from geometric representation theory.  
    design:
      columns: '1'
  - block: collection
    content:
      title: Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: markdown
    content:
      title: 'Recent News'
      subtitle: ''
      text: |-
        text text text
    design:
      columns: '1'
---
