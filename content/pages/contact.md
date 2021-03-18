---
title: Kapcsolat
hide_title: false
sections:
  - type: form_section
    section_id: contact-form
    content: |+
      Let’s build something great together.<br>
      Complete our contact form or send us an email at <email@example.com>.

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
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Küldés
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
