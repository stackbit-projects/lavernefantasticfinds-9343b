---
title: Contact
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: |-
      Reach us out!

      Our Address
      230 St Lawrence Street
      Unit 6
      Merrickville, ON K0G1N0
      Inside the Larkspur Lane Country Mall

      By Email
      lavsfantasticfinds@outlook.com

      Give us a call
      (343) 987-2711

      Or, to get in touch please fill the form below.
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: select
        name: subject
        label: Subject
        default_value: Please select
        options:
          - Error on the site
          - Sponsorship
          - Other
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Send Message
template: advanced
---
