---
title: Material Geometry Design Using Machine Learning and Optimization
summary: Adapting pruning strategy to generate auxetic material.
tags:
- Computational Material
date: "2019-07-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by Lufter
  focal_point: Smart

#links:
#- icon: twitter
#  name: Follow
#  url: https://twitter.com/georgecushen
#url_code: "https://github.com/Lufter/Lufter-Integrated-GAN-VGG-Optimization"
#url_pdf: ""
#url_slides: ""
#url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

Labeling microstructure samples by Finite Element Methods (FEM) is time comsuming, thus it can be the bottle-neck of our design process. As a result, we apply our regression VGG networks (rVGG) to accelrate labeling microstructute images. This is one leap forward to improve our design strategy. With this new method, we were able to use Bayesian-optimization model as a black box function to update material geometry that generated my generative adversarial networks (GAN) more efficiently. Since rVGG reduced the the time that required when evaluating sample material properties, the optimization model can run more iteration in limited time.

What we have done: 

* Applied generative adversarial networks (GAN) to generate high fidelity microstructure images.

* Proposed regression VGG networks (rVGG) that can predict mechanical properties from material images with 95% accuracy.

* Outperformed Finite Element Methods (FEM) in predicting time over 100 times.

* Investigated an Bayesian‑optimization model that can fine‑tune GAN‑generated microstructure geometry through the raid labeling of rVGG.

For more information, please take a look at [Design of Chiral Metamaterials via Deep Neural Networks](https://lufteracademy.netlify.app/publication/conference-paper/).
