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
        My current work focuses on developing and applying machine learning and Bayesian statistical methods for epidemiological modeling. Traditional epidemiological models often struggle to capture nonlinear spatial and temporal dependencies and interactions among multiple risk factors. To address this, I have been creating approaches that integrate spatial autocorrelation, temporal structure, and machine learning to improve outbreak prediction, hotspot detection, and disease risk mapping. For example, I developed a novel localized spatiotemporal random forest model to study the dynamics of COVID-19 incidence across United States counties, a framework that adapts to both geographic and temporal variations, capturing how epidemiological, demographic, and environmental drivers shift across regions and over time. I also employ Bayesian frameworks, which allow the incorporation of prior knowledge and provide rigorous quantification of uncertainty, particularly important when data are heterogeneous across regions and periods. For instance, I collaborated in applying Bayesian distributed lag non-linear models to capture delayed effects of environmental exposures, such as temperature, on Salmonella risk in New South Wales, Australia. Both the machine learning and Bayesian approaches contribute to methods that are more accurate, interpretable, and actionable, providing stronger support for early intervention strategies, reliable estimation, and better-informed public health decision-making.

        Looking further ahead, I am interested in advancing causal machine learning methods for epidemiological modeling. Unlike traditional predictive models, causal approaches enable the estimation of cause-and-effect relationships, counterfactual reasoning, and evaluation of potential interventions. I envision integrating causal inference with modern machine learning to assess how vaccination campaigns, public health policies, or environmental exposures influence disease outcomes. For example, causal machine learning could disentangle the effects of air pollution or climate variability on infectious disease dynamics, quantify the health impacts of targeted interventions, and guide the design of adaptive, evidence-based policies. In addition, I am developing an interest in deep learning for biological data analysis, particularly in the context of spatial transcriptomics and cellular microenvironments. Deep learning offers unique capabilities for analyzing high-dimensional, spatially structured biological data, with potential to uncover novel biomarkers, characterize tissue heterogeneity, and better understand spatial organization in tissues—advancing fields such as cancer biology, neuroscience, and precision medicine.

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
