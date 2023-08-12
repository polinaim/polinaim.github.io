---
date: "2022-10-24"
sections:
- block: about.biography
  content:
    title: Biography
    username: admin
  id: about
#- block: features
#  content:
#    items:
#    - description: 90%
#      icon: r-project
#      icon_pack: fab
#      name: R
#    - description: 100%
#      icon: chart-line
#      icon_pack: fas
#      name: Statistics
#    - description: 10%
#      icon: camera-retro
#      icon_pack: fas
#      name: Photography
#    title: Skills
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: RSIP Vision
      company_logo: rsip
      company_url: "https://www.rsipvision.com/"
      date_end: ""
      date_start: "2020-01-01"
      description: |2-
          Analyzing clinical records and medical images with the purpose of creating statistical data and develop solutions utilizing deep learning for image processing.
      location: Remote
      title: Project lead/Data analyst
      
    - company: The Norwegian University of Science and Technology (NTNU)
      company_logo: ntnu
      company_url: "https://www.ntnu.edu/"
      date_end: "2023-06-08"
      date_start: "2022-02-01"
      description: |2-
           Conducted in vitro work utilizing various techniques (ICC, viral transfections, calcium imaging and optogenetics) on micro-scale engineered platforms for investigating neural network development and plasticity.
      location: Norway
      title: Research assistant
      
    - company: Bar Ilan university
      company_logo: Bar_Ilan_seal
      company_url: "https://gondabrain.biu.ac.il/en"
      date_end: "2021-01-08"
      date_start: "2018-08-01"
      description: |2-
           Administration of clinical neuropsychological testing to gather data from various research experiments conducted in the MEG neuroimaging unit and performing physiological and behavioral analysis of the collected data.
      location: Israel
      title: Research assistant
      
    title: Experience
  design:
    columns: "2"
#- block: accomplishments
#  content:
#    date_format: Jan 2006
#    items:
#    - certificate_url: https://www.coursera.org
#      date_end: ""
#      date_start: "2021-01-25"
#      description: ""
#      organization: Coursera
#      organization_url: https://www.coursera.org
#      title: Neural Networks and Deep Learning
#      url: ""
#    - certificate_url: https://www.edx.org
#      date_end: ""
#      date_start: "2021-01-01"
#      description: Formulated informed blockchain models, hypotheses, and use cases.
#      organization: edX
#      organization_url: https://www.edx.org
#      title: Blockchain Fundamentals
#      url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
#    - certificate_url: https://www.datacamp.com
#      date_end: "2020-12-21"
#      date_start: "2020-07-01"
#      description: ""
#      organization: DataCamp
#      organization_url: https://www.datacamp.com
#      title: Object-Oriented Programming in R
#      url: ""
#    subtitle: null
#    title: Accomplish&shy;ments
#  design:
#    columns: "2"

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
#- block: markdown
#  content:
#    subtitle: ""
#    text: '{{< gallery album="demo" >}}'
#    title: Gallery
#  design:
#    columns: "1"
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
#- block: collection
#  content:
#    filters:
#      folders:
#      - event
#    title: Recent & Upcoming Talks
#  design:
#    columns: "2"
#    view: compact
#  id: talks
- block: tag_cloud
  content:
    title: Tags
  design:
    columns: "2"
- block: contact
  content:
    address:
      city: Paris
      country: France
      country_code: FR
      postcode: "75012"
      region: 
      street: 17 rue Moreau
    appointment_url: https://calendly.com
    autolink: true
    contact_links:
    directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
    email: polinama@stud.ntnu.no
    
    form:
      formspree:
        id: null
      netlify:
        captcha: false
      provider: netlify
    subtitle: null
    text: 
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
