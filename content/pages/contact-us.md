---
type: PageLayout
title: Contact Us
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: Prepare for the future with us.
      color: text-dark
    subtitle: We can't wait to meet you!
    text: >+
      Whether you want to learn more about us, book your FREE AI readiness
      consultation, or retain our services, reaching out is the first step!
      Please send us an email or fill out the contact form below to get things
      started.


      ### [Email](mailto:rachelcradke@gmail.com)

    actions: []
    media:
      type: FormBlock
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
        - type: TextFormControl
          name: business name
          label: Business/Organization
          hideLabel: true
          placeholder: Your business or organization
          isRequired: false
          width: full
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
        - type: SelectFormControl
          name: choose-type
          label: Company size
          hideLabel: false
          defaultValue: Please choose...
          options: []
          isRequired: false
          width: full
        - type: TextareaFormControl
          name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        icon: arrowRight
        iconPosition: right
        style: primary
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
    badge:
      type: Badge
      label: Contact Us
      color: text-primary
    colors: bg-light-fg-dark
slug: contact-us
isDraft: false
seo:
  type: Seo
  metaTitle: Landing Page
  metaDescription: Write here your new page's description including most relevant keywords.
  addTitleSuffix: true
  socialImage: /images/main-hero.jpg
  metaTags: []
---
