---
# Leave the homepage title empty to use the site title
title: Shin Fujieda
date: 2022-12-28
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: experience
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
        - title: Sr. Software Development Engineer
          company: AMD
          company_url: 'https://www.amd.com/'
          location: Tokyo, Japan
          date_start: '2019-08-01'
          date_end: ''
          description: Develop a GPU global illumination renderer called Radeon ProRender.
        - title: Data Scientist
          company: IBM
          company_url: ''
          location: Tokyo, Japan
          date_start: '2018-04-01'
          date_end: '2019-07-31'
          description: Created solutions for image processing tasks with machine learning techniques.
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
        - name: Computer Graphics
          tag: CG
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
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
      email: Shin.Fujieda@amd.com
      phone:
      appointment_url:
      address:
        street: Marunouchi Trust Tower Main Bldg 10F, 1-8-3 Marunouchi
        city: Chiyoda-ku
        region: Tokyo
        postcode: '100-0005'
        country: Japan
        country_code: JPN
      directions:
      office_hours:
      contact_links:
        - icon: linkedin
          icon_pack: fab
          name: Message Me
          link: 'https://www.linkedin.com/in/sfujieda/'
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/shinel_fj'
      # Automatically link email and phone or display as text?
      autolink: true
      coordinates:
        latitude: '35.6826'
        longitude: '139.7694'
    design:
      columns: '2'
---
