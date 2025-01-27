---
type: PageLayout
title: About
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg4.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    text: >
      ### Hello! I’m a passionate software developer with a strong enthusiasm
      for tackling complex problems. My primary focus is on Python, and I’m
      always looking for ways to enhance my coding skills and keep up with the
      latest trends in technology. I love what I do and am excited to continue
      growing in this ever-evolving field!


      I believe in the power of continuous learning and brain engagement, always
      challenging myself to think critically and improve. Outside of coding, I
      share my journey  to stay consistent and motivated.


      i’m always excited to connect with like-minded individuals, learn from
      others, and collaborate on meaningful projects. Feel free to explore my
      work, and don’t hesitate to reach out!
    media:
      type: ImageBlock
      altText: Hero image
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
          - pt-16
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 8
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
  - type: HeroSection
    title: ''
    subtitle: ''
    actions:
      - type: Button
        label: about me
        altText: ''
        url: 'https://amarnani.netlify.app/info/'
        showIcon: true
        icon: arrowRight
        iconPosition: left
        style: secondary
        elementId: ''
      - type: Button
        label: ' My GitHub'
        altText: ''
        url: '/https://github.com/amarnani121'
        showIcon: true
        icon: github
        iconPosition: right
        style: secondary
        elementId: ''
      - type: Button
        label: ' LinkedIn'
        altText: ''
        url: 'https://www.linkedin.com/in/amareshuppaluri/'
        showIcon: true
        icon: linkedin
        iconPosition: right
        style: secondary
        elementId: ''
      - type: Button
        label: Projects
        altText: ''
        url: '/https://amarnani.netlify.app/projects/'
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
      - type: Button
        label: YouTube
        altText: ''
        url: 'https://youtube.com/@amarnani121'
        showIcon: true
        icon: playCircle
        iconPosition: right
        style: secondary
        elementId: ''
      - type: Button
        label: RESUME
        altText: ''
        url: >-
          https://docs.google.com/document/d/1NtemMRoSvtvT1nEdltOE_KI8tiQ2A_KCCCpP9BjuoLs/edit?usp=sharingusp=sharing
        showIcon: true
        icon: arrowRightCircle
        iconPosition: right
        style: secondary
        elementId: ''
    colors: colors-f
    backgroundSize: inset
    elementId: ''
    styles:
      self:
        height: auto
        width: full
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: ContactSection
    backgroundSize: full
    title: "Let’s talk... \U0001F4AC"
    colors: colors-f
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: '"Can you share your thoughts with me?"'
          isRequired: true
          width: full
          type: TextareaFormControl
        - name: updatesConsent
          label: Sign me up to recieve my words
          isRequired: false
          width: full
          type: CheckboxFormControl
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
          - ml-4
          - mr-4
        padding:
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
