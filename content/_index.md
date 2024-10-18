---
title: 'Home'
date: 2024-10-17
type: landing

design:
  # Default section spacing
  spacing: "4rem"

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: biography
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: MB-Banner2.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'

  - block: markdown
    content:
      title: 'Was bringe ich mit?'
      subtitle: ''
      text: | 
        👉 Mehrjährige Erfahrung in der Personalplanung an verschiedenen Standorten<br>
        👉 Führungskompetenz in cross-divisionalen Projekten<br>
        👉 Umfangreiches Netzwerk<br>
        👉 Sicherer Umgang mit dem Top-Management<br>
        👉 Fähigkeit, Komplexes einfach und klar darzustellen<br>
        👉 Internationale Erfahrung, z.B.: Aufbau Personalplanung in East London
  - block: experience
    content:
      title: Erfahrungen
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: skills
    content:
      title: Skills
      username: admin
  - block: markdown
    content:
      title: 'Hobbies'
      subtitle: ''
      text: |
      
       <div style ="display: flex; justify-content: space-between;">
        <img src="images/kitesurfing.png" alt="Kitesurfen" style="width: 30%;"/>
        <img src="images/diving.png" alt="Tauchen" style="width: 30%;"/>
        <img src="images/food.png" alt="Essen" style="width: 30%;"/>
       </div>
    

    
---


