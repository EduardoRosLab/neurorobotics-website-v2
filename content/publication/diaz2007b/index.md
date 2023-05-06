---
title: 'Image Processing Architecture for Local Features Computation'
authors:
  - "J. Díaz"
  - eros
  - 'S. Mota'
  - rcarrillo

author_notes:
date: '2007-08-30T17:44:35+01:00'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2007-08-30T17:44:35+01:00'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 'International Workshop on Applied Reconfigurable Computing'
publication_short: 'ARC07'

abstract: "Quadrature filters are widely used in the Computer Vision community because of their biological support and also because they allow an efficient coding of local features. They can be used to estimate local energy, phase, and orientation or even allow classifying image textures. The drawback of this image decomposition is that requires performing intensive pixel-wise computations which makes it impossible to use in most real-time applications. In this contribution we present a high performance architecture capable of extracting local phase, orientation and energy at a rate of 56.5 Mpps. Taking into account that FPGA resources are constrained, we have implemented a steerable filters bank (instead of Gabor filters bank) based on Second Order Gaussian derivatives. This method has the advantage that the filters are 2-D separable and each image orientation can be extracted from a basic set of seven filters. We present in this paper the proposed architecture and analyze the quantization degradation error generated by using fixed point arithmetic. We show the resources consumption, the performance and finally, we present some results from the developed system."

# Summary. An optional shortened abstract.
summary:

tags:
featured: false

links:
 - name: "Journal"
   url: "https://doi.org/10.1007/978-3-540-71431-6_24"
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