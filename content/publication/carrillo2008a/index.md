---
title: 'A real-time spiking cerebellum model for learning robot control'
authors:
  - rcarrillo
  - eros
  - 'C. Boucheny'
  - 'O.J.M.D. Coenen'

author_notes:
date: '2008-08-01T17:44:35+01:00'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2008-08-01T17:44:35+01:00'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.

publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: 'Biosystems'
publication_short: 'Biosystems'

abstract: "We describe a neural network model of the cerebellum based on integrate-and-fire spiking neurons with conductance-based synapses. The neuron characteristics are derived from our earlier detailed models of the different cerebellar neurons. We tested the cerebellum model in a real-time control application with a robotic platform. Delays were introduced in the different sensorimotor pathways according to the biological system. The main plasticity in the cerebellar model is a spike-timing dependent plasticity (STDP) at the parallel fiber to Purkinje cell connections. This STDP is driven by the inferior olive (IO) activity, which encodes an error signal using a novel probabilistic low frequency model. We demonstrate the cerebellar model in a robot control system using a target-reaching task. We test whether the system learns to reach different target positions in a non-destructive way, therefore abstracting a general dynamics model. To test the system's ability to self-adapt to different dynamical situations, we present results obtained after changing the dynamics of the robotic platform significantly (its friction and load). The experimental results show that the cerebellar-based system is able to adapt dynamically to different contexts."

# Summary. An optional shortened abstract.
summary:

tags:
featured: false

links:
 - name: "Journal"
   url: "https://doi.org/10.1016/j.biosystems.2008.05.008"
url_pdf: ''
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
