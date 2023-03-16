---
title: 'VOR Adaptation on a Humanoid iCub Robot Using a Spiking Cerebellar Model'
authors:
  - fnaveros
  - nluque
  - eros
  - "Angelo Arleo"

author_notes:
date: '2019-01-25T17:44:35'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2019-01-25T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'IEEE Transactions on Cybernetics'
publication_short: 'IEEE Trans. Cybern.'

abstract: "We embed a spiking cerebellar model within an adaptive real-time (RT) control loop that is able to operate a real robotic body (iCub) when performing different vestibulo-ocular reflex (VOR) tasks. The spiking neural network computation, including event- and time-driven neural dynamics, neural activity, and spike-timing dependent plasticity (STDP) mechanisms, leads to a nondeterministic computation time caused by the neural activity volleys encountered during cerebellar simulation. This nondeterministic computation time motivates the integration of an RT supervisor module that is able to ensure a well-orchestrated neural computation time and robot operation. Actually, our neurorobotic experimental setup (VOR) benefits from the biological sensory motor delay between the cerebellum and the body to buffer the computational overloads as well as providing flexibility in adjusting the neural computation time and RT operation. The RT supervisor module provides for incremental countermeasures that dynamically slow down or speed up the cerebellar simulation by either halting the simulation or disabling certain neural computation features (i.e., STDP mechanisms, spike propagation, and neural updates) to cope with the RT constraints imposed by the real robot operation. This neurorobotic experimental setup is applied to different horizontal and vertical VOR adaptive tasks that are widely used by the neuroscientific community to address cerebellar functioning. We aim to elucidate the manner in which the combination of the cerebellar neural substrate and the distributed plasticity shapes the cerebellar neural activity to mediate motor adaptation. This paper underlies the need for a two-stage learning process to facilitate VOR acquisition."

# Summary. An optional shortened abstract.
summary:

tags:
  - Cerebellum
  - Robotics
  - Learning
featured: true

links:
 - name: "Journal"
   url: "https://ieeexplore.ieee.org/abstract/document/8653961"
url_pdf: 'http://arxiv.org/abs/2003.01409'
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
