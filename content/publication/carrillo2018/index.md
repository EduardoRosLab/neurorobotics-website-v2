+++
title = "A Metric for Evaluating Neural Input Representation in Supervised Learning Networks"
date = 2018-12-25T17:44:35+01:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Richard R. Carrillo", "Francisco Naveros", "Eduardo Ros", "Niceto R. Luque"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = " Frontiers in neuroscience "
publication_short = "Front. Neurosci."

# Abstract and optional shortened version.
abstract = "Supervised learning has long been attributed to several feed-forward neural circuits within the brain, with particular attention being paid to the cerebellar granular layer. The focus of this study is to evaluate the input activity representation of these feed-forward neural networks. The activity of cerebellar granule cells is conveyed by parallel fibers and translated into Purkinje cell activity, which constitutes the sole output of the cerebellar cortex. The learning process at this parallel-fiber-to-Purkinje-cell connection makes each Purkinje cell sensitive to a set of specific cerebellar states, which are roughly determined by the granule-cell activity during a certain time window. A Purkinje cell becomes sensitive to each neural input state and, consequently, the network operates as a function able to generate a desired output for each provided input by means of supervised learning. However, not all sets of Purkinje cell responses can be assigned to any set of input states due to the network's own limitations (inherent to the network neurobiological substrate), that is, not all input-output mapping can be learned. A key limiting factor is the representation of the input states through granule-cell activity. The quality of this representation (e.g., in terms of heterogeneity) will determine the capacity of the network to learn a varied set of outputs. Assessing the quality of this representation is interesting when developing and studying models of these networks to identify those neuron or network characteristics that enhance this representation. In this study we present an algorithm for evaluating quantitatively the level of compatibility/interference amongst a set of given cerebellar states according to their representation (granule-cell activation patterns) without the need for actually conducting simulations and network training. The algorithm input consists of a real-number matrix that codifies the activity level of every considered granule-cell in each state. The capability of this representation to generate a varied set of outputs is evaluated geometrically, thus resulting in a real number that assesses the goodness of the representation."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "Carrillo2018.pdf"
url_preprint = "http://arxiv.org/abs/2003.01588"
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""
url_custom = [{name = "Journal", url = "https://www.frontiersin.org/articles/10.3389/fnins.2018.00913/full" }]

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
