---
# Leave the homepage title empty to use the site title
title: ''
date: 2024-05-14
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: Experience
    id: internships
    content:
      title: Internships
      # Date format for experience
      # Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      # Add/remove as many `experience` items below as you like.
      # Required fields are `title`, `company`, and `date_start`.
      # Leave `date_end` empty if it's your current employer.
      # Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Business Analyst Intern
          company: Publicis Groupe
          company_url: 'https://www.publicisgroupe.com/fr/splash'
          company_logo: 
          location: Shanghai
          date_start: '2024-03-19'
          date_end: ''
        - title: Data Analyst Intern
          company: Alibaba Group
          company_url: 'https://www.alibabagroup.com/'
          company_logo: 
          location: Hangzhou
          date_start: '2023-07-03'
          date_end: '2023-08-04'
        - title: Research Assistant
          company: Zhejiang Academy of Forestry
          company_url: 'https://www.zjforestry.ac.cn/'
          company_logo: 
          location: Hangzhou
          date_start: '2023-01-03'
          date_end: '2023-04-03'
        - title: Investigator
          company: Investigation Team of Domestic Sewage Treatment Facilities
          company_url: ''
          company_logo: 
          location: Hangzhou
          date_start: '2021-07-01'
          date_end: '2021-08-01'
    design:
      columns: '2'
  - block: accomplishments
    id: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplishments'
      subtitle: 
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      # Add/remove as many `item` blocks below as you like.
      # `title`, `organization`, and `date_start` are the required parameters.
      # Leave other parameters empty if not required.
      # Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: 
          date_end: ''
          date_start: '2021-11-01'
          description: ''
          icon: 
          organization: China Society for Industrial and Applied Mathematics
          organization_url: 
          title: 1<sup>st</sup> Class Prize of China Undergraduate Mathematical Contest in Modeling (CUMCM)
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2023-05-01'
          description: ''
          icon: 
          organization: Department of Education of Zhejiang Province
          organization_url: 
          title: Honorary Title of Outstanding Graduate of Zhejiang Province
          url: ''
        - certificate_url: 
          date_end: '2022-12-01'
          date_start: '2020-12-01'
          description: ''
          icon: 
          organization: Department of Education of Zhejiang Province
          organization_url: 
          title: Government Scholarship of Zhejiang Province
          url: ''
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: WHERE AM I
      email: John_Peng1127@163.com
      address:
        street: No. 688 Nanjing West Road
        city: Jing'an District
        region: Shanghai City
        country: China
      coordinates:
        latitude: '31.23'
        longitude: '121.46'  
    design:
      columns: '1'
---
