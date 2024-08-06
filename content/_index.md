---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

#  - block: tag_cloud
#    content:
#      title: Educational and professional goals
#    design:
#      columns: '2'

  - block: experience
    id: posts
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
      
# 1 UNFPA LACRO
        - title: International Consultant
          company: United Nations Population Fund (UNFPA), Latin America & the Caribbean  Regional Office
          company_url: 'https://lac.unfpa.org/es'
          company_logo: UNFPA
          location: Panama (PAN)
          date_start: '2024-05-03'
          date_end: ''
          description: |2-
              Measurement of harmful practices in indigenous populations in Latin populations in Latin American countries.

# 2 DANE ADVISOR
        - title: Direction Advisor
          company: Departamento Administrativo Nacional de Estadística        (NSO Colombia)
          company_url: 'https://www.dane.gov.co/'
          company_logo: DANE
          location: Bogotá (COL)
          date_start: '2022-12-01'
          date_end: '2023-08-20'
          description: |2- 
              Coordinate the Internal Working Group on Poverty (Monetary Poverty and Multidimensional Poverty Index) and the Internal Working Group on SDGs (Sustainable Development Goals).

# 3 UNFPA COLOMBIA
        - title: Demographer
          company: United Nations Population Fund (UNFPA), Colombia
          company_url: 'https://colombia.unfpa.org/es'
          company_logo: UNFPA
          location: Bogotá (COL)
          date_start: '2018-04-01'
          date_end: '2022-12-01'
          description: |2-
              Advise the production and analysis of socio-demographic data in the framework for SDGs and CMPD agendas at national and territorial level. Support the development of information with a gender approach and differential approach like, ethnic, geographic, disability and life course.

# 4 DANE DEMOGRAP
        - title: Demographer
          company: Departamento Administrativo Nacional de Estadística (NSO Colombia)
          company_url: 'https://www.dane.gov.co/'
          company_logo: DANE
          location: Bogotá (COL)
          date_start: '2014-08-01'
          date_end: '2018-03-01'
          description: |2- 
              Formulate the methodology for monitoring of the components of population change. Advice for the statistical use of admin records to strengthen demographic estimations.

# 5 INED
        - title: Research practices
          company: Institut national d'études démographiques (Ined)
          company_url: 'https://www.ined.fr/en/'
          company_logo: INED
          location: Paris (FRA)
          date_start: '2013-11-01'
          date_end: '2014-07-01'
          description: |2- 
              Demographic analysis of population with multiple residences. Optimization on expansion factors in french surveys.
    design:
      columns: '2'

  - block: contact
    id: projects
    content:
      title: CAnD3 learning goals
      subtitle:
      text: |-
        I am a fellow of the Consortium on Analytics for Data-Driven Decision Making (CAnD3 https://www.mcgill.ca/cand3/) which focuses on developing population analysis in an aging society, to support evidence-based decision making. The objectives set and achieved during the development of this training were:
        
        1. To become more skilled in using Python because I know that it has options that could help me in my work as a research assistant at the university.
        2. To explore new packages that I have never used before in R or Python that could be useful for me to do as a researcher, such as Markdown
        3.	To further develop the habit of using forums and web pages where doubts regarding the use of software such as R and Python are resolved, supported, and also contributed on my behalf.
        4. To become more skilled in my speech, specifically, I tend to extend my arguments and not be concrete in my ideas.
        5. To integrate more complex geographic maps into my academic developments that help me justify my arguments and ideas.
        6. To further develop my understanding of DAG schemes so I can integrate it into the writing of my thesis work and the preparation of presentations, among others.


#  - block: accomplishments
#    content:
#      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
#      title: 'Accomplish&shy;ments'
#      subtitle:
#      # Date format: https://docs.hugoblox.com/customization/#date-format
#      date_format: Jan 2006
#      # Accomplishments.
#      #   Add/remove as many `item` blocks below as you like.
#      #   `title`, `organization`, and `date_start` are the required parameters.
#      #   Leave other parameters empty if not required.
#      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
#      items:
#        - certificate_url: https://www.coursera.org
#          date_end: ''
#          date_start: '2021-01-25'
#          description: ''
#          icon: coursera
#          organization: Coursera
#          organization_url: https://www.coursera.org
#          title: Neural Networks and Deep Learning
#          url: ''
#        - certificate_url: https://www.edx.org
#          date_end: ''
#          date_start: '2021-01-01'
#          description: Formulated informed blockchain models, hypotheses, and use cases.
#          icon: edx
#          organization: edX
#          organization_url: https://www.edx.org
#          title: Blockchain Fundamentals
#          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamental#s
#        - certificate_url: https://www.datacamp.com
#          date_end: '2020-12-21'
#          date_start: '2020-07-01'
#          description: ''
#          icon: datacamp
#          organization: DataCamp
#          organization_url: https://www.datacamp.com
#          title: 'Object-Oriented Programming in R'
#          url: ''
#    design:
#      columns: '1'
  - block: collection
    id: talks
    content:
      title: CAnD3 artifacts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
#  - block: portfolio
#    id: projects
#    content:
#      title: Projects
#      filters:
#        folders:
#          - project
#      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
#      default_button_index: 0
#      # Filter toolbar (optional).
#      # Add or remove as many filters (`filter_button` instances) as you like.
#      # To show all items, set `tag` to "*".
#      # To filter by a specific tag, set `tag` to an existing tag name.
#      # To remove the toolbar, delete the entire `filter_button` block.
#      buttons:
#        - name: All
#          tag: '*'
#        - name: Public sector
#          tag: Public sector
#        - name: United Nations
#          tag: United Nations
#    design:
#      # Choose how many columns the section has. Valid values: '1' or '2'.
#      columns: '1'
#      view: showcase
#      # For Showcase view, flip alternate rows?
#      flip_alt_rows: false
#  - block: markdown
#    content:
#      title: Gallery
#      subtitle: ''
#      text: |-
#        {{< gallery album="demo" >}}
#    design:
#      columns: '1'
#  - block: collection
#    id: featured
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publication
#        featured_only: true
#    design:
#      columns: '2'
#      view: card
#  - block: collection
#    content:
#      title: Recent Publications
#      text: |-
#        {{% callout note %}}
#        Quickly discover relevant content by [filtering publications](./publication/).
#        {{% /callout %}}
#      filters:
#        folders:
#          - publication
#        exclude_featured: true
#    design:
#      columns: '2'
#      view: citation
#  - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - event
#    design:
#      columns: '2'
#      view: compact
#  - block: tag_cloud
#    content:
#      title: Popular Topics
#    design:
#      columns: '2'

  - block: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'


  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: 
      # Contact (add or remove contact options as necessary)
      email: carlos.arturo.ramirez.hernandez@umontreal.ca
      phone: +1 (438) 5290394
#      appointment_url: 'https://calendly.com'
      address:
        street: 3150, rue Jean-Brillant
        city: Montréal
        region: QC
        postcode: 'H3T 1N8'
        country: Canada
        country_code: CA
      directions: Pavillon Lionel-Groulx, Office C-5037 on Floor 5
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '45.49917528205894'
        longitude: '-73.6183511451161'  
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: CARAMIREZHER
          link: 'https://twitter.com/CARAMIREZHER'
#        - icon: skype
#          icon_pack: fab
#          name: Skype Me
#          link: 'skype:echo123?call'
#        - icon: video
#          icon_pack: fas
#          name: Zoom Me
#          link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'


---
