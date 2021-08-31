---
title: Kontakt
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: >
      Hallo! Vielen Dank für Ihr Interesse an Kerngesund.de! Hier können Sie ein
      Kontaktformular ausfüllen, um uns eine
      [E-Mail](mailto:info@1fach-bewegen.de) zu schicken.
    form_id: contactForm
    form_action: /danke
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Ihr Name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Ihre Email-Adresse
        is_required: true
      - input_type: select
        name: subject
        label: Worum gehts?
        default_value: Bitte auswählen
        options:
          - Fehler auf der Seite melden
          - Förderer
          - Anderes
      - input_type: textarea
        name: message
        label: Nachricht
        default_value: Ihre Nachricht
      - input_type: checkbox
        name: Einverständnis
        label: >-
          Ich habe verstanden, dass meine persönlichen Daten gespeichert werden,
          um mich kontaktieren zu können.
    submit_label: Nachricht schicken
seo:
  title: KontaKt
  description: Dies ist die Kontakseite
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: Dies ist die Kontakseite
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
