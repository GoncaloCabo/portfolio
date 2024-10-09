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
      Ola sou o Gonçalo e sou do Curso de Técnico de Gestão e Programação de
      Sistemas Informáticos
    subtitle: >-
      Estou no ultimo ano de curso e procuro ser um programador profissional no
      futuro, e este é o meu portfolio.
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
  - type: CtaSection
    title: Let's do this
    text: >-
      The Stackbit theme is flexible and scalable to every need. It can manage
      any layout and any screen.
    actions:
      - type: Button
        label: Saber Mais
        altText: ''
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
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
      - content/pages/projects/project-four.md
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
    subtitle: ''
    title: Projetos Feitos Por Mim
  - type: MediaGallerySection
    title: Algumas Linguagens em que ja trabalhei
    subtitle: ''
    images:
      - type: ImageBlock
        url: /images/Java.jpg
        altText: Java
        caption: Image one caption
        elementId: ''
      - type: ImageBlock
        url: /images/Python.png
        altText: Python
        caption: Image two caption
        elementId: ''
      - type: ImageBlock
        url: /images/C++.png
        altText: C++
        caption: Image three caption
        elementId: ''
      - type: ImageBlock
        url: /images/PHP.png
        altText: PHP
        caption: Image four caption
        elementId: ''
      - type: ImageBlock
        url: /images/HTML.png
        altText: HTML
        caption: Caption of the image
        elementId: ''
    colors: colors-f
    spacing: 24
    columns: 5
    aspectRatio: '1:1'
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
---
