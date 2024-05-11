---
title: null
type: landing  
#title: Publications
#cms_exclude: true
# View.
#   1 = List
#   2 = Compact
#   3 = Card
#   4 = Citation
# view: 2
# Optional header image (relative to `static/media/` folder).
# header:
#   caption: ''
#   image: ''
sections:
  - block: collection
    content:
      filters:
        featured_only: false
        folders:
        - publications
      title: Journal articles
    design:
      columns: "2"
      view: card
    id: journal
  - block: collection
    content:
      filters:
        featured_only: false
        folders:
        - article
      title: Working papers
    design:
      columns: "2"
      view: card
    id: preprint
---
