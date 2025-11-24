---
# Leave the homepage title empty to use the site title
title: ''
date: 2025-11-14
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      #title: 'About me'
      text: ''
      button: false
        # text: Download CV
        # url: uploads/resume.pdf
      # Show a call-to-action button under your biography? (optional)
      headings:
        about: 'About me'
        education: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: square # Options: circle (default), square, rounded
        text: 'text'
      # icons:
      #   about: ''
      #   education: ''
      #   interests: ''
  - block: markdown
    id: news
    content:
      title: 'Recent news'
      subtitle: ''
      text: |-
        I won the [International Stefan Banach prize](https://ibp.ptm.org.pl/en/laureaci/) for the best Ph.D. dissertation.
    design:
      columns: '1'
  - block: markdown
    id: research
    content:
      title: 'My research'
      subtitle: ''
      text: |-
        I am interested in D-modules in algebraic and nonarchimedean geometry. In my [Ph.D. thesis](https://sites.google.com/impan.pl/feliks-raczka/home/thesis?authuser=0) I studied de Rham cohomology of holonomic D-modules on rigid-analytic varieites. Recently, I also think a lot about D-affinity of flag varieties in positive characteristc and related problems from geometric representation theory.
    design:
      columns: '1'
      
---
