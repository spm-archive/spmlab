---
title: People
date: 2025-07-29

type: landing

sections:

  - block: hero
    id: people_banner
    content:
      title:
      text: 
      image:
        filename: team_banner.jpg
    design:
      background:
        color: "#387188"
      spacing:
        padding: ['40px', '0', '40px', '0']
         
  - block: markdown
    content:
      title:
      text: |
        <div style="text-align: center;">
          <h2 style="font-size: 1.8rem; font-weight: 700; margin-bottom: 12px;">
            Meet Our Team
          </h2>
          <p style="font-size: 1.1rem; max-width: 600px; margin: 0 auto;">
            A multidisciplinary group united by a passion for stretchable electronics.
          </p>
        </div>
    design:
      columns: '1'
      background:
        color: "#387188"
      spacing:
        padding: ['20px', '0', '40px', '0']
  
  - block: people
    content:
      title: Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Principal Investigators
          - Lab Advisors
          - Administration
          - Post Docs
          - Visitors
          - PhD Students
          - Researchers
          - Master Students
          - Alumni
          - Bachelor Students
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true
      avatar_shape: circle

  - block: markdown
    content:
      title:
      text: |
        <div style="text-align: center; margin-top: 16px;">
          <a href="../alumni/" style="
                        background: white;
                        color: #387188;
                        padding: 14px 40px;
                        border-radius: 8px;
                        text-decoration: none;
                        font-weight: 700;
                        font-size: 1rem;
                        display: inline-block;
                      ">
                        See Our Alumni →
                      </a>
        </div>
    design:
      columns: '1'
      background:
        color: "#387188"
      spacing:
        padding: ['0px', '0', '20px', '0']
---