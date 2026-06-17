---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      headings:
        about: "Hello, I'm Giovanni Crestani!"
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md # Options: xs, sm, md, lg (default), xl
      avatar:
        size: large # Options: small, medium (default), large, xl, xxl
        shape: circle # Options: circle (default), square, rounded
  - block: section-split
    id: research
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        My PhD research uses **population genomics** to understand how complex traits
        adapt. I work with a *Drosophila melanogaster* system created in the 1980s:
        populations under continuous selection for **postponed reproduction** (only old
        flies are allowed to reproduce), which has produced striking phenotypes —
        including flies that live more than twice as long as usual. By reconstructing the
        genomic changes behind this adaptation, I aim to understand how reproducible,
        reversible, and parallel evolution really is.

        **Keywords:** Experimental Evolution, Evolutionary Genomics, *Drosophila melanogaster*
    design:
      background:
        color:
          light: 'rgba(128,128,128,0.14)'
  - block: section-split
    id: publications
    content:
      title: 'Publications'
      subtitle: ''
      text: |-
        <a href="https://www.biorxiv.org/content/10.64898/2026.02.25.708047v1" target="_blank" rel="noopener" class="text-xl sm:text-2xl font-bold no-underline text-gray-900 dark:text-white hover:text-primary-600 dark:hover:text-primary-400">Parallel adaptive responses to postponed reproduction increase lifespan and immune defense</a>

        Gamboa-Santarosa KA\*, **Crestani GA**\*, Moran A, Modha D, Dugo HS, Abdoli M, Burke MK, Shahrestani P. (2026). *bioRxiv.* doi:&nbsp;[10.64898/2026.02.25.708047](https://doi.org/10.64898/2026.02.25.708047)

        <span class="text-sm text-gray-500 dark:text-gray-400">Manuscript in review, invited for resubmission. \*Equal contribution.</span>
  - block: github-projects
    id: projects
    content:
      title: 'Projects'
      repos:
        - repo: gacrestani/burke_lab_pipeline
          title: Burke Lab Pipeline
        - title: OmniAccess
          url: https://omniaccess.app/
          description: "AI-powered tool that improves accessibility in lecture presentations."
          icon: globe-alt
        - repo: gacrestani/iPSC-Pipeline
          title: iPSC Pipeline
        - repo: gacrestani/chave_dicotomica
          title: Dichotomous Key App
    design:
      background:
        color:
          light: 'rgba(128,128,128,0.14)'
  - block: section-split
    id: teaching
    content:
      title: 'Teaching'
      subtitle: ''
      text: |-
        I'm a Graduate Teaching Assistant for Introductory Biology at Oregon State
        University, where I help students get hands-on with core lab instruments and the
        scientific method. Students consistently describe a welcoming, patient, and
        well-organized lab environment.

        **Lectures Taught:** BI 221

        **Labs Taught:** BI 101, BI 103, BI 221, BI 222, BI 223

        **Average Student Evaluation:** 5.5/6.0
---
