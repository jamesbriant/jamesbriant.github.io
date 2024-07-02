---
title: Embedding machine-learnt sub-grid variability improves climate model biases
summary: Fusion of machine learning and a climate model to embed high resolution variability into a coarse resolution climate simulation.
A trained Guassian process model is coupled in-situ with a simplified atmospheric general circulation model.
tags:
  - Climate
date: "2023-08-02T00:00:00Z"

# Optional external URL for project (replaces project detail page).
# external_link: https://example.org

image:
  caption: Photo by James Briant
  focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---
The under-representation of cloud formation is a long-standing bias associated with climate simulations. Parameterisation schemes are required to capture cloud processes within current climate models but have known biases. We overcome these biases by embedding a Multi-Output Gaussian Process (MOGP) trained on high resolution Unified Model simulations to represent the variability of temperature and specific humidity within a climate model. A trained MOGP model is coupled in-situ with a simplified Atmospheric General Circulation Model named SPEEDY. The temperature and specific humidity profiles of SPEEDY are perturbed at fixed intervals according to the variability predicted from the MOGP. Ten-year predictions are generated for both control and ML-hybrid models. The hybrid model reduces the global precipitation bias by 18\% and over the tropics by 22\%. To further understand the drivers of these improvements, physical quantities of interest are explored, such as the distribution of lifted index values and the alteration of the Hadley cell. The control and hybrid set-ups are also run in a plus 4K sea-surface temperature experiment to explore the effects of the approach on patterns relating to cloud cover and precipitation in a warmed climate setting.

In collaboration with Dr. Dan Giles (UCL), Dr. Cyril Morcrette (UK Met Office) and Prof. Serge Guillas (UCL).