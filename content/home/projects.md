+++
widget = "portfolio"  # Use the Portfolio widget
headless = true  # This file represents a page section.

active = true  # Activate this widget? true/false
weight = 65  # Order that this section will appear.
title = "Projects"

[content]
  # Page type to display. E.g. project.
  page_type = "project"
  
  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.
  
  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0
  
  [[content.filter_button]]
    name = "All"
    tag = "*"
  
  [[content.filter_button]]
    name = "Transportation Demand Analysis"
    tag = "transportation"
  
  [[content.filter_button]]
    name = "Location Choice"
    tag = "location"
	
  [[content.filter_button]]
    name = "Urban Energy"
    tag = "energy"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact  
  #   3 = Card
  #   5 = Showcase
  view = 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows = false
+++

