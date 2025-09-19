---
title: 'A Metric for Evaluating Neural Input Representation in Supervised Learning Networks'
authors:
  - rcarrillo
  - fnaveros
  - eros
  - nluque

author_notes:
date: '2018-12-25T17:44:35'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2018-12-25T17:44:35'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.

publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Frontiers in neuroscience"
publication_short: "Front. Neurosci."

abstract: "Supervised learning has long been attributed to several feed-forward neural circuits within the brain, with particular attention being paid to the cerebellar granular layer. The focus of this study is to evaluate the input activity representation of these feed-forward neural networks. The activity of cerebellar granule cells is conveyed by parallel fibers and translated into Purkinje cell activity, which constitutes the sole output of the cerebellar cortex. The learning process at this parallel-fiber-to-Purkinje-cell connection makes each Purkinje cell sensitive to a set of specific cerebellar states, which are roughly determined by the granule-cell activity during a certain time window. A Purkinje cell becomes sensitive to each neural input state and, consequently, the network operates as a function able to generate a desired output for each provided input by means of supervised learning. However, not all sets of Purkinje cell responses can be assigned to any set of input states due to the network's own limitations (inherent to the network neurobiological substrate), that is, not all input-output mapping can be learned. A key limiting factor is the representation of the input states through granule-cell activity. The quality of this representation (e.g., in terms of heterogeneity) will determine the capacity of the network to learn a varied set of outputs. Assessing the quality of this representation is interesting when developing and studying models of these networks to identify those neuron or network characteristics that enhance this representation. In this study we present an algorithm for evaluating quantitatively the level of compatibility/interference amongst a set of given cerebellar states according to their representation (granule-cell activation patterns) without the need for actually conducting simulations and network training. The algorithm input consists of a real-number matrix that codifies the activity level of every considered granule-cell in each state. The capability of this representation to generate a varied set of outputs is evaluated geometrically, thus resulting in a real number that assesses the goodness of the representation."

# Summary. An optional shortened abstract.
summary:

tags:
  - EDLUT
  - Robotics
featured: true

links:
 - name: "Journal"
   url: "https://www.frontiersin.org/articles/10.3389/fnins.2018.00913/full"
url_pdf: "Carrillo2018.pdf"
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#  focal_point: ''
#  preview_only: false

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
slides:
---
