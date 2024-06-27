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
  - block: experience
    id: service
    content:
      title: Service
      date_format: "2006"
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Program Chair
          company: ''
          date_start: '2024-01-01'
          description: |2-
              CASCADE &ndash; [**2024**](http://cascade-conference.org/)<br>
              Fault Diagnosis and Tolerance in Cryptography (FDTC) &ndash; [**2023**](https://fdtc.deib.polimi.it/FDTC23/)
        - title: Program Committee
          company: ''
          date_start: '2024-01-01'
          description: |2-
              Smart Card Research and Advanced Application (CARDIS) &ndash; [**2021**](https://cardis2021.its.uni-luebeck.de/), [**2022**](https://events.cs.bham.ac.uk/cardis2022/), [**2023**](https://sbd-research.nl/cardis-2023/)<br>
              Constructive Side‐Channel Analysis and Secure Design (COSADE) &ndash; [**2023**](https://www.cosade.org/cosade23/), [**2024**](https://www.cosade.org/cosade24/)<br>
              Design, Automation and Test in Europe (DATE) &ndash; [**2024**](https://www.date-conference.com/tpc#DT5)<br>
              Fault Diagnosis and Tolerance in Cryptography (FDTC) &ndash; [**2024**](https://fdtc.deib.polimi.it/FDTC24/)
        - title: Editorial Board
          company: ''
          date_start: '2024-01-01'
          description: |2-
              Transactions on Cryptographic Hardware and Embedded Systems (IACR TCHES) &ndash; [**2021**](https://ches.iacr.org/2021/), [**2022**](https://ches.iacr.org/2022/), [**2023**](https://ches.iacr.org/2023/), [**2024**](https://ches.iacr.org/2024/), [**2025**](https://ches.iacr.org/2025/)
    design:
      columns: '2'
  - block: accomplishments
    id: awards
    content:
      title: Awards
      text:
      items:
        - title: Admission to the Young College
          certificate_url: ''
          date_start: '2024-01-01'
          date_end: '2027-12-31'
          # description: 'Admission to the Young College is an important distinction for young scientists and artists in North Rhine-Westphalia. Fellows receive an annual stipend of 10,000 € for a period of up to four years.'
          organization: Nordrhein-Westfälische Akademie der Wissenschaften und der Künste
          organization_url: 'https://www.awk.nrw/'
          url: 'https://www.awk.nrw/news/jk/gesichter-des-jungen-kollegs-dr-ing-pascal-sasdrich'
        - title: Associate Principle Investigator (PI)
          certificate_url: ''
          date_start: '2023-01-01'
          date_end: ''
          description: ''
          organization: 'Cluster of Excellence CASA - Cyber Security in the Age of Large-Scale Adversaries'
          organization_url: 'https://casa.rub.de/'
          url: ''
        - title: Deutscher IT-Sicherheitspreis (100.000 €)
          certificate_url: ''
          date_start: '2022-11-10'
          date_end: ''
          # description: '1st place (awarded with 100,000 €) for the concept "Simply Secure: A Toolbox for Automated Generation and Evaluation of Protected Hardware" (together with David Knichel, Amir Moradi, Nicolai Müller).'
          organization: Horst Görtz Stiftung
          organization_url: 
          url: 'https://www.deutscher-it-sicherheitspreis.de/'
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
        featured_only: false
        exclude_future: true
        exclude_past: false
      count: 10
      sort_by: 'Date'
      sort_ascending: false
    design:
      columns: '2'
      view: 3
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
