---
# Leave the homepage title empty to use the site title
title: 
date: 2022-10-24
type: landing

sections:
     
  
  - block: about.biography
    id: about
    content:
      title: About me
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
  
  

    
    
    
    design:
      columns: '2'
  
        
    
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
