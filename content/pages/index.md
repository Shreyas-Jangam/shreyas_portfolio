---
type: PageLayout
title: Home
colors: colors-c
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
    title: "Hi, I’m shreyas, a district\_Program Coordinator at the Shantilal Muttha Foundation, with a diverse background in Technical Consulting, Web & App Development, Digital Art, and more. I combine my passion for social impact with a broad range of skills to drive meaningful change in communities."
    subtitle: >-
      Hello! I’m excited to share a glimpse into my journey, which has been a
      mix of hard work, growth, and meaningful impact. From my time in technical
      consulting and development to my current role as Ratnagiri District
      Program Coordinator at the Shantilal Muttha Foundation, every experience
      has taught me valuable lessons. This path has been full of challenges and
      rewarding moments, and it’s shaped me into someone deeply committed to
      driving positive change through innovation and collaboration.
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
    text: >+
      <div style="text-align: center">Currently, I’m serving as the **Ratnagiri
      District Program Coordinator** at the **Shantilal Muttha Foundation**,
      where I work on creating social impact through community-driven programs.
      While my focus is now on empowering local communities and managing
      impactful initiatives, my journey has been rich in diverse experiences,
      from technical consulting to creative problem-solving.In my past work,
      I’ve built a solid foundation in **web development**, **artificial
      intelligence**, **machine learning**, and **blockchain technologies**.
      I've had the opportunity to create innovative solutions, like developing
      an image classification model using VGG16 on **Google Colab**, building a
      sentiment analysis web app, and designing a **blockchain-based transaction
      tracking system** for an NGO. These projects reflect my drive to learn,
      solve problems, and push the boundaries of what technology can do.Beyond
      the technical realm, I’ve always enjoyed blending creativity with my
      skills. From **technical blogging** to creating engaging content on social
      media, I believe that storytelling and digital art play a key role in
      connecting with people. Whether it’s through tech or creative mediums, my
      goal is to build solutions that make a difference.Looking back, this
      journey has been a thrilling mix of challenges, growth, and the constant
      pursuit of new opportunities to create value. Now, in my current role, I’m
      channeling all that knowledge and experience into driving social impact
      and community development—and I’m excited to continue this path of
      learning and impact!


      </div>

  - type: MediaGallerySection
    title: 'In Progress, Always'
    subtitle: 'Continuously learning, creating, and becoming'
    images:
      - type: ImageBlock
        url: /images/WhatsApp Image 2025-01-20 at 5.05.44 PM.jpeg
        altText: Image one
        caption: Image one caption
        elementId: ''
      - type: ImageBlock
        url: /images/new234.JPG
        altText: Image two
        caption: Image two caption
        elementId: ''
      - type: ImageBlock
        url: /images/WhatsApp Image 2025-01-20 at 5.05.44 PM (1).jpeg
        altText: Image three
        caption: Image three caption
        elementId: ''
      - type: ImageBlock
        url: /images/WhatsApp Image 2025-01-20 at 5.05.44 PM (2).jpeg
        altText: Image four
        caption: Image four caption
        elementId: ''
    colors: colors-f
    spacing: 16
    columns: 4
    aspectRatio: '4:3'
    showCaption: false
    enableHover: true
    elementId: ''
    styles:
      self:
        height: auto
        width: full
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all projects
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
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
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    subtitle: Projects
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-d
    subtitle: Featured Posts
    showFeaturedImage: false
    actions:
      - type: Link
        label: See all posts
        url: /blog
    posts:
      - content/pages/blog/post-six.md
      - content/pages/blog/post-four.md
      - content/pages/blog/post-three.md
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
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
          - pt-28
          - pb-48
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
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
metaTitle: shreyas jangam
metaDescription: shreyas jangam
socialImage: /images/WhatsApp Image 2025-01-18 at 11.58.27 PM.jpeg
metaTags:
  - type: MetaTag
    property: 'og:title'
    content: ''
---
