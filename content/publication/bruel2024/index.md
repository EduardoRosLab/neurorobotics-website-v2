---
title: 'The spinal cord facilitates cerebellar upper limb motor learning and control; inputs from neuromusculoskeletal simulation'
authors:
  - "A. Bruel"
  - iabadia
  - "T. Collin"
  - "I. Sakr"
  - "H. Lorach"
  - nluque
  - eros
  - "A. Ijspeert"

author_notes:
date: '2024-01-08T17:44:35'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-08T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'Plos Computational Biology'
publication_short: 'Plos Comp. Biol.'

abstract: "Complex interactions between brain regions and the spinal cord (SC) govern body motion, which is ultimately driven by muscle activation. Motor planning or learning are mainly conducted at higher brain regions, whilst the SC acts as a brain-muscle gateway and as a motor control centre providing fast reflexes and muscle activity regulation. Thus, higher brain areas need to cope with the SC as an inherent and evolutionary older part of the body dynamics. Here, we address the question of how SC dynamics affects motor learning within the cerebellum; in particular, does the SC facilitate cerebellar motor learning or constitute a biological constraint? We provide an exploratory framework by integrating biologically plausible cerebellar and SC computational models in a musculoskeletal upper limb control loop. The cerebellar model, equipped with the main form of cerebellar plasticity, provides motor adaptation; whilst the SC model implements stretch reflex and reciprocal inhibition between antagonist muscles. The resulting spino-cerebellar model is tested performing a set of upper limb motor tasks, including external perturbation studies. A cerebellar model, lacking the implemented SC model and directly controlling the simulated muscles, was also tested in the same. The performances of the spino-cerebellar and cerebellar models were then compared, thus allowing directly addressing the SC influence on cerebellar motor adaptation and learning, and on handling external motor perturbations. Performance was assessed in both joint and muscle space, and compared with kinematic and EMG recordings from healthy participants. The differences in cerebellar synaptic adaptation between both models were also studied. We conclude that the SC facilitates cerebellar motor learning; when the SC circuits are in the loop, faster convergence in motor learning is achieved with simpler cerebellar synaptic weight distributions. The SC is also found to improve robustness against external perturbations, by better reproducing and modulating muscle cocontraction patterns."

# Summary. An optional shortened abstract.
summary:

tags:
  - Neural networks
  - Compliant Robots
featured: true

links:
 - name: "Journal"
   url: "https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1011008"
url_pdf: 'bruel2024.pdf'
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
projects: ['hbp','spikeage','dlrob','musclebot']

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---
