---
# Page title
title: 
# Page type - we want a landing page (such as a homepage)
type: landing

design:
  spacing: 2rem


# Your landing page sections - add as many different content blocks as you like
sections:
  - block: collection
    id: articles
    content:
      title: Artículos
      filters:
        folders:
          - publication
        publication_type: "article-journal"
    design:
      view: citation
    sort_by: 'Date'
  - block: collection
    id: chapter
    content:
      title: Capítulos de libros
      filters:
        folders:
          - publication
        publication_type: "chapter"
    design:
      view: citation
    sort_by: 'Date'
  - block: collection
    id: reports
    content:
      title: Informes técnicos
      filters:
        folders:
          - publication
        publication_type: "report"
    design:
      view: citation
    sort_by: 'Date'
---