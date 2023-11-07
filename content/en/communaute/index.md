---
# Page title
title: Community
# Page type - we want a landing page (such as a homepage)
type: landing

# Your landing page sections - add as many different content blocks as you like
sections:
  - block: markdown
    id: banner
    content:
      title: Chair community     
    design:
      columns: '1'
      background: 
        image: 
          filename: Banner.jpg
          filters:
            brightness: 0.8
          size: cover
          position: center  
          parallax: false
          text_color_light: true
  - block: collection
    id: section-1
    content:
      title: Who are we ?
      subtitle: "We are several stakeholders united by a common goal: to create a collective dynamic leading to the implementation of more sustainable roadside maintenance practices."
      text: "**Partners involved in the project**"
       # Display content from the `content/post/` folder
      filters:
        folders:
          - partners
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose your content listing view - here we use the `showcase` view
      view: showcase
      background:
         color: 'white'
      # For the Showcase view, do you want to flip alternate rows?
      flip_alt_rows: false
---
