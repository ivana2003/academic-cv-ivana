---
title: ''
summary: ''
date: 2026-09-20
type: landing

sections:

  # =========================================================
  # PROFILE / BIOGRAPHY
  # =========================================================
  - block: resume-biography-3
    content:
      username: me
      text: ''

      button:
        text: Download CV
        url: https://ivana2003.github.io/academic-cv-ivana/uploads/CV_Crescenzi_Ivana.pdf

      headings:
        about: About Me
        education: Education
        interests: Research Interests

    design:
      background:
        gradient_mesh:
          enable: true

      name:
        size: md

      avatar:
        size: medium
        shape: circle


  # =========================================================
  # RESEARCH
  # =========================================================
  - block: markdown
    id: research
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        My research focuses on Natural Language Processing and Large Language Models,
        with particular interest in trustworthy and personalized NLP.

        I am also interested in machine learning theory, algorithms and optimization,
        particularly in the theoretical analysis of user-conditioned objective
        functions and the geometry and topology of loss landscapes.

        My recent work includes multilingual humor detection, reclaimed and harmful
        language detection, retrieval-augmented methods, and the evaluation of
        large language models.
    design:
      columns: '1'


  # =========================================================
  # PUBLICATIONS
  # =========================================================
  - block: collection
    id: publications
    content:
      title: Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
---
