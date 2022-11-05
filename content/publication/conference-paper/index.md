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
abstract: Full waveform inversion (FWI) often faces a lot of difficulty
  inverting for the subsurface when starting with a poor initial model,
  especially in complex subsurface regions, such as those containing salt
  bodies. Thus, human intervention is often needed to pick the salt boundary and
  improve the starting model for the inversion, which can be erroneous and time
  consuming. Recently, machine learning has greatly assisted us in interpreting
  the salt body from seismic images, which helps automate the salt building
  process. However, such ML algorithms require seismic images, which in turn
  requires a reasonable good velocity model. Here, we build the salt body using
  low frequency FWI with the aid of neural networks, specifically U-net. The
  inversion is implemented in a multi-scale fashion and the networks for
  flooding and unflooding the salt are applied after each scale. We start the
  inversion from a constant velocity model using low frequencies of 3-7 Hz.
  Then, we apply a U-net to improve the inversion and flood the salt. We repeat
  this process of FWI and flooding in the next frequency bandwidth. In the last
  frequency bandwidth, we use a U-net for unflooding and impliment a final FWI.
  The networks were trained in a supervised manner using 1D inverted velocity
  models. We show the potential of the approach on the center part of BP 2004
  salt model.
tags: []
projects: []
slides: ""
url_pdf: ""
publication_types:
  - "1"
image:
  caption: ""
  focal_point: ""
  preview_only: false
summary: ""
url_dataset: https://github.com/wowchemy/wowchemy-hugo-themes
url_project: ""
url_source: https://github.com/wowchemy/wowchemy-hugo-themes
url_video: https://youtube.com
publication: In *Second International Meeting for Applied Geoscience & Energy*
featured: false
date: 2013-07-01T00:00:00Z
url_slides: ""
publishDate: 2017-01-01T00:00:00Z
url_poster: ""
url_code: https://github.com/wowchemy/wowchemy-hugo-themes
doi: ""
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
