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
  - block: skills
    content:
      title: Skills
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
        - title: Self employed Consultant
          company: Paracons e.U.
          company_url: ''
          company_logo: NOVA
          location: Austria
          date_start: '2022-05-01'
          date_end: ''
          description: Technical Textiles Stuff
        - title: CEO
          company: Mecsek-Ballon Kft
          company_url: ''
          company_logo: NOVA
          location: Hungary
          date_start: '2019-04-01'
          date_end: '2022-04-15'
          description: |2-
              Responsibilities include:

              * Motivating
              * Restructuring
              * Sourcing
              * Business Development
              * Tenders


        - title: Production Manager / Development / Shareholder
          company: NOVA Vertriebsges. m.b.H.
          company_url: ''
          company_logo: NOVA
          location: Austria
          date_start: '2014-04-01'
          date_end: '2023-04-30'
          description: |2-
              Responsibilities include:

              * Production Planing
              * Development of Paragliders / Parachutes
              * Supply Chain Management
              * 
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
          title: Template 
          url: ''
       
    design:
      columns: '2'
 
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
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    id: publications
    content:
      title: Publications
      text: 
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: 
      # Contact (add or remove contact options as necessary)
      email: nikolaus@kurcz.de
      phone: +43 681 20343289
      address:
        street: Grillhofweg 8
        city: Innsbruck
        region: Tirol
        postcode: '6080'
        country: Austria
        country_code: AT
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '47.236'
        longitude: '11.402'  
      contact_links:
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'skype:echo123?call'
      # Automatically link email and phone or display as text?
      autolink: true
     
    design:
      columns: '2'
---
