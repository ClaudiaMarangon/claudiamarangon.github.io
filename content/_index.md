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
        url: uploads/cv_claudiamarangon_2026.pdf
    design:
      css_class: light
      spacing:
        padding: ["2rem", "0", "2rem", "0"]
      background:
        color: white

  - block: markdown
    id: job-market-paper
    content:
      title: "Job Market Paper"
      text: |
        {{< publist folder="job-market-paper" self="Claudia Marangon" showYear="false" >}}
    design:
      spacing:
        padding: ["2rem", "0", "2rem", "0"]
      background:
        color: "#f5f7ff"

  - block: markdown
    id: working-papers
    content:
      title: "Working Papers"
      text: |
        {{< publist folder="working-papers" self="Claudia Marangon" showYear="false" >}}
    design:
      spacing:
        padding: ["2rem", "0", "2rem", "0"]
      background:
        color: white

  - block: markdown
    id: work-in-progress
    content:
      title: "Work in Progress"
      text: |
        {{< wiplist folder="wip" self="Claudia Marangon" >}}
    design:
      spacing:
        padding: ["2rem", "0", "2rem", "0"]
      background:
        color: "#f5f7ff"

  - block: markdown
    id: conference-publications
    content:
      title: "Conference Publications"
      text: |
        {{< publist folder="conf-publications" self="Claudia Marangon" showYear="true" >}}
    design:
      spacing:
        padding: ["2rem", "0", "2rem", "0"]
      background:
        color: white

  - block: markdown
    id: teaching
    content:
      title: "Teaching"
      text: |
        {{< teachlist folder="teaching" >}}
    design:
      spacing:
        padding: ["2rem", "0", "2rem", "0"]
      background:
        color: "#f5f7ff"
---
