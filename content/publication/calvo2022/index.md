---
title: 'Black-box and surrogate optimization for tuning spiking neural models of striatum plasticity'
authors:
  - "Nicolás C. Cruz"
  - agonzalez
  - "Juana L. Redondo"
  - jgarrido
  - "Eva M. Ortigosa"
  - "Pilar M. Ortigosa"

author_notes:
date: '2022-10-20T17:44:35'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-10-20T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'Frontiers in Neuroinformatics'
publication_short: 'Front. Neuroinform.'

abstract: "The basal ganglia (BG) is a brain structure that has long been proposed to play an essential role in action selection, and theoretical models of spiking neurons have tried to explain how the BG solves this problem. A recently proposed functional and biologically inspired network model of the striatum (an important nucleus of the BG) is based on spike-timing-dependent eligibility (STDE) and captured important experimental features of this nucleus. The model can recognize complex input patterns and consistently choose rewarded actions to respond to such sensory inputs. However, model tuning is challenging due to two main reasons. The first is the expert knowledge required, resulting in tedious and potentially biased trial-and-error procedures. The second is the computational cost of assessing model configurations (approximately 1.78 h per evaluation). This study addresses the model tuning problem through numerical optimization. Considering the cost of assessing solutions, the selected methods stand out due to their low requirements for solution evaluations and compatibility with high-performance computing. They are the SurrogateOpt solver of Matlab and the RBFOpt library, both based on radial basis function approximations, and DIRECT-GL, an enhanced version of the widespread black-box optimizer DIRECT. Besides, a parallel random search serves as a baseline reference of the outcome of opting for sophisticated methods. SurrogateOpt turns out to be the best option for tuning this kind of model. It outperforms, on average, the quality of the configuration found by an expert and works significantly faster and autonomously. RBFOpt and the random search share the second position, but their average results are below the option found by hand. Finally, DIRECT-GL follows this line becoming the worst-performing method."

# Summary. An optional shortened abstract.
summary:

tags:
  - Basal Ganglia
  - Reinforcement Learning
  - Spiking Neuronal Networks
  - Evolutionary algorithms

featured: false

links:
 - name: "Journal"
   url: "https://www.frontiersin.org/articles/10.3389/fninf.2022.1017222/full"
url_pdf: 'calvo2022'
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
projects: ['cerebio','hbp','intsenso']

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---
