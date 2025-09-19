---
title: 'A neuromechanics solution for adjustable robot compliance and accuracy'
authors:
  - iabadia
  - "A. Bruel"
  - "G. Courtine"
  - "A. Ijspeert"
  - eros
  - nluque

author_notes:
date: '2025-01-28T11:45:00'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-01-28T11:45:10Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.

publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: 'Science Robotics'
publication_short: 'Science Robotics'

abstract: "Robots have to adjust their motor behavior to changing environments and variable task requirements to successfully operate in the real world and physically interact with humans. Thus, robotics strives to enable a broad spectrum of adjustable motor behavior, aiming to mimic the human ability to function in unstructured scenarios. In humans, motor behavior arises from the integrative action of the central nervous system and body biomechanics; motion must be understood from a neuromechanics perspective. Nervous regions such as the cerebellum facilitate learning, adaptation, and coordination of our motor responses, ultimately driven by muscle activation. Muscles, in turn, self-stabilize motion through mechanical viscoelasticity. In addition, the agonist-antagonist arrangement of muscles surrounding joints enables cocontraction, which can be regulated to enhance motion accuracy and adapt joint stiffness, thereby providing impedance modulation and broadening the motor repertoire. Here, we propose a control solution that harnesses neuromechanics to enable adjustable robot motor behavior. Our solution integrates a muscle model that replicates mechanical viscoelasticity and cocontraction together with a cerebellar network providing motor adaptation. The resulting cerebello-muscular controller drives the robot through torque commands in a feedback control loop. Changes in cocontraction modify the muscle dynamics, and the cerebellum provides motor adaptation without relying on prior analytical solutions, driving the robot in different motor tasks, including payload perturbations and operation across unknown terrains. Experimental results show that cocontraction modulates robot stiffness, performance accuracy, and robustness against external perturbations. Through cocontraction modulation, our cerebello-muscular torque controller enables a broad spectrum of robot motor behavior."

# Summary. An optional shortened abstract.
summary:

tags:
  - EDLUT
  - Compliant Robots
  - Cerebellum
  - Neuromechanics
  - Human-Robot Interaction
  - Adjustable behavior
  - Muscle dynamics
  - Spinal Cord
featured: true

links:
 - name: "Journal"
   url: "https://www.science.org/doi/full/10.1126/scirobotics.adp2356"
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
caption: 'Drawing inspiration from neuromechanics for adjustable robot motor behavior'
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ['musclebot', 'trembleice', 'dlrob', 'hbp']

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---
