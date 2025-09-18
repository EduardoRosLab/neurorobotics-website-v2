---
title: 'Distributed cerebellar plasticity implements adaptable gain control in a manipulation task: a closed-loop robotic simulation'
authors:
  - jgarrido
  - nluque
  - "E. D'Angelo"
  - eros

author_notes:
date: '2013-10-09T17:44:35+01:00'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2013-10-09T17:44:35+01:00'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'Frontiers in Neural Circuits'
publication_short: 'Front. Neural Circuits'

abstract: "Adaptable gain regulation is at the core of the forward controller operation performed by the cerebro-cerebellar loops and it allows the intensity of motor acts to be finely tuned in a predictive manner. In order to learn and store information about body-object dynamics and to generate an internal model of movement, the cerebellum is thought to employ long-term synaptic plasticity. LTD at the PF-PC synapse has classically been assumed to subserve this function (Marr, 1969). However, this plasticity alone cannot account for the broad dynamic ranges and time scales of cerebellar adaptation. We therefore tested the role of plasticity distributed over multiple synaptic sites (Hansel et al., 2001; Gao et al., 2012) by generating an analog cerebellar model embedded into a control loop connected to a robotic simulator. The robot used a three-joint arm and performed repetitive fast manipulations with different masses along an 8-shape trajectory. In accordance with biological evidence, the cerebellum model was endowed with both LTD and LTP at the PF-PC, MF-DCN and PC-DCN synapses. This resulted in a network scheme whose effectiveness was extended considerably compared to one including just PF-PC synaptic plasticity. Indeed, the system including distributed plasticity reliably self-adapted to manipulate different masses and to learn the arm-object dynamics over a time course that included fast learning and consolidation, along the lines of what has been observed in behavioral tests. In particular, PF-PC plasticity operated as a time correlator between the actual input state and the system error, while MF-DCN and PC-DCN plasticity played a key role in generating the gain controller. This model suggests that distributed synaptic plasticity allows generation of the complex learning properties of the cerebellum. The incorporation of further plasticity mechanisms and of spiking signal processing will allow this concept to be extended in a more realistic computational scenario."

# Summary. An optional shortened abstract.
summary:

tags:
  - Spiking Neuronal networks
  - Cerebellum
  - Learning

featured: false

links:
 - name: "Journal"
   url: "https://www.frontiersin.org/articles/10.3389/fncir.2013.00159/full"
url_pdf: 'garrido2013b'
url_code: 'https://senselab.med.yale.edu/modeldb/ShowModel.cshtml?model=150067'
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
