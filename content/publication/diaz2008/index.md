---
title: 'Local image phase, energy and orientation extraction using FPGAs'
authors:
  - "J. Díaz"
  - eros
  - 'S. Mota'
  - rcarrillo

author_notes:
date: '2008-08-30T17:44:35+01:00'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2008-08-30T17:44:35+01:00'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'International Journal of Electronics'
publication_short: 'Int. J. Electronics'

abstract: "Local features such as phase, energy and orientation have been widely used in the literature for multiple computer vision applications such as edge detection, texture analysis, motion estimation, depth computation, etc. They can be computed using wavelet image decomposing based on Quadrature filters tuned at different scales and orientations. Although this represents a very powerful image analysis technique, its feasibility for real-time domain applications is still beyond current computer capabilities due to the high demand of computational resources. In this article, we present an architecture developed for real-time processing of these features using reconfigurable hardware. Although, to the best of our knowledge, previous implementations of Gabor or steerable filters on chip already exist, none of them provides energy, phase, and orientation information at the same time. We show how to implement quadrature filters based on Gaussian derivatives. We develop a hardware friendly technique to interpolate between a multi-oriented filter bank to compute features at their main orientation which has not been used before. We finally describe the system resource requirements, performance and some system illustrative results."

# Summary. An optional shortened abstract.
summary:

tags:
featured: false

links:
 - name: "Journal"
   url: "https://doi.org/10.1080/00207210801941200"
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
