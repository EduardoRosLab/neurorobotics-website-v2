---
title: 'A deep learning strategy to identify cell types across species from high-density extracellular recordings.'
authors:
  - "M. Beau"
  - "D. J. Herzfeld"
  - fnaveros
  - "M. E. Hemelt"
  - "F. D’Agostino"
  - "M. Oostland"
  - "A. Sánchez-López"
  - "Y. Y. Chung"
  - "M. Maibach"
  - "S. Kyranakis"
  - "H. N. Stabb"
  - "M. G. Martínez Lopera"
  - "A. Lajko"
  - "M. Zedler"
  - "S. Ohmae"
  - "N.J. Hall"
  - "B. A. Clark"
  - "D. Cohen"
  - "S. Lisberger"
  - "D. Kostadinov"
  - "C. Hull"
  - "M. Häusser"
  - "J. F. Medina"

author_notes:
date: '2025-04-17T17:44:35'
doi: '10.1016/j.cell.2025.01.041'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-04-17T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'Cell'
publication_short: 'Cell'

abstract: "High-density probes allow electrophysiological recordings from many neurons simultaneously across entire brain circuits but fail to reveal cell type. Here, we develop a strategy to identify cell types from extracellular recordings in awake animals and reveal the computational roles of neurons with distinct functional, molecular, and anatomical properties. We combine optogenetics and pharmacology using the cerebellum as a testbed to generate a curated ground-truth library of electrophysiological properties for Purkinje cells, molecular layer interneurons, Golgi cells, and mossy fibers. We train a semi-supervised deep learning classifier that predicts cell types with greater than 95% accuracy based on the waveform, discharge statistics, and layer of the recorded neuron. The classifier’s predictions agree with expert classification on recordings using different probes, in different laboratories, from functionally distinct cerebellar regions, and across species. Our classifier extends the power of modern dynamical systems analyses by revealing the unique contributions of simultaneously recorded cell types during behavior."

# Summary. An optional shortened abstract.
summary:

tags:
  - Cerebellum
  - Cerebellar cortex
  - Cell-type identification
  - Circuit mapping
  - Neuropixels
  - Variational autoencoder
  - Machine learning
  - Classification
featured: true

links:
 - name: "Journal"
   url: "https://www.cell.com/cell/abstract/S0092-8674(25)00110-2"
url_pdf: 'https://pmc.ncbi.nlm.nih.gov/articles/PMC10862837/pdf/nihpp-2024.01.30.577845v2.pdf'
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
projects: ['neuseqbot']

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---
