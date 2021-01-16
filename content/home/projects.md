---
# A Projects section created with the Portfolio widget.
widget: portfolio  # See https://sourcethemes.com/academic/docs/page-builder/
headless: true  # This file represents a page section.
active: true  # Activate this widget? true/false
weight: 20  # Order that this section will appear.

title: Projects
subtitle: ""

content:
  # Page type to display. E.g. project.
  page_type: project

  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete the entire `filter_button` block.
  filter_botton:
  - name: All
    tag: "*"
  - name: Broadly Neutralizing Antibodies
    tag: bnabs
  - name: Clinical Trials
    tag: clinical-trials
  - name: Collaborative Science
    tag: collaborative-science
  - name: Microbial Abundance
    tag: microbial-abundance
  - name: Variable Importance
    tag: variable-importance

design:
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns: "2"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---
