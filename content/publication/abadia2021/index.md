---
title: 'A cerebellar-based solution to the nondeterministic time delay problem in robotic control'
authors:
  - iabadia
  - fnaveros
  - eros
  - rcarrillo
  - nluque

author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  -
  - 'Equal contribution'
  - 'Equal contribution'
date: '2021-09-08T17:44:35'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-09-08T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.

publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: 'Science Robotics'
publication_short: 'Science Robotics'

abstract: "The presence of computation and transmission-variable time delays within a robotic control loop is a major cause of instability, hindering safe human-robot interaction (HRI) under these circumstances. Classical control theory has been adapted to counteract the presence of such variable delays; however, the solutions provided to date cannot cope with HRI robotics inherent features. The highly nonlinear dynamics of HRI cobots (robots intended for human interaction in collaborative tasks), together with the growing use of flexible joints and elastic materials providing passive compliance, prevent traditional control solutions from being applied. Conversely, human motor control natively deals with low power actuators, nonlinear dynamics, and variable transmission time delays. The cerebellum, pivotal to human motor control, is able to predict motor commands by correlating current and past sensorimotor signals, and to ultimately compensate for the existing sensorimotor human delay (tens of milliseconds). This work aims at bridging those inherent features of cerebellar motor control and current robotic challenges—namely, compliant control in the presence of variable sensorimotor delays. We implement a cerebellar-like spiking neural network (SNN) controller that is adaptive, compliant, and robust to variable sensorimotor delays by replicating the cerebellar mechanisms that embrace the presence of biological delays and allow motor learning and adaptation."

# Summary. An optional shortened abstract.
summary:

tags:
  - EDLUT
  - Compliant Robots
  - Cerebellum
featured: true

links:
 - name: "Journal"
   url: "https://www.science.org/doi/10.1126/scirobotics.abf2756"
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
projects: ['cerebio','hbp','neuseqbot','intsenso']

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---
