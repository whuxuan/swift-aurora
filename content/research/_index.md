---
# Leave the homepage title empty to use the site title
title: 'Research'
summary: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '1rem'

sections:
  - block: tag-cloud
    content:
      title: Topics
      taxonomy: tags
      count: 20
      font_size_min: 0.8
      font_size_max: 2.0
      filters:
        folders:
          - publications
    design:
      spacing:
        padding: ['3rem', '0', '1rem', '0']
  - block: paper-list
    content:
      title: Working Papers
      filters:
        folders:
          - publications
        publication_type: working-paper
    design:
      spacing:
        padding: ['3rem', '0', '3rem', '0']
  - block: paper-list
    content:
      title: Publications
      filters:
        folders:
          - publications
        publication_type: article-journal
    design:
      spacing:
        padding: ['3rem', '0', '3rem', '0']
  - block: paper-list
    content:
      title: Works in Progress
      filters:
        folders:
          - publications
        publication_type: in-progress
    design:
      spacing:
        padding: ['3rem', '0', '3rem', '0']


---
