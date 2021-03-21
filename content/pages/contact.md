---
title: Kapcsolat
hide_title: false
sections:
  - type: form_section
    section_id: contact-form
    content: >
      Készítsünk neked valami szépet! Ha árajánlatot szeretnél, vagy kérdésed 
      van, töltsd ki a kapcsolati űrlapot az oldalon, vagy írj egy email az
      <info@pennarello.hu> címen!


      ***
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Név
        default_value: Keresztnév
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Email cím
        is_required: true
      - input_type: textarea
        name: message
        label: Üzenet
        default_value: Írd be az üzeneted...
      - input_type: checkbox
        name: consent
        label: >-
          Hozzájárulok az űrlapon megadott adataim kapcsolattartáshoz való
          tárolásához.
    submit_label: Küldés
seo:
  title: Kapcsolat | Pennarello Kft.
  description: 'Árajánlatkérés grafikai tervezésre, és egyedi Miskolc faliképek rendelése'
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Kapcsolat | Pennarello Kft.
      keyName: property
    - name: 'og:description'
      value: Kapcsolat | Pennarello Kft.
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Kapcsolat | Pennarello Kft.
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
