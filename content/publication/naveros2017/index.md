---
title: 'Event-and time-driven techniques using parallel CPU-GPU co-processing for spiking neural networks'
authors:
  - fnaveros
  - jgarrido
  - rcarrillo
  - eros
  - nluque


author_notes:
date: '2017-02-16T17:44:35'
doi: ''


# Schedule page publish date (NOT publication's date).
publishDate: '2017-02-16T17:44:35'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'Frontiers in Neuroinformatics'
publication_short: 'Front. Neuroinform.'

abstract: "Modeling and simulating the neural structures which make up our central neural system is instrumental for deciphering the computational neural cues beneath. Higher levels of biological plausibility usually impose higher levels of complexity in mathematical modeling, from neural to behavioral levels. This paper focuses on overcoming the simulation problems (accuracy and performance) derived from using higher levels of mathematical complexity at a neural level. This study proposes different techniques for simulating neural models that hold incremental levels of mathematical complexity: leaky integrate-and-fire (LIF), adaptive exponential integrate-and-fire (AdEx), and Hodgkin-Huxley (HH) neural models (ranged from low to high neural complexity). The studied techniques are classified into two main families depending on how the neural-model dynamic evaluation is computed: the event-driven or the time-driven families. Whilst event-driven techniques pre-compile and store the neural dynamics within look-up tables, time-driven techniques compute the neural dynamics iteratively during the simulation time. We propose two modifications for the event-driven family: a look-up table recombination to better cope with the incremental neural complexity together with a better handling of the synchronous input activity. Regarding the time-driven family, we propose a modification in computing the neural dynamics: the bi-fixed-step integration method. This method automatically adjusts the simulation step size to better cope with the stiffness of the neural model dynamics running in CPU platforms. One version of this method is also implemented for hybrid CPU-GPU platforms. Finally, we analyze how the performance and accuracy of these modifications evolve with increasing levels of neural complexity. We also demonstrate how the proposed modifications which constitute the main contribution of this study systematically outperform the traditional event- and time-driven techniques under increasing levels of neural complexity."

# Summary. An optional shortened abstract.
summary:

tags:
  - simulation
  - EDLUT
  - Spiking Neural Networks
featured: false

links:
 - name: "Journal"
   url: "https://www.frontiersin.org/articles/10.3389/fninf.2017.00007/full"
url_pdf: 'naveros2017.pdf'
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
projects: ['cerebsensing','hbp']

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---
