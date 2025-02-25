---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/featured-Image4.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 100
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: inset
    title: '"Exploring Code: A Portfolio of My Work"'
    subtitle: >-
      A showcase of creativity, dedication, and skills. Scroll down to explore
      the details that define me
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
  - type: RecentProjectsSection
    subtitle: Projects
    actions:
      - type: Link
        label: See all projects
        altText: See all projects
        url: /projects
        showIcon: false
        icon: arrowRight
        iconPosition: right
        elementId: ''
    colors: colors-f
    variant: variant-b
    elementId: ''
    recentCount: 6
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    styles:
      self:
        height: screen
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 0
        borderStyle: none
        borderRadius: none
        borderColor: border-primary
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: center
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: "Got an interesting project? Tell me more...\U0001F4AC"
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
          width: 1/2
          type: EmailFormControl
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: updatesConsent
          label: Sign me up to recieve updates
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
socialImage: /images/Screenshot 2024-12-03 144453.png
metaTitle: 'Amaresh '
addTitleSuffix: false
metaTags: []
---
