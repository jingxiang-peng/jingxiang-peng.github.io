---
# Leave the homepage title empty to use the site title
title: ''
date: 2024-05-14
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: 自我介绍
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: portfolio
    id: projects
    content:
      title: 项目经历
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
      title: 实习经历
      # Date format for experience
      # Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: 2006年1月
      # Experiences.
      # Add/remove as many `experience` items below as you like.
      # Required fields are `title`, `company`, and `date_start`.
      # Leave `date_end` empty if it's your current employer.
      # Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: 商业分析实习生
          company: 阳狮集团
          company_url: 'https://www.publicisgroupe.com/fr/splash'
          company_logo: 
          location: 上海
          date_start: '2024-03-19'
          date_end: ''
        - title: 数据分析实习生
          company: 阿里巴巴集团
          company_url: 'https://www.alibabagroup.com/'
          company_logo: 
          location: 杭州
          date_start: '2023-07-03'
          date_end: '2023-08-04'
        - title: 科研助理
          company: 浙江省林业科学研究院
          company_url: 'https://www.zjforestry.ac.cn/'
          company_logo: 
          location: 杭州
          date_start: '2023-01-03'
          date_end: '2023-04-03'
        - title: 调查员
          company: 污水处理调查小组
          company_url: ''
          company_logo: 
          location: 杭州
          date_start: '2021-07-01'
          date_end: '2021-08-01'
    design:
      columns: '2'
  - block: accomplishments
    id: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 个人成就
      subtitle: 
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: 2006年1月
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
          organization: 中国工业与应用数学学会
          organization_url: 
          title: 全国大学生数学建模竞赛一等奖
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2023-05-01'
          description: ''
          icon: 
          organization: 浙江省教育厅
          organization_url: 
          title: 浙江省优秀毕业生
          url: ''
        - certificate_url: 
          date_end: '2022-12-01'
          date_start: '2020-12-01'
          description: ''
          icon: 
          organization: 浙江省教育厅
          organization_url: 
          title: 浙江省政府奖学金
          url: ''
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: 我在哪
      email: John_Peng1127@163.com
      address:
        street: 南京西路688号
        city: 静安区
        region: 上海市
        country: 中国
      coordinates:
        latitude: '31.23'
        longitude: '121.46'
    design:
      columns: '1'
---
