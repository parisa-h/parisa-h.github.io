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
    design:
      background:
        color: white
  - block: experience
    id: experience
    content:
      title: Experience
      date_format: 'Jan 2006'
    design:
      columns: '1'
  - block: collection
    id: publications
    content:
      title: Selected Publications
      # filters:
      #   folders:
      #     - publication
      #   featured_only: true
    design:
      view: citation
  - block: markdown
    id: awards
    content:
      title: Honors and Awards
      text: |-
        - JPMorgan Innovation Award, JPMorgan Chase & Co., 2022
        - Alexander Hessel Award for the Best Ph.D. Dissertation, ECE Department, NYU, 2020
        - Class Representative for Tandon School of Engineering at the NYU Commencement, 2019
        - David Goodman Research Award, ECE Department, New York University, 2019
        - Student Leader Award, WoMentorship Program, NYU, 2019
    design:
      columns: '2'
---
