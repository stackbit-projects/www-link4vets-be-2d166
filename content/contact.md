---
title: Contact Info
img_alt: ''
form_id: contactform
form_action: /contact-success
form_fields:
  - input_type: text
    name: name
    label: Naam
    default_value: Jouw naam
    is_required: true
  - input_type: email
    name: email
    label: Email
    default_value: Jouw email adres
    is_required: true
  - input_type: select
    name: subject
    label: Onderwerp
    default_value: Kies een onderwerp
    options:
      - Fout op de site
      - Link4Vets Puppy Database
      - Sponsorship
      - Overige
  - input_type: textarea
    name: message
    label: Bericht
    default_value: Jouw Bericht
  - input_type: checkbox
    name: consent
    label: >-
      ik begrijp dat dit formulier mijn informatie opslaat zodat ik
      gecontacteerd kan worden.
submit_label: Versturen
layout: contact
subtitle: test
---

Fill the form below to get in touch with me.
