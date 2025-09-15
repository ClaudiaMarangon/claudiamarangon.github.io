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
      spacing:
        padding: ["2rem", "0", "2rem", "0"]   # top, right, bottom, left
      background:
        color: white

  - block: markdown
    id: research
    content:
      title: "Research"
      text: |

        ### Working Papers
        {{< publist folder="working-papers" self="Claudia Marangon" showYear="false" >}}

        ### Work in Progress
        {{< wiplist folder="wip" self="Claudia Marangon" >}}

        ### Conference Publications
        {{< publist folder="conf-publications" self="Claudia Marangon" showYear="true" >}}
    design:
      spacing:
        padding: ["2rem", "0", "2rem", "0"]   # top, right, bottom, left

      background:
        color: "#f5f7ff"
  - block: markdown
    id: teaching
    content:
      title: "Teaching"
      text: |
        {{< teachlist folder="teaching" >}}
    design:
      spacing:
        padding: ["2rem", "0", "2rem", "0"]   # top, right, bottom, left
      background:
        color: white
    # design:
    #   view: teachlist
    #   columns: "1"




---