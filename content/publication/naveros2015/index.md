---
title: 'A spiking neural simulator integrating event-driven and time-driven computation schemes using parallel CPU-GPU co-processing: a case study'
authors:
  - fnaveros
  - nluque
  - jgarrido
  - rcarrillo
  - "M. Anguita"
  - eros


author_notes:
date: '2015-07-01T17:44:35'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2015-07-01T17:44:35'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'IEEE Transactions on Neural Networks and Learning Systems'
publication_short: 'IEEE Trans. Neural Netw. Learn. Syst.'

abstract: "Time-driven simulation methods in traditional CPU architectures perform well and precisely when simulating small-scale spiking neural networks. Nevertheless, they still have drawbacks when simulating large-scale systems. Conversely, event-driven simulation methods in CPUs and time-driven simulation methods in graphic processing units (GPUs) can outperform CPU time-driven methods under certain conditions. With this performance improvement in mind, we have developed an event-and-time-driven spiking neural network simulator suitable for a hybrid CPU-GPU platform. Our neural simulator is able to efficiently simulate bio-inspired spiking neural networks consisting of different neural models, which can be distributed heterogeneously in both small layers and large layers or subsystems. For the sake of efficiency, the low-activity parts of the neural network can be simulated in CPU using event-driven methods while the high-activity subsystems can be simulated in either CPU (a few neurons) or GPU (thousands or millions of neurons) using time-driven methods. In this brief, we have undertaken a comparative study of these different simulation methods. For benchmarking the different simulation methods and platforms, we have used a cerebellar-inspired neural-network model consisting of a very dense granular layer and a Purkinje layer with a smaller number of cells (according to biological ratios). Thus, this cerebellar-like network includes a dense diverging neural layer (increasing the dimensionality of its internal representation and sparse coding) and a converging neural layer (integration) similar to many other biologically inspired and also artificial neural networks."

# Summary. An optional shortened abstract.
summary:

tags:
  - simulation
  - EDLUT
  - Spiking Neural Networks
featured: false

links:
 - name: "Journal"
   url: "http://ieeexplore.ieee.org/abstract/document/6883192/"
url_pdf: 'naveros2015.pdf'
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
projects: [hbp']

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---
