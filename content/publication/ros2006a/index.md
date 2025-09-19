---
title: 'Event-Driven Simulation Scheme for Spiking Neural Networks Using Lookup Tables to Characterize Neuronal Dynamics'
authors:
  - eros
  - rcarrillo
  - "E.M. Ortigosa"
  - "B. Barbour"
  - "R. Agís"

author_notes:
date: '2006-12-01T17:44:35'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2006-12-01T17:44:35'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.

publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Neural Computation"
publication_short: "Neur. Computat."

abstract: "Nearly all neuronal information processing and interneuronal communication in the brain involves action potentials, or spikes, which drive the short-term synaptic dynamics of neurons, but also their long-term dynamics, via synaptic plasticity. In many brain structures, action potential activity is considered to be sparse. This sparseness of activity has been exploited to reduce the computational cost of large-scale network simulations, through the development of event-driven simulation schemes. However, existing event-driven simulations schemes use extremely simplified neuronal models. Here, we implement and evaluate critically an event-driven algorithm (ED-LUT) that uses precalculated look-up tables to characterize synaptic and neuronal dynamics. This approach enables the use of more complex (and realistic) neuronal models or data in representing the neurons, while retaining the advantage of high-speed simulation. We demonstrate the method's application for neurons containing exponential synaptic conductances, thereby implementing shunting inhibition, a phenomenon that is critical to cellular computation. We also introduce an improved two-stage event-queue algorithm, which allows the simulations to scale efficiently to highly connected networks with arbitrary propagation delays. Finally, the scheme readily accommodates implementation of synaptic plasticity mechanisms that depend on spike timing, enabling future simulations to explore issues of long-term learning and adaptation in large-scale networks."
# Summary. An optional shortened abstract.
summary:

tags:
  - EDLUT
  - Spiking Neural Networks
featured: false

links:
 - name: "Journal"
   url: "https://doi.org/10.1162/neco.2006.18.12.2959"
url_pdf: ""
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
