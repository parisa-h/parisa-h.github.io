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
        color: bg-light
  - block: experience
    id: experience
    content:
      title: Experience
      date_format: 'Jan 2006'
    design:
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Selected Publications
      count: 0
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: markdown
    id: awards
    content:
      title: Honors and Awards
      text: |-
        <ul class="awards-list">
        <li>JPMorgan Innovation Award, JPMorgan Chase & Co., 2022</li>
        <li>Alexander Hessel Award for the Best Ph.D. Dissertation, ECE Department, NYU, 2020</li>
        <li>Class Representative for Tandon School of Engineering at the NYU Commencement, 2019</li>
        <li>David Goodman Research Award, ECE Department, New York University, 2019</li>
        <li>Student Leader Award, WoMentorship Program, NYU, 2019</li>
        </ul>
    design:
      columns: '1'
      width: full
---
