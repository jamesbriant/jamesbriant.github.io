---
title: Embedding High Resolution Variability into a Climate Simulation
summary: Fusion of machine learning and a climate model to embed high resolution variability into a coarse resolution climate simulation.
tags:
  - Weather
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

This project is developing a novel method to improve representation of cloud formation in climate models. Our method changes the simulated climate and reduces bias in hindcasts.

Pre-trained Gaussian Processes learn the temperature and specific humidity fields from high a resolution weather forecast. During the climate model run-time, Gaussian Process predictions add perturbations to climate model fields.

In collaboration with Dr. Dan Giles (UCL), Dr. Cyril Morcrette (UK Met Office) and Prof. Serge Guillas (UCL). An initial paper being readied for submission in Summer 2023 and more details will be available here after pre-print is available on Arxiv.