---
title: 'From sensors to spikes: evolving receptive fields to enhance sensorimotor information in a robot-arm'
authors:
  - nluque
  - jgarrido
  - "J. Ralli"
  - "J.L. Jiménez"
  - eros

author_notes:
date: '2012-08-01T17:44:35'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2012-08-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'International Journal of Neural Systems'
publication_short: 'Int. J. Neur. Syst.'

abstract: "In biological systems, instead of actual encoders at different joints, proprioception signals are acquired through distributed receptive fields. In robotics, a single and accurate sensor output per link (encoder) is commonly used to track the position and the velocity. Interfacing bio-inspired control systems with spiking neural networks emulating the cerebellum with conventional robots is not a straight forward task. Therefore, it is necessary to adapt this one-dimensional measure (encoder output) into a multidimensional space (inputs for a spiking neural network) to connect, for instance, the spiking cerebellar architecture; i.e. a translation from an analog space into a distributed population coding in terms of spikes. This paper analyzes how evolved receptive fields (optimized towards information transmission) can efficiently generate a sensorimotor representation that facilitates its discrimination from other \"sensorimotor states\". This can be seen as an abstraction of the Cuneate Nucleus (CN) functionality in a robot-arm scenario. We model the CN as a spiking neuron population coding in time according to the response of mechanoreceptors during a multi-joint movement in a robot joint space. An encoding scheme that takes into account the relative spiking time of the signals propagating from peripheral nerve fibers to second-order somatosensory neurons is proposed. Due to the enormous number of possible encodings, we have applied an evolutionary algorithm to evolve the sensory receptive field representation from random to optimized encoding. Following the nature-inspired analogy, evolved configurations have shown to outperform simple hand-tuned configurations and other homogenized configurations based on the solution provided by the optimization engine (evolutionary algorithm). We have used artificial evolutionary engines as the optimization tool to circumvent nonlinearity responses in receptive fields."

# Summary. An optional shortened abstract.
summary:

tags:
  - Receptive Fields
  - Learning
  - Spiking Neuronal Networks

featured: false

links:
 - name: "Journal"
   url: "http://www.worldscientific.com/doi/abs/10.1142/S012906571250013X"
url_pdf: 'luque2012'
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
