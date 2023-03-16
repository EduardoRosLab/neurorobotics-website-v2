+++
title = "A spiking neural simulator integrating event-driven and time-driven computation schemes using parallel CPU-GPU co-processing: a case study"
date = 2015-07-01T17:44:35+01:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Francisco Naveros", "Niceto R. Luque",  "Jesús A. Garrido", "Richard R. Carrillo", "Mancia Anguita", "Eduardo Ros"]

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
publication = "IEEE Transactions on Neural Networks and Learning Systems"
publication_short = "IEEE Trans. Neural Netw. Learn. Syst."

# Abstract and optional shortened version.
abstract = "Time-driven simulation methods in traditional CPU architectures perform well and precisely when simulating small-scale spiking neural networks. Nevertheless, they still have drawbacks when simulating large-scale systems. Conversely, event-driven simulation methods in CPUs and time-driven simulation methods in graphic processing units (GPUs) can outperform CPU time-driven methods under certain conditions. With this performance improvement in mind, we have developed an event-and-time-driven spiking neural network simulator suitable for a hybrid CPU-GPU platform. Our neural simulator is able to efficiently simulate bio-inspired spiking neural networks consisting of different neural models, which can be distributed heterogeneously in both small layers and large layers or subsystems. For the sake of efficiency, the low-activity parts of the neural network can be simulated in CPU using event-driven methods while the high-activity subsystems can be simulated in either CPU (a few neurons) or GPU (thousands or millions of neurons) using time-driven methods. In this brief, we have undertaken a comparative study of these different simulation methods. For benchmarking the different simulation methods and platforms, we have used a cerebellar-inspired neural-network model consisting of a very dense granular layer and a Purkinje layer with a smaller number of cells (according to biological ratios). Thus, this cerebellar-like network includes a dense diverging neural layer (increasing the dimensionality of its internal representation and sparse coding) and a converging neural layer (integration) similar to many other biologically inspired and also artificial neural networks."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["EDLUT"]

# Links (optional).
url_pdf = "pdf/naveros2015.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""
url_custom = [{name = "Journal", url = "http://ieeexplore.ieee.org/abstract/document/6883192/" }]

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

