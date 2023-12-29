---
title: SIAM UQ24 - Embedding High Resolution Variability into a Climate Simulation

event: SIAM Conference on Uncertainty Quantification (UQ24)
event_url: https://www.siam.org/conferences/cm/conference/uq24

location: Trieste, Italy
# address:
#   street: a
#   city: b
#   region: c
#   postcode: 'd'
#   country: e

summary: Fusion of machine learning and a climate model to embed high resolution variability into a coarse resolution climate simulation.
abstract: "2.2Underrepresentation of cloud formation is a known failing in current Climate simulations. This is due to the coarse grid resolution which is required due to the computational constraint of integrating over long time scales but does not permit the underlying cloud generating physical processes. This work employs a multi-output Gaussian Process (MOGP) trained on high resolution Unified Model (UM) runs and predicts the variability of temperature and specific humidity fields. A proof of concept study has been carried out where a trained MOGP model is coupled in-situ with a simplified Atmospheric General Circulation Model (AGCM) named SPEEDY. The temperature and specific humidity profiles of the SPEEDY model outputs are perturbed at each timestep according to the predicted high resolution informed variability. 10-year forecasts are generated for both default SPEEDY and fused SPEEDY models and output fields compared ensuring fused predictions remain representative of Earth's atmosphere. Some changes in the precipitation, outgoing longwave and shortwave radiation patterns are observed indicating modelling improvements in the complex region surrounding India and the Indian sea."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2023-03-01T17:00:00Z'
# date_end: '2023-07-19T12:10:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate: '2017-01-01T00:00:00Z'

authors: [admin]
tags: []

# Is this a featured talk? (true/false)
featured: false

# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#   focal_point: Right

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - Weather
---

{{% callout note %}}
**Coming Soon:** Slides and video recording coming as soon as paper pre-print is available on Arxiv.
{{% /callout %}}

<!-- Slides can be added in a few ways:

- **Create** slides using Wowchemy's [_Slides_](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page. -->