---
title: 'Optimization of Efficient Neuron Models With Realistic Firing Dynamics. The Case of the Cerebellar Granule Cell'
authors:
  - mmarin
  - "María J. Sáez-Lara"
  - eros
  - jgarrido

author_notes:
date: '2020-07-14T17:44:35'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-07-14T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'Frontiers in Cellular Neuroscience'
publication_short: 'Front. Cell. Neurosci.'

abstract: "Biologically relevant large-scale computational models currently represent one of the main methods in neuroscience for studying information processing primitives of brain areas. However, biologically realistic neuron models tend to be computationally heavy and thus prevent these models from being part of brain-area models including thousands or even millions of neurons. The cerebellar input layer represents a canonical example of large scale networks. In particular, the cerebellar granule cells, the most numerous cells in the whole mammalian brain, have been proposed as playing a pivotal role in the creation of somato-sensorial information representations. Enhanced burst frequency (spiking resonance) in the granule cells has been proposed as facilitating the input signal transmission at the theta-frequency band (4–12 Hz), but the functional role of this cell feature in the operation of the granular layer remains largely unclear. This study aims to develop a methodological pipeline for creating neuron models that maintain biological realism and computational efficiency whilst capturing essential aspects of single-neuron processing. Therefore, we selected a light computational neuron model template (the adaptive-exponential integrate-and-fire model), whose parameters were progressively refined using an automatic parameter tuning with evolutionary algorithms (EAs). The resulting point-neuron models are suitable for reproducing the main firing properties of a realistic granule cell from electrophysiological measurements, including the spiking resonance at the theta-frequency band, repetitive firing according to a specified intensity-frequency (I-F) curve and delayed firing under current-pulse stimulation. Interestingly, the proposed model also reproduced some other emergent properties (namely, silent at rest, rheobase and negligible adaptation under depolarizing currents) even though these properties were not set in the EA as a target in the fitness function (FF), proving that these features are compatible even in computationally simple models. The proposed methodology represents a valuable tool for adjusting AdEx models according to a FF defined in the spiking regime and based on biological data. These models are appropriate for future research of the functional implication of bursting resonance at the theta band in large-scale granular layer network models."

# Summary. An optional shortened abstract.
summary:

tags:
  - Neuron Models
  - Evolutionary Algorithms
  - Cerebellum
  - Granular layer
featured: true

links:
 - name: "Journal"
   url: "https://www.frontiersin.org/articles/10.3389/fncel.2020.00161/full"
url_pdf: 'marin2020'
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
projects: ['cerebrot','hbp','intsenso']

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---
