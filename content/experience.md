---
title: 'Education & Awards'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-experience
    content:
      username: me
    design:
      # Hugo date format (years for education)
      date_format: '2006'
      # Show Education only (career history hidden on this page)
      show_experience: false
      is_education_first: true
      spacing:
        padding: ["2.5rem", "0", "1.5rem", "0"]
  - block: resume-certifications
    content:
      title: Certifications
      username: me
    design:
      date_format: '2 January 2006'
      spacing:
        padding: ["1.5rem", "0", "1.5rem", "0"]
  - block: resume-awards
    content:
      title: Selected Awards
      username: me
    design:
      spacing:
        padding: ["1.5rem", "0", "2.5rem", "0"]
---
