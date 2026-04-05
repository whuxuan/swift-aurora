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
      title: Working Paper
      text: ''
      filters:
        folders:
          - publications
        publication_type: working-paper
        exclude_featured: false
    design:
      view: citation
      spacing:
        padding: ['2rem', '0', '2rem', '0']
  - block: collection
    content:
      title: Publications
      text: ''
      filters:
        folders:
          - publications
        publication_type: article-journal
        exclude_featured: false
    design:
      view: citation
      spacing:
        padding: ['2rem', '0', '2rem', '0']
  - block: collection
    content:
      title: Works in Progress
      text: ''
      filters:
        folders:
          - publications
        publication_type: in-progress
        exclude_featured: false
    design:
      view: citation
      spacing:
        padding: ['2rem', '0', '2rem', '0']


---
