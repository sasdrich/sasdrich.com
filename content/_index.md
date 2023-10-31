---
# Leave the homepage title empty to use the site title
title: 'Pascal Sasdrich'
date: 2023-10-31
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      username: pascal
  # - block: markdown
  #   id: service
  #   content:
  #     title: Service
  #     text: |-
  #         ### Program Committees
  #         * Smart Card Research and Advanced Application (CARDIS): 2021 - 2022
  #   design:
  #     columns: '2'
  # - block: accomplishments
  #   id: awards
  #   content:
  #     title: Awards
  #     text:
  #     items:
  #       - title: 9. Deutscher IT-Sicherheitspreis (1. Platz, 100.000 €)
  #         certificate_url: ''
  #         date_end: ''
  #         date_start: '2022-11-10'
  #         description: 'Einfach sicher: Ein Werkzeugkasten zur automatisierten Erstellung geschützter Hardware (zusammen mit David Knichel, Amir Moradi und Nicolai Müller)'
  #         organization: Horst Görtz Stiftung
  #         organization_url: https://www.deutscher-it-sicherheitspreis.de/
  #         url: ''
    design:
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Publications
      text:
      count: 0
      filters:
        folders:
          - publication
        # publication_type: '1' # conference proceedings
        # publication_type: '2' # journal articles
        exclude_future: true
        exclude_past: false
      sort_by: 'Date'
      sort_ascending: false
    design:
      columns: '2'
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
       
      email: pascal.sasdrich@rub.de
      phone: +49 234 32-25734
      appointment_url: ''
      address:
        street: Universitätsstr. 150
        city: 44801 Bochum
        region: NRW
        country: Germany
        country_code: DE
      directions: 
      office_hours:
      contact_links:
      autolink: true
    design:
      columns: '2'
---
