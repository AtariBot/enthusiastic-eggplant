---
title: Home
sections:
  - type: hero_section
    title: This is another page in our portal
    subtitle: >-
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam a metus
      quis lorem malesuada luctus.
    actions:
      - label: Learn More
        url: /features
        style: primary
      - label: Contact Us
        url: /contact
        style: secondary
    align: left
    image: images/hero.svg
    image_alt: Hero placeholder image
    image_position: right
    has_background: true
    background:
      background_color: blue
      background_image: images/diagonal-lines.svg
      background_image_opacity: 50
      background_image_size: cover
      background_image_repeat: no-repeat
  - 
    title: Ecommerce
    show_recent: true
    recent_count: 3
  - title: Logistics
    show_recent: false
    recent_count: 0
    type: blog_feed_section
  - title: Supply Chain
    show_recent: false
    recent_count: 0
    type: blog_feed_section
  - type: cta_section
    title: Looking for something else?
    subtitle: See our online help
    actions:
      - label: Learn More
        url: /features
        style: primary
    has_background: true
    background_color: gray
seo:
  title: Stackbit Starter Theme
  description: The preview of the Starter theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Stackbit Starter Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the Starter theme
      keyName: property
    - name: 'og:image'
      value: images/starter-preview.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Stackbit Starter Theme
    - name: 'twitter:description'
      value: The preview of the Starter theme
    - name: 'twitter:image'
      value: images/starter-preview.png
      relativeUrl: true
template: advanced
---