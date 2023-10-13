---
title: Media
date: 2023-10-13

type: landing

sections:
  - block: portfolio
    id: projects
    content:
      title: Media
      subtitle: Media suggeriti, raggruppati per tipologia
      text: ''
      filters:
        # Folders to display content from
        folders:
          - media-full
        # Which Hugo page kinds to show (https://gohugo.io/templates/section-templates/#page-kinds)
        kinds:
          - page
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
      # Default portfolio filter button
      # 0 corresponds to the first button below and so on
      # For example, 0 will default to showing all content as the first button below shows content with *any* tag
      default_button_index: 0
      # Filter button toolbar (optional).
      # Add or remove as many buttons as you like.
      # To show all content, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the button toolbar, delete the entire `buttons` block.
      buttons:
        - name: Tutti
          tag: '*'
        - name: Libri
          tag: libri
        - name: Film
          tag: film
        - name: Software
          tag: software
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose a listing view
      view: 
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
---