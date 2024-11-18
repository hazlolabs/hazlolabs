---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: >-
      HAZLO LABS can take your startup from idea to revenuE & BEYOND with our
      unique investment, incubation and acceleration approach.
    subtitle: >-
      While cash flow is critical in the early stages of any business, not all
      money is the same. You need people who understand and believe in your
      vision—partners who know how to bring it to life and turn it into a
      thriving, scalable brand.
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
    text: ''
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: "Got an interesting startup? Tell us more...\U0001F4AC"
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: 1/2
          type: EmailFormControl
        - type: TextareaFormControl
          name: message
          label: Message
          hideLabel: false
          placeholder: Type your message here
          width: full
          isRequired: false
      submitLabel: "Submit \U0001F680"
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
    text: >
      **Send you pitch deck to**
      [**brian@hazlolabs.com**](mailto:brian@hazlolabs.com?subject=Pitch%20Deck)****
---
