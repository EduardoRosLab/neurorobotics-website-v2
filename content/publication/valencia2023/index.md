---
title: 'Bidirectional recurrent learning of inverse dynamic models for robots with elastic joints: a real-time real-world implementation'
authors:
  - "B. Valencia-Vidal"
  - eros
  - iabadia
  - nluque

author_notes:
date: '2023-06-08T17:44:35'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-06-08T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'Frontiers in Neurorobotics'
publication_short: 'Front. Neurorobotics'

abstract: "Collaborative robots, or cobots, are designed to work alongside humans and to alleviate their physical burdens, such as lifting heavy objects or performing tedious tasks. Ensuring the safety of human–robot interaction (HRI) is paramount for effective collaboration. To achieve this, it is essential to have a reliable dynamic model of the cobot that enables the implementation of torque control strategies. These strategies aim to achieve accurate motion while minimizing the amount of torque exerted by the robot. However, modeling the complex non-linear dynamics of cobots with elastic actuators poses a challenge for traditional analytical modeling techniques. Instead, cobot dynamic modeling needs to be learned through data-driven approaches, rather than analytical equation-driven modeling. In this study, we propose and evaluate three machine learning (ML) approaches based on bidirectional recurrent neural networks (BRNNs) for learning the inverse dynamic model of a cobot equipped with elastic actuators. We also provide our ML approaches with a representative training dataset of the cobot's joint positions, velocities, and corresponding torque values. The first ML approach uses a non-parametric configuration, while the other two implement semi-parametric configurations. All three ML approaches outperform the rigid-bodied dynamic model provided by the cobot's manufacturer in terms of torque precision while maintaining their generalization capabilities and real-time operation due to the optimized sample dataset size and network dimensions. Despite the similarity in torque estimation of these three configurations, the non-parametric configuration was specifically designed for worst-case scenarios where the robot dynamics are completely unknown. Finally, we validate the applicability of our ML approaches by integrating the worst-case non-parametric configuration as a controller within a feedforward loop. We verify the accuracy of the learned inverse dynamic model by comparing it to the actual cobot performance. Our non-parametric architecture outperforms the robot's default factory position controller in terms of accuracy."

# Summary. An optional shortened abstract.
summary:

tags:
  - Neural networks
  - Compliant Robots
featured: true

links:
 - name: "Journal"
   url: "https://www.frontiersin.org/articles/10.3389/fnbot.2023.1166911/full"
url_pdf: 'valencia2023.pdf'
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
projects: ['spikeage','dlrob']

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---
