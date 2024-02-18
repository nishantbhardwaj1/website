---
# Leave the homepage title empty to use the site title
title: 
date: 2022-10-24
type: landing

sections:
     
  - block: ''
    content:
      title: ''
      image:
        filename: 'hero-academic.png'
      cta:
        label: '**Get Started**'
        url: https://wowchemy.com/templates/
      cta_alt:
        label: Ask a question
        url: https://discord.gg/z8wNYzb
      cta_note:
        label: >-
          <div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/wowchemy-hugo-themes" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Wowchemy Website Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/starter-hugo-academic" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
      text: ''
    design:
      background:
        gradient_end: '#3E0F0F'
        gradient_start: '#844D50'
        text_color_light: true
  - block: about.biography
    id: about
    content:
      title: About
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    content:
      title: Skills
      items:
        - name: R
          description: ''
          icon: r-project
          icon_pack: fab
        - name: GIS
          description: ''
          icon: earth-americas
          icon_pack: fas
        - name: Python
          description: ''
          icon: python
          icon_pack: fab
  
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
      - title: Project Associate-I
        company: Wildlife Institute of India
        company_url: 'https://wii.gov.in'
        company_logo: ''
        location: Dehradun, India
        date_start: '2023-09-11'
        date_end: ''
        description: |2- 
          Assessed level of human-wildlife conflict in villages adjoining Nandhaur Wildlife Sanctuary.
          Designed and conducted field surveys, camera trapping and transects in Nandhaur Landscape.
          Implemented AI and machine learning tools like Megadetector to classify camera trap images.
          Conducted focus group interviews and in consultation, with target local communities, facilitated training in a suite of feasible, economically viable livelihood opportunities for communities. 
          Conducted education and awareness program  among community members and educational institutions.
      - title: Training Coordinator
        company: International Institute of Waste Management
        company_url: 'http://www.iiwm.in'
        company_logo: ''
        location: Bangalore, India
        date_start: '2021-01-01'
        date_end: '2021-03-01'
        description: |2-
          Organized a national-level workshop for government officials (Pollution Control Board). Handled all operations and communications, including content development of the information booklet.

      - title: GIS Assistant
        company: People's Trust For Endangered Species
        company_url: 'https://ptes.org'
        company_logo: ''
        location: London, United Kingdom
        date_start: '2020-10-01'
        date_end: '2020-12-01'
        description: Digitised traditional orchards from historical maps provided by Landmark and PTES to support restoration of orchards (a priority habitat in UK's Biodiversity Action Plan). Overlayed aerial imagery to identify the status of traditional orchards 
        
      - title: Student Volunteer
        company: Natural History Society of Northumbria
        company_url: 'https://www.nhsn.org.uk'
        company_logo: ''
        location: Newcastle, United Kingdom
        date_start: '2019-10-01'
        date_end: '2020-10-01'
        description: Managed the habitat at the reserve. I dedicated several hours to practical conservation work at Gosforth Nature Reserve with tasks including tree planting at a new native 'wildwood', hide maintenance, cutting reed bed, invasive species control, and board walk maintenance.

      - title:  Research Intern
        company: Wild Otters Research
        company_url: 'https://wildotters.com'
        company_logo: ''
        location: Goa, India
        date_start: '2018-06-01'
        date_end: '2018-07-15'
        description: Conducted field surveys for Smooth-coated otters in mangroves. Identified Smooth-coated otter signs like pugmarks, defecating areas.Set up and monitored trail cameras. Used GPS and Google earth for digital mapping. Analysed and sorted content from trail camera data
        

    
    
    
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items: 
        - certificate_url: https://coursera.org/share/345f28a83fe6758416e0e9d02d93bd4d  
          date_end: ''
          date_start: '2023-01-01'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Introduction to Python Programming
          url: ''
        - certificate_url: https://coursera.org/share/aecb75e02af64aaf5ff36297f509f2ed
          date_end: ''
          date_start: '2023-01-01'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Understanding and visualising data with Python 
          url: ''
        - certificate_url: https://coursera.org/share/b25051fe32163141864db2746a562d9e
          date_end: ''
          date_start: '2019-07-01'
          description: ''
          organization: Coursera
          organization_url: https://www.Coursera.org 
          title: 'Fundamentals of GIS'
        
    
    design:
      columns: '2'
  - block: collection
    id: featured
    content:
      title: Publications
      filters:
        folders:
          - publication
        
    
    
    
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Fill the form below and I will get back to you :)
      # Contact (add or remove contact options as necessary)
      
      
      
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
