---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: accomplishments

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 65

title: Teaching
subtitle: ''

content:
  # Page type to display. E.g. project.
  page_type: teaching

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
  - name: All
    tag: '*'
  - name: Deep Learning
    tag: Deep Learning
  - name: Other
    tag: Demo
item:
-  url: uploads/KSU.pdf
  date_end: "2012-06-06"
  date_start: "2009-07-25"
  description: "I got Distinguished Rewards several times during my Bachelor’s degree"
  organization: The University of King Saud
  organization_url: https://ksu.edu.sa/en/
  title:  Distinguished Rewards
  url: ""
  
design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 1

  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---
