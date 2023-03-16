+++
title = "Distributed cerebellar plasticity implements adaptable gain control in a manipulation task: a closed-loop robotic simulation"
date = 2013-10-09T17:44:35+01:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Jesus A. Garrido", "Niceto R. Luque", "Egidio D‘Angelo", "Eduardo Ros"]

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
publication = "Frontiers in Neural Circuits"
publication_short = "Front. Neural Circuits"

# Abstract and optional shortened version.
abstract = "Adaptable gain regulation is at the core of the forward controller operation performed by the cerebro-cerebellar loops and it allows the intensity of motor acts to be finely tuned in a predictive manner. In order to learn and store information about body-object dynamics and to generate an internal model of movement, the cerebellum is thought to employ long-term synaptic plasticity. LTD at the PF-PC synapse has classically been assumed to subserve this function (Marr, 1969). However, this plasticity alone cannot account for the broad dynamic ranges and time scales of cerebellar adaptation. We therefore tested the role of plasticity distributed over multiple synaptic sites (Hansel et al., 2001; Gao et al., 2012) by generating an analog cerebellar model embedded into a control loop connected to a robotic simulator. The robot used a three-joint arm and performed repetitive fast manipulations with different masses along an 8-shape trajectory. In accordance with biological evidence, the cerebellum model was endowed with both LTD and LTP at the PF-PC, MF-DCN and PC-DCN synapses. This resulted in a network scheme whose effectiveness was extended considerably compared to one including just PF-PC synaptic plasticity. Indeed, the system including distributed plasticity reliably self-adapted to manipulate different masses and to learn the arm-object dynamics over a time course that included fast learning and consolidation, along the lines of what has been observed in behavioral tests. In particular, PF-PC plasticity operated as a time correlator between the actual input state and the system error, while MF-DCN and PC-DCN plasticity played a key role in generating the gain controller. This model suggests that distributed synaptic plasticity allows generation of the complex learning properties of the cerebellum. The incorporation of further plasticity mechanisms and of spiking signal processing will allow this concept to be extended in a more realistic computational scenario."
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
url_pdf = "garrido2013b.pdf"
url_preprint = ""
url_code = "https://senselab.med.yale.edu/modeldb/ShowModel.cshtml?model=150067"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""
url_custom = [{name = "Journal", url = "https://www.frontiersin.org/articles/10.3389/fncir.2013.00159/full "}]

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
