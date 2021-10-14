---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 65

title: Projects
subtitle: ''

content:
  # Page type to display. E.g. project.
  page_type: project

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
  - name: "Animal electrophysiology"
    tag: "Animal ephys"
  - name: "Benchtop"
    tag: "Benchtop"
  - name: "Behaviour"
    tag: "Behaviour"
  - name: "Calcium Imaging"
    tag: "Calcium Imaging"
  - name: "Computers"
    tag: "Computers"
  - name: "Computer Clusters"
    tag: "Computer clusters"
  - name: "Data Analysis"
    tag: "Data analysis"
  - name: "Data Repositories"
    tag: "Database"
  - name: "Electric Stimulation"
    tag: "Electric"
  - name: "Fluorescence"
    tag: "Fluorescence"
  - name: "Hardware"
    tag: "Hardware"  
  - name: "Human Neuroscience"
    tag: "Human Neuroscience"
  - name: "Human electrophysiology"
    tag: "Human ephys"
  - name: "Microscopes"
    tag: "Microscope"
  - name: "Microscopes software"
    tag: "Microscopes software"
  - name: "Optogenetics"
    tag: "Optogenetics"
  - name: "Prosthetics"
    tag: "Prosthetics"
  - name: "Simulations"
    tag: "Simulation"
  - name: "Software"
    tag: "Software"
  - name: "Tutorials and learning portals"
    tag: "Learning"
  - name: "World Wide Series Seminars"
    tag: "worldwideseries"
  - name: "Other"
    tag: "Other"


design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '1'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---
