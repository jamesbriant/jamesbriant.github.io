---
# Leave the homepage title empty to use the site title
title: James Briant
date: 2023-08-01
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
 # - block: features
 #   content:
 #     title: Skills
 #     items:
 #       - name: R
 #         description: 90%
 #         icon: r-project
 #         icon_pack: fab
 #       - name: Statistics
 #         description: 100%
 #         icon: chart-line
 #         icon_pack: fas
 #       - name: Photography
 #         description: 10%
 #         icon: camera-retro
 #         icon_pack: fas
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Calibration
          tag: Calibration
        - name: Weather
          tag: Weather
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true
  # - block: accomplishments
  #   content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: 'Accomplish&shy;ments'
  #     subtitle:
  #     # Date format: https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - certificate_url: https://www.coursera.org
  #         date_end: ''
  #         date_start: '2021-01-25'
  #         description: ''
  #         organization: Coursera
  #         organization_url: https://www.coursera.org
  #         title: Neural Networks and Deep Learning
  #         url: ''
  #       - certificate_url: https://www.edx.org
  #         date_end: ''
  #         date_start: '2021-01-01'
  #         description: Formulated informed blockchain models, hypotheses, and use cases.
  #         organization: edX
  #         organization_url: https://www.edx.org
  #         title: Blockchain Fundamentals
  #         url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #       - certificate_url: https://www.datacamp.com
  #         date_end: '2020-12-21'
  #         date_start: '2020-07-01'
  #         description: ''
  #         organization: DataCamp
  #         organization_url: https://www.datacamp.com
  #         title: 'Object-Oriented Programming in R'
  #         url: ''
  #   design:
  #     columns: '2'
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: |-
  #       {{% callout note %}}
  #       Quickly discover relevant content by [filtering publications](./publication/).
  #       {{% /callout %}}
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: true
  #   design:
  #     columns: '2'
  #     view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      count: 0 # 0 = all pages
      filters:
        folders:
          - event
        author: ""
        category: ""
        tag: ""
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      sort_by: 'Date'
      sort_ascending: false
    design:
      columns: '1'
      view: compact
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Data Detectives Ambassador
          company: UCL - Department of Statistical Science
          company_url: 'https://www.ucl.ac.uk/statistics/data-detectives'
          company_logo: University_College_London_logo
          location: London, UK
          date_start: '2023-07-03'
          date_end: '2023-07-07'
          description: |2-
              * Facilitated week-long workshop introducing A-level students to R and RStudio.
              * Discussed university life and promoted academia through my experiences.
        - title: Journal Club Officer
          company: UCL - AI Society
          company_url: 'https://uclaisociety.co.uk'
          company_logo: ai_soc_logo
          location: London, UK
          date_start: '2021-10-01'
          date_end: '2023-05-30'
          description: |2-
              * Organised a journal club within UCL's student run AI society.
              * Hosted internationally recognised researchers including Prof. Marc Deisenroth (UCL), Prof. Andrew Davison (Imperial) and Dr. Raphael Köster (DeepMind).
              * Assisted with organising [ClimateHack.ai](https://climatehack.ai) in Spring 2022, the inaugural student-run climate themed hackathon.
        - title: Research Assistant
          company: University of Nottingham - School of Mathematical Sciences
          company_url: 'https://www.nottingham.ac.uk/mathematics/'
          company_logo: nottingham-logo
          location: Nottingham, UK
          date_start: '2020-07-01'
          date_end: '2020-08-25'
          description: |2-
              * Used Bayesian non-parametric models to estimate poverty in Dar es Salaam, Tanzania.
              * Contributed towards [R package BSBT](github.com/rowlandseymour/BSBT) available on CRAN.
              * Developed efficient algorithms incorporating the Bradley-Terry model to allow for rapid simulations using large volumes of data.
        - title: Machine Intelligence & Robotics Global Summer School
          company: Shanghai Jiao Tong University
          company_url: 'https://global.sjtu.edu.cn/en/studyatSJTU/session/394'
          company_logo: sjtu
          location: Shanghai, China
          date_start: '2019-07-11'
          date_end: '2019-08-02'
          description: |2-
              * Attended 3-week summer programme which introduced theories and methods in AI and machine learning.
              * Travelled around Shanghai exploring the culture, food and history.
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Please get in touch!
      # Contact (add or remove contact options as necessary)
      email: james[dot]briant[dot]21[at]ucl[dot]ac[dot]uk
      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      # address:
      #   street: 450 Serra Mall
      #   city: Stanford
      #   region: CA
      #   postcode: '94305'
      #   country: United States
      #   country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # contact_links:
      #   - icon: twitter
      #     icon_pack: fab
      #     name: DM Me
      #     link: 'https://twitter.com/Twitter'
      #   - icon: skype
      #     icon_pack: fab
      #     name: Skype Me
      #     link: 'skype:echo123?call'
      #   - icon: video
      #     icon_pack: fas
      #     name: Zoom Me
      #     link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: true
    design:
      columns: '2'
---
