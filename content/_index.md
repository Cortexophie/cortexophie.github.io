---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
      # design:
      # background:
      #   gradient_end: '#1976d2'
      #   gradient_start: '#004ba0'
      #   text_color_light: true
  - block: about.biography
    id: about
    content:
      title: About me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: skills
    content:
      title: My interests
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Adjunct Lecturer
          company: University of Akureyri
          company_url: 'https://www.unak.is/english/'
          company_logo: unak
          location: Iceland
          date_start: '2024-08-01'
          date_end: '2024-12-30'
          description: Teaching Sensation and Perception
      
        - title: Adjunct Lecturer
          company: University of Akureyri
          company_url: 'https://www.unak.is/english/'
          company_logo: unak
          location: Iceland
          date_start: '2024-01-08'
          date_end: '2024-05-31'
          description: Taught Cognitive Psychology

        - title: Researcher
          company: Icelandic Vision Lab
          company_url: 'https://visionlab.is/'
          company_logo: ivl
          location: Iceland
          date_start: '2021-09-01'
          date_end: '2023-10-08'
          description: Researched attentional control settings
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.coursera.org
          date_end: ''
          date_start: '2021-01-25'
          description: ''
          icon: coursera
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Neural Networks and Deep Learning
          url: ''
        - certificate_url: https://www.edx.org
          date_end: ''
          date_start: '2021-01-01'
          description: Formulated informed blockchain models, hypotheses, and use cases.
          icon: edx
          organization: edX
          organization_url: https://www.edx.org
          title: Blockchain Fundamentals
          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        - certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          icon: datacamp
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'Object-Oriented Programming in R'
          url: ''
    design:
      columns: '2'
  
  - block: collection
    content:
      title: Recent Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
      
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event/ETRA
    design:
      columns: '2'
      view: compact
  - block: tag_cloud
    content:
      title: Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Feel free to reach out to me using any of the options below.
      # Contact (add or remove contact options as necessary)
      # # Choose a map provider in `params.yaml` to show a map from these coordinates
      # coordinates:
      #   latitude: '64.1282'
      #   longitude: '-21.8277'  
      contact_links:
        - icon: envelope
          icon_pack: fas
          name: email me
          link: 'mailto:krasov.sofia@gmail.com'
        - icon: facebook
          icon_pack: fab
          name: Shoot me a DM
          link: 'https://www.facebook.com/sofia.krasovskaya.1/'
        - icon: bluesky
          icon_pack: fab
          name: Follow me on bsky
          link: 'https://bsky.app/profile/cortexophie.bsky.social'

      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
