---
title: 'On robot compliance. A cerebellar control approach'
authors:
  - iabadia
  - fnaveros
  - jgarrido
  - eros
  - nluque
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
date: '2019-10-23T17:44:35'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-05-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.

publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: 'IEEE transaction on cybernetics'
publication_short: 'IEEE trans. on cybernetics'

abstract: "The work presented here is a novel biological approach for the compliant control of a robotic arm in real time (RT). We integrate a spiking cerebellar network at the core of a feedback control loop performing torque driven control. The spiking cerebellar controller provides torque commands allowing for accurate and coordinated arm movements. To compute these output motor commands, the spiking cerebellar controller receives the robot’s sensorial signals, the robot’s goal behaviour, and an instructive signal. These input signals are translated into a set of evolving spiking patterns, representing univocally a specific system state at every point of time. Spike Timing- Dependent Plasticity (STDP) is then supported, allowing for building adaptive control. The spiking cerebellar controller continuously adapts the torque commands provided to the robot from experience as STDP is deployed. Adaptive torque commands, in turn, help the spiking cerebellar controller to cope with built-in elastic elements within the robot’s actuators mimicking human muscles (inherently elastic). We propose a natural integration of a bio-inspired control scheme, based on the cerebellum, with a compliant robot. We prove that our compliant approach outperforms the accuracy of the default factory-installed position control in a set of tasks used for addressing cerebellar motor behaviour: controlling six degrees of freedom (DoF) in (i) smooth movements, (ii) fast ballistic movements, and (iii) unstructured scenario compliant movements."

# Summary. An optional shortened abstract.
summary:

tags:
  - EDLUT
  - Neurorobotics
  - Cerebellum
featured: true

links:
 - name: "Journal"
   url: "https://ieeexplore.ieee.org/document/8880621"
url_pdf: https://arxiv.org/abs/2003.01033
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
projects: ['cerebrot','hbp']

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---
