---
title: "Alumni"
type: landing

sections:
  - block: slider
    content:
      slides:
        - title:
          content:
          align: center
          background:
            image:
              filename: team2025.jpg
              size: contain
              text_color_light: true
            position: center
            color: '#d6eaf5'
        - title:
          content:
          align: center
          background:
            image:
              filename: team2023.jpg
              size: contain
              text_color_light: true
            position: center
            color: '#d6eaf5'
        - title:
          content:
          align: center
          background:
            image:
              filename: team2019.jpg
              size: cover
              text_color_light: true
            position: contain
            color: '#d6eaf5'
        - title:
          content:
          align: center
          background:
            image:
              filename: team2015.jpg
              size: contain
              text_color_light: true
            position: center
            color: '#d6eaf5'
    design:
      slide_height: 500px
      is_fullscreen: false
      loop: true
      interval: 4000

  - block: markdown
    content:
      title: Our Alumni
      text: |
        <div style="text-align: center; margin-bottom: 20px;">
          Past members of the lab who have moved on to new adventures.
          <ul style="list-style: none; columns: 4; -webkit-columns: 4; column-gap: 40px; font-size: 1.1rem; color: #0e0e0fd9; line-height: 1.7; padding-left: 22px; margin: 0;">
                <li> Lucio Sgrina </li>
                <li> André Lopes </li>
                <li> Joana Pestana </li>
                <li> Laser Patterning </li>
                <li> Ana Tomé </li>
                <li> Andriy Sayuk </li>
                <li> Hugo Paisana </li>
                <li> Davide Gomes </li>
                <li> Riccardo Dessì </li>
                <li> Luis Negrão </li>
                <li> Rui Rocha </li>
                <li> Simone Maragliulo </li>
                <li> Joana Pastor </li>
                <li> João Santos </li>
                <li> Joana Rita </li>
                <li> João Santos </li>
                <li> Kevin Nunes </li>
                <li> Carlos Viegas </li>
                <li> Cristina Leal </li>
                <li> Detjon Brahimaj </li>
                <li> Daniel F. Fernandes </li>
                <li> Bruno </li>
                <li> Guilherme Costa </li>
                <li> José Carvalheiro </li>
                <li> Francisca Carvalho </li>
                <li> Alexandre Chambel </li>
                <li> Lúis Rosa </li>
                <li> João Silva </li>
                <li> João Veiga </li>
                <li> Diogo Oliveira </li>
                <li> Miguel Maranha </li>
                <li> João Vilarinho  </li>
                <li> Cristiana Ramalho </li>
                <li> Gabriel Santos  </li>
                <li> Maria Dias </li>
                <li> Abdolah Hajalilou </li>
                <li> Elahe Parvini </li>
                <li> Fabian Dias </li>
                <li> Sandra Mamede </li>
            </ul>  
        </div>

    design:
      columns: '1'

  - block: people
    content:
      title:
      user_groups:
        - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true
      avatar_shape: circle
---