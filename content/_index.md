---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing 
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Goal'
      subtitle: ''
      text: |-
        I am committed to becoming a proficient data scientist, specializing in data processing and machine learning. My objective is to leverage the power of data to extract meaningful insights, develop innovative solutions, and drive impactful advancements across diverse industries.With a strong foundation in analytical methodologies and programming, I am focused on exploring the transformative potential of machine learning and artificial intelligence in optimizing processes, enhancing decision-making, and solving complex challenges.
    
        I continuously strive to expand my knowledge and refine my expertise to excel in the evolving field of data science.
        
        I welcome opportunities for collaboration to push the boundaries of innovation and create meaningful impact.
    design:
      columns: '1'
 
 
  - block: collection
    id: talks
    content:
      title: Certificate
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1

  - block: markdown
    id: papers
    content:
      title: contact me
      text: |-
        You can reach me out here
    
          email: parvinsultana@gmail.com    
          phone:017****66    
          facebook: https://www.facebook.com/faria.sultana.18041
          LinkedIn: https://www.linkedin.com/
          GitHub: https://github.com/Ananya394
    
    design:     
      columns: 1
  
---
