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
        My current research focuses on developing machine learning (ML) and Bayesian statistical methods for applications in epidemiology. For example, I recently developed a localized spatiotemporal random forest model to study COVID-19 dynamics across US counties, capturing how epidemiological, demographic, and environmental drivers shift across regions and periods. I also collaborated in applying Bayesian frameworks, including distributed lag non-linear models, to quantify uncertainty and evaluate delayed environmental effects, such as temperature on Salmonella risk across New South Wales local health districts. These methods provide more accurate, interpretable, and actionable insights to support early interventions and inform public health decision-making.

        Looking ahead, I am interested in integrating causal inference with modern ML for applications in epidemiology, estimating intervention effects and enable counterfactual reasoning. This direction could disentangle the impacts of policies, vaccination campaigns, and environmental exposures on disease outcomes, guiding adaptive, evidence-based strategies. In addition, I am developing an interest in ML for biological data, particularly spatial transcriptomics and cellular microenvironments, where such methods can uncover biomarkers, characterize tissue heterogeneity, and advance precision medicine.
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
    id: teaching
    content:
      title: "Teaching Experience"
      text: |-
        - **Assistant Lecturer – (November, 2018 – October, 2019)**  
          Department of Mathematics and Statistics, The Oke-Ogun Polytechnic Saki  
          Topics: STA 111 - Descriptive Statistics, STA 113 - Statistical Regression Methods, MAT 125 - Intoductory Linear Algebra, STA 413 - Non-Paramtric Methods
  - block: markdown
    id: awards
    content:
      title: "Selected Academic Recognition"
      text: |-
        - [Research Dissemination Grant]() – James Cook University, 2025
        - [AMSI Travel Grant](https://rhed.amsi.org.au/grant-recipients/) – Australian Mathematical Science Institute BioInfoSummer, 2024
        - [Postgraduate Research Scholarship (Full)]() – James Cook University Australia, 2023
        - [Competitive iSI Scholarship](https://ischolarinitiative.org/2023-isi-scholarship-awardees/) – i-Scholar Initiative, 2023 
        - [Competitive ANSA Fellowship](https://www.ansaofficial.org/post/meet-the-2022-ansa-fellowship-recipients) – Association of Nigerian Scholars in America, 2022
        - [Postgraduate Degree Scholarship (Full)]() – African Institute for Mathematical Sciences Rwanda, 2021
  - block: skills
    id: skills
    content:
      title: "Technical Skills"
      text: "" 
      items:
    design:
      columns: "2"
---
