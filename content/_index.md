---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:

  - block: slider
    content:
      slides:
      - title: Data Manent 
        content: Understanding digital world
        #content: Siamo una piattaforma senza scopo di lucro per essere consapevoli delle pratiche commerciali e dei rischi del web e dei dispositivi tecnologici.
        align: center
        background:
          image:
            filename: vr_1610.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000


  - block: hero
    content:
      title: |
        Manifesto
      text: |
        Data Manent è una piattaforma senza scopo di lucro dedicata a promuovere la consapevolezza sulle pratiche commerciali e i rischi legati al web e ai dispositivi tecnologici. Offriamo guide informative e risorse pratiche per aiutarti a comprendere e affrontare le sfide digitali. La nostra missione è educativa e orientata a fornire agli utenti strumenti per prendere decisioni consapevoli, contribuendo così a una società digitale più sicura e informata.
  #- block: tag_cloud
  #  content:
  #    title: Argomenti Popolari
  #    subtitle: 
  #    text: 
      # Choose a taxonomy from the `taxonomies` list in `config.yaml` to display (e.g. tags, categories, authors)
  #    taxonomy: tags
      # Choose how many tags you would like to display (0 = all tags)
  #    count: 20
  #  design:
      # Minimum and maximum font sizes (1.0 = 100%).
  #    font_size_min: 0.7
  #    font_size_max: 2.0
  #    columns: '1'


  - block: collection
    id: posts
    content:
      title: Ultimi Articoli
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - social-media
          - sistemi-operativi
          - software
          - web-browsers
          - wearables
          - formazione
        author: ""
        category: ""
        tag: ""
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      # Choose a listing view
      view: card
      # Choose single or dual column layout


#  - block: markdown
#    content:
#      title:
#      subtitle: ''
#      text:
#    design:
#      columns: '1'
#      background:
#        image: 
#          filename: coders.jpg
#          filters:
#            brightness: 1
#          parallax: false
#          position: center
#          size: cover
#          text_color_light: true
#      spacing:
#        padding: ['20px', '0', '20px', '0']
#      css_class: fullscreen
#  
#  - block: markdown
#    content:
#      title:
#      subtitle:
#      text: |
#        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
#    design:
#      columns: '1'
  
---