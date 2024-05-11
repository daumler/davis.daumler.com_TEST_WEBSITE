---
title: Journal Articles
cms_exclude: true

# View.
#   1 = List
#   2 = Compact
#   3 = Card
#   4 = Citation
view: 2

# Optional header image (relative to `static/media/` folder).
# header:
#   caption: ''
#   image: ''

title: ''
date: ''
type: widget_page
sections:
  - block: collection
    content:
      filters:
        featured_only: false
        folders:
        - journal_articles
      title: Journal articles
    design:
      columns: "2"
      view: 2
    id: journal
  - block: collection
    content:
      filters:
        featured_only: true
        folders:
        - publications3
      title: Working papers
    design:
      columns: "2"
      view: 2
    id: preprint
---
