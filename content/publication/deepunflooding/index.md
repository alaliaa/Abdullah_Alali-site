---
title: "Deep learning unflooding for robust subsalt waveform inversion"
authors:
- admin
- Vladimir Kazei
- Mahesh Kalita
- Tariq Alkhalifah
author_notes:
- KAUST
- Aramco Americas
- Shearwater
- KAUST
date: "2022-03-13T00:00:00Z"
doi: " https://doi.org/10.1111/1365-2478.13193"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Geophysical prospecting*"
publication_short: ""

abstract: Full-waveform inversion, a popular technique that promises high-resolution models, has helped in improving the salt definition in inverted velocity models. The success of the inversion relies heavily on having prior knowledge of the salt, and using advanced acquisition technology with long offsets and low frequencies. Salt bodies are often constructed by recursively picking the top and bottom of the salt from seismic images corresponding to tomography models, combined with flooding techniques. The process is time consuming and highly prone to error, especially in picking the bottom of the salt. Many studies suggest performing full-waveform inversion with long offsets and low frequencies after constructing the salt bodies to correct the misinterpreted boundaries. Here, we focus on detecting the bottom of the salt automatically by utilizing deep learning tools. We specifically generate many random one-dimensional models, containing or free of salt bodies, and calculate the corresponding shot gathers. We then apply full-waveform inversion starting with salt flooded versions of those models, and the results of the full-waveform inversion become inputs to the neural network, whereas the corresponding true one-dimensional models are the output. The network is trained in a regression manner to detect the bottom of the salt and estimate the subsalt velocity. We analyse three scenarios in creating the training datasets and test their performance on the two-dimensional BP 2004 salt model. We show that when the network succeeds in estimating the subsalt velocity, the requirement of low frequencies and long offsets are somewhat mitigated. In general, this work allows us to merge the top-to-bottom approach with full-waveform inversion, save the bottom of the salt picking time and empower full-waveform inversion to converge in the absence of low frequencies and long offsets in the data.

# Summary. An optional shortened abstract.
summary: We automatically unflood the salt body in full-waveform inversion by utilizing deep learning tools. We analyze three scenarios in creating the training datasets. 

tags: []
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/2201.02947.pdf
url_code: 'https://github.com/alaliaa/Unet_Salt_Unflooding'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://onlinelibrary.wiley.com/doi/full/10.1111/1365-2478.13193'
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
Check out a very nice summary for this work in [SWAG page](https://swag-kaust.github.io/swag-paper-template/alali-Deep-learning-unflooding-for-robust-subsalt-waveform-inversion.html)
{{% /callout %}}
