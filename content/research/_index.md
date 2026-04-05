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
  - block: collection
    content:
      title: Working Papers
      count: 0
      text: ''
      filters:
        folders:
          - publications
        publication_type: working-paper
        exclude_featured: false
    design:
      view: citation
      spacing:
        padding: ['3rem', '0', '3rem', '0']
  - block: collection
    content:
      title: Publications
      count: 0
      text: ''
      filters:
        folders:
          - publications
        publication_type: article-journal
        exclude_featured: false
    design:
      view: citation
      spacing:
        padding: ['3rem', '0', '3rem', '0']
  - block: collection
    content:
      title: Works in Progress
      count: 0
      text: ''
      filters:
        folders:
          - publications
        publication_type: in-progress
        exclude_featured: false
    design:
      view: citation
      spacing:
        padding: ['3rem', '0', '3rem', '0']


---
