---
title: "The effectiveness of a pseudo inverse extended born operator to handle lateral heterogeneity for imaging and velocity analysis applications"
authors:
- admin
- Bingbing Sun
- Tariq Alkhalifah
author_notes:
- KAUST
- KAUST
- KAUST
date: "2020-06-09T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-06-09T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Geophysical prospecting*"
publication_short: ""

abstract: Wave equation–based migration velocity analysis techniques aim to construct a kinematically accurate velocity model for imaging or as an initial model for full waveform inversion applications. The most popular wave equation–based migration velocity analysis method is differential semblance optimization, where the velocity model is iteratively updated by minimizing the unfocused energy in an extended image volume. However, differential semblance optimization suffers from artefacts, courtesy of the adjoint operator used in imaging, leading to poor convergence. Recent findings show that true amplitude imaging plays a significant role in enhancing the differential semblance optimization's gradient and reducing the artefacts. Here, we focus on a pseudo‐inverse operator to the horizontally extended Born as a true amplitude imaging operator. For laterally inhomogeneous models, the operator required a derivative with respect to a vertical shift. Extending the image vertically to evaluate such a derivative is costly and impractical. The inverse operator can be simplified in laterally homogeneous models. We derive an extension of the approach to apply the full inverse formula and evaluate the derivative efficiently. We simplified the implementation by applying the derivative to the imaging condition and utilize the relationship between the source and receiver wavefields and the vertical shift. Specifically, we verify the effectiveness of the approach using the Marmousi model and show that the term required for the lateral inhomogeneity treatment has a relatively small impact on the results for many cases. We then apply the operator in differential semblance optimization and invert for an accurate macro‐velocity model, which can serve as an initial velocity model for full waveform inversion.

# Summary. An optional shortened abstract.
summary: Analysis of the application of a pseudo inverse extended Born operator in a complex hetrogenious models. The operator is also tested in a DSO optimization to obtained a smooth velocity model for imaging and full-waveform inversion. 

tags: []
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://www.earthdoc.org/content/journals/10.1111/1365-2478.12916'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

{{% callout note %}}
For more details please check the full paper using the links above
{{% /callout %}}
