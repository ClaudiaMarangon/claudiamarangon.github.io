---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: CV
        url: uploads/cv_claudiamarangon_2024.pdf
    design:
      css_class: light
      background:
        color: white
  - block: collection
    id: research
    content:
      title: Research
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
      css_class: light
      background:
        color: lavender
  - block: markdown
    id: teaching
    content:
      title: Teaching
      subtitle: ''
      text: ''

  - block: markdown
    id: news
    content:
      title: Contact
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      css_class: light
      background:
        color: lavender
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
---
