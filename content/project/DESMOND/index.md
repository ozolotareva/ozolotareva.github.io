---
title: DESMOND
summary: A method for the dentification of network-constrained differentially expressed biclusters. 
tags:
- Biclustering
date: "2021-04-27T00:00:00Z"

weight: 2
# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  #caption: Photo by rawpixel on Unsplash
  focal_point: Smart

#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example

---

Identification of differentially expressed genes is necessary for unraveling disease pathogenesis. This task is complicated by the fact that many diseases are heterogeneous at the molecular level and samples representing distinct disease subtypes may demonstrate different patterns of dysregulation. Biclustering methods are capable of identifying genes that follow a similar expression pattern only in a subset of samples and hence can consider disease heterogeneity. However, identifying biologically significant and reproducible sets of genes and samples remain challenging for the existing tools. Many recent studies have shown that the integration of gene expression and protein interaction data improves the robustness of prediction and classification and advances biomarker discovery.

Here, we present DESMOND, a new method for identification of Differentially ExpreSsed gene MOdules iN Diseases. DESMOND performs network-constrained biclustering on gene expression data and identifies gene modules—connected sets of genes up- or down-regulated in subsets of samples. We applied DESMOND on expression profiles of samples from two large breast cancer cohorts and have shown that the capability of DESMOND to incorporate protein interactions allows identifying the biologically meaningful gene and sample subsets and improves the reproducibility of the results.

https://doi.org/10.1093/bioinformatics/btaa1038

