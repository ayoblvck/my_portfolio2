---
date: "2022-10-24"
sections:
- block: about.biography
  content:
    title: Biography
    username: admin
  id: about
- block: features
  content:
    items:
    - icon: r-project
      icon_pack: fab
      name: R
    - icon: chart-line
      icon_pack: fas
      name: Statistics
    - icon: camera-retro
      icon_pack: fas
      name: Python
    title: Skills
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: GlaxoSmithKline
      company_logo: org-gsk
      company_url: "https://www.gsk.com/"
      date_end: ""
      date_start: "2022-09-10"
      description: |2-
          Responsibilities include:

          * Analysing
          * Modelling
          * Deploying
      location: United Kingdom
      title: Statistical Data Scientist
    - date_end: ""
      date_start: "2022-09-10"
      description: |2-
          Responsibilities include:
          * Analysing
          * Modelling
          * Deploying
      location: United Kingdom
      title: Freelance Data Scientist      
    title: Experience
  design:
    columns: "2"
- block: accomplishments
  content:
    date_format: Jan 2006
    items:
    - certificate_url: https://www.credly.com/badges/1901f141-845c-4143-b33b-6b36bcb6c2af/public_url
      date_end: ""
      date_start: "2021-01-25"
      description: ""
      organization: Coursera
      organization_url: https://www.coursera.org
      title: Google Data Analytics Certificate
      url: ""
    - certificate_url: https://www.credly.com/badges/d2725022-b66a-4d80-b250-b26d9ab40714?source=linked_in_profile
      date_end: ""
      date_start: "2022-06-01"
      description: Formulated informed blockchain models, hypotheses, and use cases.
      organization: Microsoft
      organization_url: https://www.microsoft.com
      title: Microsoft Certified Azure AI Fundamentals
      url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
    subtitle: null
    title: Accomplish&shy;ments
  design:
    columns: "2"
- block: collection
  content:
    count: 5
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - post
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: ""
    text: ""
    title: Recent Posts
  design:
    columns: "2"
    view: compact
  id: posts
- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: Deep Learning
      tag: Deep Learning
    - name: Other
      tag: Demo
    default_button_index: 0
    filters:
      folders:
      - project
    title: Projects
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects
- block: markdown
  content:
    subtitle: ""
    text: '{{< gallery album="demo" >}}'
    title: Gallery
  design:
    columns: "1"
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Featured Publications
  design:
    columns: "2"
    view: card
  id: featured
- block: collection
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    text: |-
      {{% callout note %}}
      Quickly discover relevant content by [filtering publications](./publication/).
      {{% /callout %}}
    title: Recent Publications
  design:
    columns: "2"
    view: citation
- block: collection
  content:
    filters:
      folders:
      - event
    title: Recent & Upcoming Talks
  design:
    columns: "2"
    view: compact
  id: talks
- block: tag_cloud
  content:
    title: Popular Topics
  design:
    columns: "2"
- block: contact
  content:
    address:
      city: London, United Kingdom
      country: United Kingdom
      country_code: UK
    appointment_url: https://calendly.com
    autolink: true
    email: maryamsanni1@yahoo.com
    form:
      formspree:
        id: null
      netlify:
        captcha: false
      provider: netlify
    office_hours:
    - Monday 10:00 to 13:00
    - Wednesday 09:00 to 10:00
    subtitle: null
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
