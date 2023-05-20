---
title: Integrating U-net with full-waveform inversion for an efficient salt body
  construction
authors:
  - admin
  - Tariq Alkhalifah
author_notes:
  - KAUST
  - KAUST
publication_short: "" 
abstract: Full waveform inversion (FWI) often faces a lot of difficulty inverting for the subsurface when starting with a poor initial model, especially in complex subsurface regions, such as those containing salt bodies. Thus, human intervention is often needed to pick the salt boundary and improve the starting model for the inversion, which can be erroneous and time consuming. Recently, machine learning has greatly assisted us in interpreting the salt body from seismic images, which helps automate the salt building process. However, such ML algorithms require seismic images, which in turn requires a reasonable good velocity model. Here, we build the salt body using low frequency FWI with the aid of neural networks, specifically U-net. The inversion is implemented in a multi-scale fashion and the networks for flooding and unflooding the salt are applied after each scale. We start the inversion from a constant velocity model using low frequencies of 3-7 Hz. Then, we apply a U-net to improve the inversion and flood the salt. We repeat this process of FWI and flooding in the next frequency bandwidth. In the last frequency bandwidth, we use a U-net for unflooding and impliment a final FWI. The networks were trained in a supervised manner using 1D inverted velocity models. We show the potential of the approach on the center part of BP 2004 salt model.
tags: []
projects: []
slides: ""
url_pdf: https://arxiv.org/pdf/2304.02758.pdf
publication_types:
  - "1"
image:
  caption: ""
  focal_point: ""
  preview_only: false
summary: Inversion workflow for salt bodies from poor inital model, limited offsets and with frequencies starting from 5 Hz. Multistage flooding and unflooding is implimented using U-net networks within the multiscale approach in the FWI. 
url_dataset: ""
url_project: ""
url_source: https://library.seg.org/doi/pdf/10.1190/image2022-3751821.1
url_video: ""
publication: In *Second International Meeting for Applied Geoscience & Energy*
featured: true
date: "2022-08-15T00:00:00Z"
url_slides: "https://docs.google.com/presentation/d/1q50Ku1UXLmKZqgRo1QjkkWC0JQOUQRHC/edit?usp=sharing&ouid=115783403967921953165&rtpof=true&sd=true"
publishDate: "2022-08-15T00:00:00Z"
url_poster: "https://drive.google.com/file/d/1NmKiyycONeh3ijg9PEcLc3ag70vIdJ4l/view?usp=sharing"
url_code: https://github.com/alaliaa/Integrating-Unet-with-FWI-for-salt
doi: "https://doi.org/10.1190/image2022-3751821.1"
---
{{% callout note %}}
This work is still in progress
{{% /callout %}}



