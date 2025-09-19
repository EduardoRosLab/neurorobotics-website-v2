---
title: 'Adaptive spiking cerebellar models and real-time simulations'
authors:
  - "O.J.M. Coenen"
  - "C. Boucheny"
  - "M. Bezzi"
  - "D. Marchal"
  - "M.P. Arnold"
  - eros
  - rcarrillo
  - "E.M. Ortigosa"
  - "R. Agís"
  - "B. Barbour"
  - "A. Arleo"
  - "T. Nieus"
  - "E. D'Angelo"

author_notes:
date: '2004-08-01T17:44:35+01:00'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2004-08-01T17:44:35+01:00'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.

publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: '34th Society for Neuroscience annual meeting (2004)'
publication_short: 'SFN2004'

abstract: "Platforms for real-time simulations of complete cerebellar (Cb) models using conductance-based integrate-and-fire (IF) neurons are presented. One is a table-based event-triggered simulator, which makes use of predictive threshold computation to achieve RT simulation of an adaptive Cb model composed of thousands of neurons learning the smooth tracking of target trajectories. Another is a Cb model running on a neural network simulator communicating spike events to an FPGA-chip hardware, which simulates a large number of granule cells. This system was tested on learning to play games of pong (solo ping-pong), by moving a racket attached to a simulated six-muscle human arm model. Parts of the models result from simplifing detailed NEURON models based on physiological data to retain the essential properties of information transmission and representation of the recorded neurons. Simulations details are provided regarding the simulators and the systems being simulated. Particular attention is given to the spike-timing dependent learning mechanisms at the parallel fibers to Purkinje cells synapses and to a probabilistic encoding of the error by the inferior olive (I0). The effects of plasticity rules at the granular layer are also investigated. Generally, the results demonstrate the ability of the models to learn accurately even though IO firing is very low, and to learn multiple tasks with little destructive interference. Real-time simulations are expected to be available as a demonstration of a cerebellum learning target trajectories."

# Summary. An optional shortened abstract.
summary:

tags:
featured: false

url_pdf: 'coenen2004.pdf'
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
