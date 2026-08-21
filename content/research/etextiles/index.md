---
title: E-Textiles
date: ""
type: landing

summary: Making textiles smarter with electronics

image:
  focal_point: 'top'

tags: ["Wearable Electronics", "Smart Fabrics", "Textile Sensors"]
# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
sections:
  - block: markdown
    content:
      title: E-Textiles
      text: 
    design:
      columns: '1'
      spacing:
        padding: ['50px', '0', '0', '0']
        margin: ['0', '0', '0', '0']

  - block: markdown
    content:
      title: 
      subtitle:
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: etextiles/featured.png
          filters:
            brightness: 1
          parallax: false
          position: center
          size: actual
          text_color_light: true
      spacing:
        padding: ['300px', '0', '50px', '0']


  - block: markdown
    content:
      title: 
      text: | 
       We develop smart textile technologies that seamlessly integrate electronics into fabrics. Our research focuses on wearable sensors, conductive textiles, and healthcare applications. The objective is to create the next-generation wearable systems.
    design:
      columns: '1'
      spacing:
        padding: ['15px', '0', '0', '0']
        margin: ['0', '0', '0', '0']

#Published articles
  - block: collection
    content:
      title: 
      text: 
      count: 100
      filters:
          folders: 
            - publication
          tag: 'e-textiles'
    design:
      view: compact
      columns: '1'
---