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
        My current work focuses on developing spatial and spatiotemporal machine learning methods for epidemiological data modeling. Traditional epidemiological models often struggle to capture nonlinear spatial and temporal dependencies and interactions among multiple risk factors. To address this, I have been developing approaches that integrate spatial autocorrelation, temporal structure, and machine learning to improve outbreak prediction, hotspot detection, and disease risk mapping. For example, I developed a novel localized spatiotemporal random forest model to study the dynamics of COVID-19 incidence across United States counties. This framework adapts to both geographic and temporal variations, capturing how epidemiological, demographic, and environmental drivers shift across regions and over time. Such methods yield more accurate and actionable results, supporting early intervention strategies and better allocation of health resources.

        In parallel, I employ Bayesian statistical methods to study spatiotemporal disease dynamics. Bayesian frameworks allow the incorporation of prior knowledge and provide rigorous quantification of uncertainty, which is especially critical when data are heterogeneous across regions and periods. For instance, I collaborated in applying Bayesian distributed lag non-linear models to capture delayed effects of environmental exposures, such as temperature, on Salmonella risk in New South Wales, Australia. This approach not only improves interpretability but also produces reliable estimates with quantified uncertainty, enabling more trustworthy insights for public health decision-making.

        Building on this foundation, I am developing a growing interest in extending my research into spatially-aware deep learning methods for biological data modeling, particularly in the context of spatial transcriptomics and cellular microenvironments. While I have not yet conducted substantial work in this area, I am drawn to the unique capabilities of deep learning for modeling high-dimensional, spatially structured biological data. My aim is to eventually leverage these approaches to uncover novel biomarkers, characterize tissue heterogeneity, and better understand spatial organization in biological systems. This line of research has the potential to contribute significantly to cancer biology, neuroscience, and precision medicine.

        Looking further ahead, I am also interested in exploring explainable Bayesian deep learning methods for applications across epidemiology, biology, and environmental science. I am particularly motivated by the principled mechanisms for uncertainty quantification offered by Bayesian approaches, which are crucial in biomedical contexts where decisions can have profound consequences. Although this remains an emerging direction for me, I envision combining Bayesian deep learning with explainability frameworks to create models that are not only accurate but also transparent, trustworthy, and actionable. Such methods could, for example, provide outbreak predictions with quantified confidence levels in epidemiology, enable robust biomarker discovery with interpretable biological insights, or support climate and air quality forecasts with uncertainty estimates in environmental science.

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
      columns: "1"
---
