---
# Leave the homepage title empty to use the site title
title: ""
date: 2024-11-08
type: landing

design:
  background:
    # Choose a color such as from https://html-color-codes.info
    color: 'crimson'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: light
      background:
        color: white
        text_color_light: false
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        I am currently working on papers regarding global games, congestion networks, heterogeneity in welfare analysis and information avoidance. I also plan on transitioning to more empirical work in the coming months.
    design:
      columns: '1'
---
