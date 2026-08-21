---
# Leave the homepage title empty to use the site title
title:
date: 2026-08-21
type: landing

sections:
  - block: markdown
    content:
      title:
      text: |
        <div style="width: 100vw; overflow: hidden; line-height: 0; position: relative; left: 50%; transform: translateX(-50%);">
          <video
            autoplay
            muted
            loop
            playsinline
            style="width: 100%; max-height: 100vh; object-fit: cover; display: block;"
          >
            <source src="media/lab_promo.mp4" type="video/mp4">
          </video>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['0px', '0', '0px', '0']


  # - block: slider
  #   content:
  #     slides:
  #     - title: 
  #       content:
  #       align: center
  #       background:
  #         image:
  #           filename: SmartMaterials.png
  #           size: cover
  #           text_color_light: true
  #         position: center
  #         color: '#666'
  #     - title: 
  #       content:
  #       align: center
  #       background:
  #         image:
  #           filename: FabricationTechnqiques.png
  #           size: cover
  #           text_color_light: true
  #         position: center
  #         color: '#666'
  #     - title: 
  #       content:
  #       align: center
  #       background:
  #         image:
  #           filename: applications_banner.png
  #           size: cover
  #           text_color_light: true
  #         position: center
  #         color: '#666'
  #     - title: 
  #       content:
  #       align: center
  #       background:
  #         image:
  #           filename: sustainability.png
  #           size: cover
  #           text_color_light: true
  #         position: center
  #         color: '#666'
  #   design:
  #     # Slide height is automatic unless you force a specific height (e.g. '400px')
  #     slide_height: 800px
  #     is_fullscreen: false
  #     # Automatically transition through slides?
  #     loop: true
  #     # Duration of transition between slides (in ms)
  #     interval: 3000 
  
#ERC Funding
  - block: markdown
    id: simple-cta
    content:
      title:
      text: |
        <div style="display: flex; align-items: center; justify-content: center; max-width: 900px; margin: 0 auto; padding: 50px 40px; gap: 60px;">
          <div style="flex: 0 0 auto;">
            <img
              src="media/erc_logo.png"
              alt="ERC Logo"
              style="
                height: 120px;
                width: auto;
                display: block;
              "
            />
          </div>
          <div style="text-align: left;">
            <p style="font-size: 1.1rem; color: rgba(255,255,255,0.85); margin-bottom: 32px; line-height: 1.7;">
              The SPM lab is funded by ERC Project Liquid 3D
            </p>
            <a href="./liquid/" style="
              background: white;
              color: #387188;
              padding: 12px 36px;
              border-radius: 8px;
              text-decoration: none;
              font-weight: 700;
              font-size: 1rem;
              display: inline-block;
              transition: opacity 0.2s ease;
            ">
              Learn More
            </a>
          </div>
        </div>
    design:
      columns: '1'
      background:
        color: "#387188"
        text_color_light: true
      spacing:
        padding: ['0px', '0', '0px', '0']
  
 #Featured articles
  - block: collection
    content:
      title: Featured Articles
      text: 
      count: 6
      filters:
        folders:
          - publication
        tag: 'featured'
        
    design:
      view: article-grid
      columns: '1'


#Multidisciplinary Team
  - block: markdown
    id: team_banner
    content:
      title:
      text: |
        <div style="display: flex; flex-wrap: wrap; align-items: center; max-width: 1200px; margin: 0 auto; padding: 40px 20px; gap: 40px;">
          <div style="flex: 1 1 300px; min-width: 0;">
            <img
              src="media/team_banner.jpg"
              alt="Our Team"
              style="
                width: 100%;
                height: auto;
                object-fit: cover;
                object-position: center center;
                border-radius: 12px;
                box-shadow: 0 8px 32px rgba(0,0,0,0.25);
                display: block;
              "
            />
          </div>
          <div style="flex: 1 1 250px; min-width: 0; text-align: left;">
            <h2 style="font-size: 2rem; font-weight: 700; color: white; margin-bottom: 16px; line-height: 1.2;">
              A Multidisciplinary Team
            </h2>
            <p style="font-size: 1.1rem; color: rgba(255,255,255,0.85); margin-bottom: 32px; line-height: 1.7;">
              Our lab brings together experts from electrical engineering, biomedical engineering, engineering physics and chemical engineering — united by a passion for stretchable electronics.
            </p>
            <a href="./people/" style="
              background: white;
              color: #387188;
              padding: 14px 40px;
              border-radius: 8px;
              text-decoration: none;
              font-weight: 700;
              font-size: 1rem;
              display: inline-block;
            ">
              Meet the team →
            </a>
          </div>
        </div>
    design:
      columns: '1'
      background:
        color: "#387188"
      spacing:
        padding: ['0px', '0', '0px', '0']

 #Latest News section
  - block: collection
    content:
      title: Latest News 
      subtitle:
      text: 
      count: 4
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: news-grid
      columns: '1'
      background:
        color: "#d6eaf5"
      spacing:
        padding: ['60px', '0', '10px', '0']

