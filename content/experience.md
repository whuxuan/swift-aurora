---
title: 'CV'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: cta-button-list
    content:
      buttons:
        - text: Download CV
          url: 'https://www.dropbox.com/s/e8n0l83yknn60bt/CV.pdf'
          icon: hero/arrow-down-tray
    design:
      spacing:
        padding: ['1rem', '0', '1rem', '0']
  - block: resume-experience
    content:
      username: me
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  # - block: resume-skills
  #   content:
  #     title: Skills & Hobbies
  #     username: me
  - block: resume-awards
    content:
      title: Awards
      username: me
  # - block: resume-languages
  #   content:
  #     title: Languages
  #     username: me
---
