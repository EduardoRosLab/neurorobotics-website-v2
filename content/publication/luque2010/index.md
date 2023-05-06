---
title: 'Cerebellar spiking engine: Towards objet model abstraction in manipulation'
authors:
  - nluque
  - jgarrido
  - rcarrillo
  - eros

author_notes:
date: '2010-07-08T17:44:35'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2010-07-08T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 'The 2010 International Joint Conference on Neural Networks'
publication_short: 'IJCNN 2010'

abstract: "This paper presents how a simple cerebellumlike architecture can infer corrective models in the framework of a control task when manipulating objects that significantly affect the dynamics model of the system. The main motivation of this paper is to evaluate a simplified bio-mimetic approach in the framework of a manipulation task. More concretely, the paper focuses on how the model inference process takes place within a feedforward control loop based on the cerebellar structure and on how these internal models are built up by means of biologically plausible synaptic adaptation mechanisms. This kind of investigation may provide clues on how biology achieves accurate control of non-stiff-joint robot with low-power actuators which involve controlling systems with high inertial components. This paper studies how a basic temporal-correlation kernel including long-term depression (LTD) and a constant long-term potentiation (LTP) at parallel fiber-Purkinje cell synapses can effectively infer corrective models. We evaluate how this spike-timing-dependent plasticity correlates sensorimotor activity arriving through the parallel fibers with teaching signals (dependent on error estimates) arriving through the climbing fibers from the inferior olive. This paper addresses the study of how these LTD and LTP components need to be well balanced with each other to achieve accurate learning. This is of interest to evaluate the relevant role of homeostatic mechanisms in biological systems where adaptation occurs in a distributed manner. Furthermore, we illustrate how the temporal-correlation kernel can also work in the presence of transmission delays in sensorimotor pathways. We use a cerebellumlike spiking neural network which stores the corrective models as well-structured weight patterns distributed among the parallel fibers to Purkinje cell connections."

# Summary. An optional shortened abstract.
summary:

tags:
  - Cerebellum
  - Learning
  - Spiking Neuronal Networks

featured: false

links:
 - name: "Journal"
   url: "http://ieeexplore.ieee.org/abstract/document/5596531/"
url_pdf: 'luque2010'
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
