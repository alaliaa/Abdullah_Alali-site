---
title: "Time-lapse data matching using a recurrent neural network approach"
authors:
- admin
- Vladimir Kazei
- Bingbing Sun
- Tariq Alkhalifah
author_notes:
- KAUST
- Aramco Americas
- Saudi Aramco
- KAUST
date: "2022-07-13T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Geophysics*"
publication_short: ""

abstract: Time-lapse seismic data acquisition is an essential tool to monitor changes in a reservoir due to fluid injection, such as CO2 injection. By acquiring multiple seismic surveys in the exact same location, the authors can identify the reservoir changes by analyzing the difference in the data. However, such analysis can be skewed by the near-surface seasonal velocity variations, inaccuracy, and repeatability in the acquisition parameters, and other inevitable noise. The common practice (cross equalization) to address this problem uses the part of the data in which changes are not expected to design a matching filter and then apply it to the whole data, including the reservoir area. Like cross equalization, the authors train a recurrent neural network (RNN) on parts of the data excluding the reservoir area and then infer the reservoir-related data. The RNN can learn the time dependency of the data, unlike the matching filter that processes the data based on the local information obtained in the filter window. The authors determine the method of matching the data in various examples and compare it with the conventional matching filter. Specifically, we start by demonstrating the ability of the approach in matching two traces and then test the method on a prestack 2D synthetic data. Then, the authors verify the enhancements of the 4D signal by providing reverse time migration images. The authors measure the repeatability using normalized root-mean-square and predictability metrics and find that, in some cases, our proposed method performed better than the matching filter approach.

# Summary. An optional shortened abstract.
summary: Conventionally time-lapse surveys have discripency in the signal due to the overburden changes. A data matching between different surveys is performed using recurrent neural network. 

tags: []
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: 'https://arxiv.org/pdf/2204.00941.pdf'
url_code: 'https://github.com/alaliaa/4Dseimsic-Xeq-RNN'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://docs.google.com/presentation/d/1g6hIEABd8TclHFmOaFQDYSwzN8gtAfeU/edit?usp=sharing&ouid=115783403967921953165&rtpof=true&sd=true'
url_source: 'https://library.seg.org/doi/full/10.1190/geo2021-0487.1'
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
