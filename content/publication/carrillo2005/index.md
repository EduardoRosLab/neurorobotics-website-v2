---
title: 'Lookup Table Powered Neural Event-Driven Simulator'
authors:
  - rcarrillo
  - eros
  - 'E.M. Ortigosa'
  - 'B. Barbour'
  - 'R. Agís'

author_notes:
date: '2005-08-01T17:44:35+01:00'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2005-08-01T17:44:35+01:00'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: '8th Internacional Work Conference on Artificial Neural Networks'
publication_short: 'IWANN 2005'

abstract: "A novel method for efficiently simulating large scale realistic neural networks is described. Most information transmission in these networks is accomplished by the so called action potentials, events which are considerably sparse and well-localized in time. This facilitates a dramatic reduction of the computational load through the application of the event-driven simulation schemes. However, some complex neuronal models require the simulator to calculate large expressions, in order to update the neuronal state variables between these events. This requirement slows down these neural state updates, impeding the simulation of very active large neural populations in real-time. Moreover, neurons of some of these complex models produce firings (action potentials) some time after the arrival of the presynaptic potentials. The calculation of this delay involves the computation of expressions that sometimes are difficult to solve analytically. To deal with these problems, our method makes use of precalculated lookup tables for both, fast update of the neural variables and the prediction of the firing delays, allowing efficient simulation of large populations with detailed neural models."

# Summary. An optional shortened abstract.
summary:

tags:
featured: false

links:
 - name: "Journal"
   url: "https://doi.org/10.1007/11494669_22"
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
