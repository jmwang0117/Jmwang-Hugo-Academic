---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: pages

# This file represents a page section.
headless: true
active: true

# Order that this section appears on the page.
weight: 30

title: Selected Publications
subtitle: ''

content:
  # Page type to display. E.g. project.
  page_type: publication

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0
  filter_button:
    - name: All Projects
      tag: '*'
    - name: 2022
      tag: 2022
    - name: 2021
      tag: 2021
    - name: Robotics
      tag: Robotics
    - name: Computer Vision
      tag: Computer Vision
    - name: Edge Computing
      tag: Edge Computing
    - name: Computer Graphic
      tag: Computer Graphic
    


design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '1'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 2

  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---

{{% callout note %}}
Quickly discover relevant content by [filtering publications](./publication/).
{{% /callout %}}
