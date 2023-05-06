---
title: 'A multi-resolution approach for massively-parallel hardware-friendly optical flow estimation'
authors:
  - fbarranco
  - 'J. Díaz'
  - 'B. Pino'
  - eros

author_notes:
date: '2012-08-01T17:44:35+01:00'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2012-08-01T17:44:35+01:00'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'Journal of Visual Communication and Image Representation'
publication_short: 'J. of Vis. Comm. and Imag. Repr.'

abstract: "This paper presents a novel hardware-friendly motion estimation for real-time applications such as robotics or autonomous navigation. Our approach is based on the well-known Lucas & Kanade local algorithm, whose main problem is the unreliability of its estimations for large-range displacements. This disadvantage is solved in the literature by adding the sequential multiscale-with-warping extension, although it dramatically increases the computational cost. Our choice is the implementation of a multiresolution scheme that avoids the warping computation and allows the estimation of large-range motion. This alternative allows the parallel computation of the scale-by-scale motion estimation which makes the whole computation lighter and significantly reduces the processing time compared with the multiscale-with-warping approach. Furthermore, this last fact also means reducing the hardware resource cost for its potential implementation in digital hardware devices such as GPUs, ASICs, or FPGAs. In the discussion, we analyze the speedup of the multiresolution approach compared to the multiscale-with-warping scheme. For an FPGA implementation, we obtain a reduction of latency between 40% and 50% and a resource reduction of 30%. The final solution copes with large-range motion estimations with a simplified architecture very well-suited for customized digital hardware datapath implementations as well as current multicore architectures."

# Summary. An optional shortened abstract.
summary:

tags:
featured: false

links:
 - name: "Journal"
   url: "https://www.sciencedirect.com/science/article/pii/S1047320312001472"
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
