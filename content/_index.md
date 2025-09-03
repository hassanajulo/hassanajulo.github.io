---
# Leave the homepage title empty to use the site title
title: Hassan Ajulo
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
      css_class: dark
      # Avatar customization
      avatar:
        size: medium  # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    id: research
    content:
      title: 'Research Statement'
      subtitle: ''
      text: |-
        My current research focuses on developing and applying machine learning (ML) and Bayesian statistical methods for epidemiology. For example, I recently developed a localized spatiotemporal random forest model to study COVID-19 dynamics across US counties, capturing how epidemiological, demographic, and environmental drivers shift across regions and periods. I also applied Bayesian frameworks, including distributed lag non-linear models, to quantify uncertainty and evaluate delayed environmental effects, such as temperature on Salmonella risk across New South Wales local health districts. These methods provide more accurate, interpretable, and actionable insights to support early interventions and inform public health decision-making.

        Looking ahead, I am interested in integrating causal inference with modern ML to estimate intervention effects and enable counterfactual reasoning. This direction could disentangle the impacts of policies, vaccination campaigns, biomarkers, and environmental exposures on disease outcomes, guiding adaptive, evidence-based strategies. In addition, I am developing an interest in deep learning for biological data, particularly spatial transcriptomics and cellular microenvironments, where such methods can uncover biomarkers, characterize tissue heterogeneity, and advance precision medicine.

        Please reach out to collaborate.
    design:
      columns: ''
  - block: collection
    id: publications
    content:
      title: Selected Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: markdown
    id: awards
    content:
      title: "Selected Awards & Honors"
      text: |-
        - [Research Dissemination Grant]() – James Cook University, 2025
        - [AMSI Travel Grant](https://rhed.amsi.org.au/grant-recipients/) – Australian Mathematical Science Institute BioInfoSummer, 2024
        - [Postgraduate Research Scholarship (Full)]() – James Cook University, 2023
        - [Competitive iSI Scholarship](https://ischolarinitiative.org/2023-isi-scholarship-awardees/) – i-Scholar Initiative Scholarship, 2023 
        - [Competitive ANSA Fellowship](https://www.ansaofficial.org/post/meet-the-2022-ansa-fellowship-recipients) – Association of Nigerian Scholars in America, 2022
        - [Postgraduate Degree Scholarship (Full)]() – African Institute for Mathematical Sciences, 2021
  - block: skills
    id: skills
    content:
      title: "Technical Skills"
      text: "" 
      items:
    design:
      columns: "2"
  - block: languages
    id: languages
    content:
      title: "Languages"
      text: "" 
      items:
    design:
      columns: "1"
---
