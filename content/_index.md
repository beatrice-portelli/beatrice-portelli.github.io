---
title: 'Home'
date: 2023-10-24
type: landing

# design:
  # Default section spacing
  # spacing: "4rem"
design:
  spacing: "2rem"

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:

  - block: biography
    content:
      username: beatrice-portelli
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/bportelli-cv.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: cover.jpeg
      biography:
        # Customize the style of your biography text
        style: 'font-size: 0.8em;'
        
  - block: experience
    content:
      username: beatrice-portelli
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: true
      
  - block: skills
    content:
      title: Skills & Hobbies
      username: beatrice-portelli
      
#  - block: awards
#    content:
#      title: Awards
#      username: beatrice-portelli
      
  - block: languages
    content:
      title: Languages
      username: beatrice-portelli
    
#  - block: collection
#    id: papers
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publications
#        featured_only: true
#    design:
#      view: article-grid
#      columns: 2

#  - block: collection
#    content:
#      title: Recent Publications
#      text: ""
#      filters:
#        folders:
#          - publications
#        exclude_featured: false
#    design:
#      view: citation

---

