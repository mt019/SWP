---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:

    # design:
    #   background:
    #     gradient_end: '#9A87FA'
    #     gradient_start: '#4E65E6'
    #     text_color_light: true
  - block: about.biography
    id: about
    content:
      title: 關於本所
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin


  - block: features
    content:
      title: 服務項目
      items:
        - name: 訴訟
          description: 出庭辯護
          icon: scale-balanced
          icon_pack: fas
        - name: 調解
          description: 解決紛爭
          icon: handshake
          icon_pack: fas
        - name: 顧問
          description: 契約審擬
          icon: file-contract
          icon_pack: fas


  # - block: experience
  #   content:
  #     title: Experience
  #     # Date format for experience
  #     #   Refer to https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Experiences.
  #     #   Add/remove as many `experience` items below as you like.
  #     #   Required fields are `title`, `company`, and `date_start`.
  #     #   Leave `date_end` empty if it's your current employer.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - title: CEO
  #         company: GenCoin
  #         company_url: ''
  #         company_logo: org-gc
  #         location: California
  #         date_start: '2021-01-01'
  #         date_end: ''
  #         description: |2-
  #             Responsibilities include:

  #             * Analysing
  #             * Modelling
  #             * Deploying
  #       - title: Professor of Semiconductor Physics
  #         company: University X
  #         company_url: ''
  #         company_logo: org-x
  #         location: California
  #         date_start: '2016-01-01'
  #         date_end: '2020-12-31'
  #         description: Taught electronic engineering and researched semiconductor physics.
  #   design:
  #     columns: '2'
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
  - block: collection
    id: posts
    content:
      title: 最新消息
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
  # - block: portfolio
  #   # id: projects
  #   # content:
  #   #   title: Projects
  #   #   filters:
  #   #     folders:
  #   #       - project
  #     # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #     default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      # buttons:
      #   - name: All
      #     tag: '*'
      #   - name: Deep Learning
      #     tag: Deep Learning
      #   - name: Other
      #     tag: Demo
    # design:
    #   # Choose how many columns the section has. Valid values: '1' or '2'.
    #   columns: '1'
    #   view: showcase
    #   # For Showcase view, flip alternate rows?
    #   flip_alt_rows: false
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
  
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
  - block: tag_cloud
    content:
      title: 專業領域
    design:
      columns: '2'



  - block: contact
    id: contact
    content:
      title: 聯絡資訊
      subtitle:
      text: |-
        法律諮詢採付費制，不提供任何形式的免費諮詢服務。
      # Contact (add or remove contact options as necessary)
      contact_links:

      # email: test@example.org
      phone: 02 2311 6690 （汪小姐）
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'

      contact_links:

        - icon: map-location-dot
          icon_pack: fas
          name: 106 台北市大安區 仁愛路四段31號8樓之2
          link: https://goo.gl/maps/L8MyGnNMxsnAgziP7

      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
    #   form:
    #     provider: netlify
    #     formspree:
    #       id:
    #     netlify:
    #       # Enable CAPTCHA challenge to reduce spam?
    #       captcha: false
    # design:
    #   columns: '2'

  - block: hero
    content:
  #     title: 薛維平律師事務所
      # image:
      #   filename: hero-academic.png
      # cta:
      #   label: '**Get Started**'
      #   url: https://wowchemy.com/templates/
      # cta_alt:
      #   label: Ask a question
      #   url: https://discord.gg/z8wNYzb
      cta_note:
        label: >-
          <div align="center"><iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3614.877228057775!2d121.5455719!3d25.038240200000004!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3442ab803a5f67e3%3A0xf1f2ce7d04ba913a!2z6Jab57at5bmz5b6L5bir5LqL5YuZ5omA!5e0!3m2!1szh-TW!2stw!4v1690955923023!5m2!1szh-TW!2stw" width=100% height="400" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe></div>    
---

