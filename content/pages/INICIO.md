---
type: PageLayout
title: INICIO
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: A team that works closely together
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: Section subtitle
    text: "<h1>PITATTOO FEST</h1>\n<h2>Segunda edición · 2025</h2>\n\n<p>La convención internacional de tatuajes más importante del sur colombiano vuelve recargada. Tres días de arte, cultura, tinta y comunidad en un solo lugar.</p>\n\n<p>\U0001F4C5 31 de octubre, 1 y 2 de noviembre de 2025\n\U0001F4CD Integración – Pitalito, Huila</p>\n\n<p>Más de 100 artistas invitados nacionales e internacionales.\nCompeticiones en múltiples categorías y gran premio al mejor del evento.\nZona espiritual, shows en vivo, stands de marcas, gastronomía y mucho más.</p>\n\n<div style=\"margin-top: 1rem; display: flex; gap: 1rem; flex-wrap: wrap;\">\n  <a href=\"#entradas\" style=\"background-color: black; color: white; padding: 0.75rem 1.5rem; border-radius: 6px; text-decoration: none;\">Comprar entrada</a>\n  <a href=\"#artistas\" style=\"background-color: #222; color: white; padding: 0.75rem 1.5rem; border-radius: 6px; text-decoration: none;\">Participar como artista</a>\n  <a href=\"#stands\" style=\"background-color: #444; color: white; padding: 0.75rem 1.5rem; border-radius: 6px; text-decoration: none;\">Reservar un stand</a>\n</div>\n\n"
    actions:
      - type: Button
        label: See open positions
        url: /
        icon: arrowRight
        iconPosition: right
        style: primary
    colors: bg-neutral-fg-dark
    backgroundImage:
      type: BackgroundImage
      url: /images/abstract-background.svg
      altText: Placeholder image
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
    styles:
      self:
        padding:
          - pt-40
          - pl-4
          - pb-40
          - pr-4
        alignItems: center
        flexDirection: row-reverse
        justifyContent: center
      text:
        textAlign: center
      subtitle:
        textAlign: center
  - type: FeaturedPeopleSection
    title:
      type: TitleBlock
      text: Meet the team
      color: text-dark
      styles:
        self:
          textAlign: center
    people:
      - content/data/person1.json
      - content/data/person2.json
      - content/data/person3.json
      - content/data/person4.json
      - content/data/person5.json
      - content/data/person6.json
    actions: []
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: Open positions
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: Subtitle goes here
    items:
      - type: FeaturedItem
        title: Account Executive
        subtitle: Sales
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
      - type: FeaturedItem
        title: Open Source Engineer
        subtitle: Marketing
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
      - type: FeaturedItem
        title: Senior Software Engineer
        subtitle: Engineering
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
    actions:
      - type: Button
        label: Apply now
        url: /
        icon: arrowRight
        iconPosition: right
        style: primary
    variant: toggle-list
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pb-40
          - pt-16
          - pl-3
          - pr-3
        justifyContent: center
      subtitle:
        textAlign: center
slug: INICIO
seo:
  type: Seo
  metaTitle: Careers - Demo site
  metaDescription: This is the careers page built with Netlify.
  metaTags: []
---
