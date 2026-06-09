---
title:
date: 2026-06-08
type: landing

sections:
  - block: hero
    content:
      title: |
        Forschungsgruppe
        Mobile Robotik
      image:
        filename: robotics-hero.png
      text: |
        <br>

        **Prof. Dr. Christian Pfitzner** · TH Nürnberg Georg Simon Ohm · Fakultät efi · TTZ Nürnberger Land

        Hier finden Sie aktuell ausgeschriebene Projekt-, Bachelor- und Masterarbeiten.
        Bei Interesse senden Sie bitte Ihren Lebenslauf sowie einen Notenausdruck an den
        jeweiligen Ansprechpartner der Ausschreibung.

  - block: collection
    content:
      title: Aktuelle Ausschreibungen
      subtitle:
      text:
      count: 10
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: publication
    design:
      view: card
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./publication/" cta_text="Alle Ausschreibungen ansehen →" %}}
    design:
      columns: '1'

  - block: collection
    content:
      title: Aktuelles
      subtitle:
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: compact
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./post/" cta_text="Alle Neuigkeiten ansehen →" %}}
    design:
      columns: '1'
---