# Accent Banner
  - block: markdown
    content:
      title:
      text: |
        <div style="
          padding: 50px 40px;
          background-color: #d6eaf5;
          background-image: radial-gradient(circle, #EF7B45 1.5px, transparent 1px);
          background-size: 24px 24px;
        ">
          <div style="
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 0;
            max-width: 900px;
            margin: 0 auto;
            flex-wrap: wrap;
          ">
            <div style="flex: 1; min-width: 160px; text-align: center; padding: 10px 20px; border-right: 2px solid #387188;">
              <p style="font-size: 2.4rem; font-weight: 800; color: #196a98; margin: 0; line-height: 1;">27</p>
              <p style="font-size: 0.9rem; font-weight: 500; color: #387188; margin: 8px 0 0 0; text-transform: uppercase; letter-spacing: 0.08em;">Team Members</p>
            </div>
            <div style="flex: 1; min-width: 160px; text-align: center; padding: 10px 20px; border-right: 2px solid #387188;">
              <p style="font-size: 2.4rem; font-weight: 800; color: #196a98; margin: 0; line-height: 1;">80+</p>
              <p style="font-size: 0.9rem; font-weight: 500; color: #387188; margin: 8px 0 0 0; text-transform: uppercase; letter-spacing: 0.08em;">Publications</p>
            </div>
            <div style="flex: 1; min-width: 160px; text-align: center; padding: 10px 20px; border-right: 2px solid #387188;">
              <p style="font-size: 2.4rem; font-weight: 800; color: #196a98; margin: 0; line-height: 1;">5M€</p>
              <p style="font-size: 0.9rem; font-weight: 500; color: #387188; margin: 8px 0 0 0; text-transform: uppercase; letter-spacing: 0.08em;">Funds since 2020</p>
            </div>
            <div style="flex: 1; min-width: 160px; text-align: center; padding: 10px 20px;">
              <p style="font-size: 2.4rem; font-weight: 800; color: #196a98; margin: 0; line-height: 1;">2016</p>
              <p style="font-size: 0.9rem; font-weight: 500; color: #387188; margin: 8px 0 0 0; text-transform: uppercase; letter-spacing: 0.08em;">Founded</p>
            </div>
          </div>
        </div>
    design:
      columns: '1'
      background:
        color: "#d6eaf5"
      spacing:
        padding: ['0px', '0', '0px', '0']


#Research Areas Section
  - block: portfolio
    id: research
    content:
      title: Research Areas
      text: |
       <div style="text-align: center; margin: 0px 0;">
       Stretchable electronics is a multidisciplinary field, and we tackle different problems. Find out more about our research areas.
       </div> 
      filters:
        folders:
          - research
      default_button_index: 0
      buttons:
        - name: All
          tag: '*'
    design:
      columns: '1'
      view: research-grid
      background:
        color: "#d6eaf5"
      spacing:
        padding: ['60px', '0', '10px', '0']
 

  #Published articles
  - block: collection
    content:
      title: Latest Published Articles
      text: 
      count: 3
      filters:
        folders:
          - publication
        
        
    design:
      view: compact
      columns: '1'
    #featured in banner  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        <div style="text-align: center; margin: 0px 0;">
          <p style="font-size: 1.2rem; margin-bottom: 0px;">
            Featured In
          </p>
          </div>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['0px', '0', '0', '0']
        margin: ['0', '0', '0', '0']
      background:
        color: #ffffff   
  - block: markdown
    content:
      title:
      subtitle:
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: featured_banner.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: actual
          text_color_light: true
      spacing:
        padding: ['90px', '0', '50px', '0']

#Banner meet team and instagram
  - block: markdown
    content:
      title:
      subtitle: 
      text: |
        <div style="text-align: center; margin: 40px 0;">
            <a href="./people/" style="background: transparent; color: white; padding: 15px 40px; border-radius: 8px; text-decoration: none; font-weight: 700; font-size: 1.1rem; border: 2px solid white; transition: background 0.3s ease;">
              Meet the team
            </a>
        </div>
        <div>
        <center>            
            <a href="https://www.instagram.com/softprintedmicro/" style="background: transparent; color: white; padding: 15px 40px; border-radius: 8px; text-decoration: none; font-weight: 700; font-size: 1.1rem; border: 2px solid white; transition: background 0.3s ease;">
              Follow us on Instagram 📸: @️softprintedmicro
            </a>
        </center>
        <br>        
        <center>#StretchableElectronics &nbsp; #PrintedElectronics  &nbsp; #LiquidMetals  &nbsp; #ElectronicTattoos &nbsp; #PressureMappingFilms  &nbsp; #SmartTextiles</center>
        </div>
    design:
      columns: '1'
      background:
        color: "#387188" #"#EF7B45" 
        gradient_angle: 45
        text_color_light: true
    spacing:
        padding: ['0px', '0', '0px', '0']

---
