---
title: 'Adaptive and predictive control of a simulated robot arm'
authors:
  - "S. Tolu"
  - "M. Vanegas"
  - jgarrido
  - nluque
  - eros

author_notes:
date: '2013-06-01T17:44:35'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2013-06-01T17:44:35'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: "International Journal of Neural Systems"
publication_short: "Int. J. Neur. Syst."

abstract: "In this work, a basic cerebellar neural layer and a machine learning engine are embedded in a recurrent loop which avoids dealing with the motor error or distal error problem. The presented approach learns the motor control based on available sensor error estimates (position, velocity, and acceleration) without explicitly knowing the motor errors. The paper focuses on how to decompose the input into different components in order to facilitate the learning process using an automatic incremental learning model (locally weighted projection regression (LWPR) algorithm). LWPR incrementally learns the forward model of the robot arm and provides the cerebellar module with optimal pre-processed signals. We present a recurrent adaptive control architecture in which an adaptive feedback (AF) controller guarantees a precise, compliant, and stable control during the manipulation of objects. Therefore, this approach efficiently integrates a bio-inspired module (cerebellar circuitry) with a machine learning component (LWPR). The cerebellar-LWPR synergy makes the robot adaptable to changing conditions. We evaluate how this scheme scales for robot-arms of a high number of degrees of freedom (DOFs) using a simulated model of a robot arm of the new generation of light weight robots (LWRs)."
# Summary. An optional shortened abstract.
summary:

tags:
featured: false

links:
 - name: "Journal"
   url: "http://www.worldscientific.com/doi/abs/10.1142/S012906571350010X"
url_pdf: "tolu2013.pdf"
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
