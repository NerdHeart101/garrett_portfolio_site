---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: portfolio
    id: projects
    content:
      title: Portfolio
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Robotics
          tag: Robotics
        - name: Computer Science
          tag: Computer Science
        - name: User Experience
          tag: User Experience
        - name: Visual Design
          tag: Visual Design
        - name: Instructional Development
          tag: Instructional Development
        - name: Marketing
          tag: Marketing
        
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: masonry
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
---
