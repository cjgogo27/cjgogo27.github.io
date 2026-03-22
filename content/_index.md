---
title: ''
summary: ''
date: 2026-03-22
type: landing

design:
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text:  Download CV
        url: /uploads/resume.pdf
      headings:
        about: 'Professional Summary'
        education: 'Education'
        interests: 'Research Interests'
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle
        
  - block: experience
    content:
      title: 'Experience & Awards'
      username: me
      # This block will automatically read from content/experience/
      
  - block: collection
    id: papers
    content:
      title: 'Publications'
      filters:
        folders:
          - publications
    design:
      view: article-grid
      columns: 2

