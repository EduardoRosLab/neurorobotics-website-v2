+++
title = "From sensors to spikes: evolving receptive fields to enhance sensorimotor information in a robot-arm"
date = 2012-08-01T17:44:35+01:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Niceto R. Luque", "Jesús A. Garrido", "Jarno Ralli", "Juan L. Jiménez", "Eduardo Ros"]

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
publication = "International Journal of Neural Systems"
publication_short = "Int. J. Neur. Syst."

# Abstract and optional shortened version.
abstract = "In biological systems, instead of actual encoders at different joints, proprioception signals are acquired through distributed receptive fields. In robotics, a single and accurate sensor output per link (encoder) is commonly used to track the position and the velocity. Interfacing bio-inspired control systems with spiking neural networks emulating the cerebellum with conventional robots is not a straight forward task. Therefore, it is necessary to adapt this one-dimensional measure (encoder output) into a multidimensional space (inputs for a spiking neural network) to connect, for instance, the spiking cerebellar architecture; i.e. a translation from an analog space into a distributed population coding in terms of spikes. This paper analyzes how evolved receptive fields (optimized towards information transmission) can efficiently generate a sensorimotor representation that facilitates its discrimination from other \"sensorimotor states\". This can be seen as an abstraction of the Cuneate Nucleus (CN) functionality in a robot-arm scenario. We model the CN as a spiking neuron population coding in time according to the response of mechanoreceptors during a multi-joint movement in a robot joint space. An encoding scheme that takes into account the relative spiking time of the signals propagating from peripheral nerve fibers to second-order somatosensory neurons is proposed. Due to the enormous number of possible encodings, we have applied an evolutionary algorithm to evolve the sensory receptive field representation from random to optimized encoding. Following the nature-inspired analogy, evolved configurations have shown to outperform simple hand-tuned configurations and other homogenized configurations based on the solution provided by the optimization engine (evolutionary algorithm). We have used artificial evolutionary engines as the optimization tool to circumvent nonlinearity responses in receptive fields."
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
tags = []

# Links (optional).
url_pdf = "luque2012.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""
url_custom = [{name = "Journal", url = "http://www.worldscientific.com/doi/abs/10.1142/S012906571250013X "}]

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
