---
title: Contact us
sections:
  - type: ContactSection
    title: Contact us
    text: >-
      Fill out the form below and we will get in touch within 1 business day.
      Various versions have evolved over the years, sometimes by accident,
      sometimes on purpose (injected humour and the like).
    variant: variant-a
    topGap: none
    bottomGap: none
    contentAlignVert: top
    feature:
      type: FormBlock
      action: /.netlify/functions/submission_created
      idAttr: contact-form
      submitLabel: Contact
      fields:
        - type: TextFormControl
          label: Name
          placeholder: Your name
          width: 1/2
        - type: TextFormControl
          label: Last name
          placeholder: Your last name
          width: 1/2
        - type: EmailFormControl
          label: Email
          placeholder: Your email
          width: full
        - type: CheckboxFormControl
          label: Sign me up to receive updates
          width: full
layout: PageLayout
---
