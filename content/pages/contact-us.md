---
type: PageLayout
title: Contact Us
permalink: "/contact-us/"
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
          label: Which service interests you most?
          hideLabel: false
          defaultValue: Please choose...
          options:
            - AI Readiness Audit
            - AI Strategy & Roadmap
            - AI Training Workshops
            - Ongoing AI Consulting Services
            - Custom AI Agent or App
            - Other
          isRequired: true
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
  - type: CustomCodeBlock
    elementId: hidden-netlify-form
    code: |
        <div hidden>
          <form name="contact-form" method="POST" data-netlify="true" netlify-honeypot="bot-field">
            <input type="text" name="name" />
            <input type="email" name="email" />
            <textarea name="message"></textarea>
          </form>
        </div>
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
