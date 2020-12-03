---
title: Auxetic Networks
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
#url_code: ""
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

Auxetic networks can achieve both homogenous and negtive poisson's ratio with very low density. One of the idea to generate this geometry is to adapt pruning strategy to disorder networks. By pruning out the bond that contributed least to shear modulus of the entire networks in each iteration, it is proved by Reid *etal.* [1]  that the poisson's ration will slowly converge to a negetive value. We were able to implemented this idea on the Google Could Service(GCP) with 96-core CPUs. The auxetic samples were ment to be one of the types in my machine learning dataset. 

What we have implemented:

* Implemented pruning protocol on 96 core CPUs to generate auxetic networks.

* Implemented a stochastic protocol to produce large scale homogenous microstructure datasets by two‑point correlation function.

Reference

[1] Daniel R. Reid, Nidhi Pashine, Justin M. Wozniak, Heinrich M. Jaeger, Andrea J. Liu, Sidney R. Nagel, Juan J. de Pablo, *[Auxetic metamaterials from disordered networks](https://www.pnas.org/content/115/7/E1384)*, Proceedings of the National Academy of Sciences Feb 2018, 115 (7) E1384-E1390; DOI: 10.1073/pnas.1717442115