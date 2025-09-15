---
title: ""
type: landing
date: 2022-10-24

design:
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ""
      button:
        text: CV
        url: uploads/cv_claudiamarangon_2025.pdf
    design:
      css_class: light
      background:
        color: white

  - block: markdown
    id: research
    content:
      title: "Research"
      text: |
        ### Publications
        {{< publist folder="publications" self="Claudia Marangon" showYear="true" >}}

        ### Working Papers
        {{< publist folder="working-papers" self="Claudia Marangon" showYear="false" >}}

        ### Work in Progress
        {{< wiplist folder="wip" self="Claudia Marangon" >}}
  - block: collection
    id: teaching
    content:
      title: "Teaching"
      text: |
        {{< teachlist folder="teaching" >}}
    # design:
    #   view: teachlist
    #   columns: "1"




---