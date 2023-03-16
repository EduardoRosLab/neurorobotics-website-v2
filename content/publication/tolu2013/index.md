+++
title = "Adaptive and predictive control of a simulated robot arm"
date = 2013-06-01T17:44:35+01:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Silvia Tolu", "Mauricio Vanegas", "Jesus A. Garrido", "Niceto R. Luque", "Eduardo Ros"]

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
abstract = "In this work, a basic cerebellar neural layer and a machine learning engine are embedded in a recurrent loop which avoids dealing with the motor error or distal error problem. The presented approach learns the motor control based on available sensor error estimates (position, velocity, and acceleration) without explicitly knowing the motor errors. The paper focuses on how to decompose the input into different components in order to facilitate the learning process using an automatic incremental learning model (locally weighted projection regression (LWPR) algorithm). LWPR incrementally learns the forward model of the robot arm and provides the cerebellar module with optimal pre-processed signals. We present a recurrent adaptive control architecture in which an adaptive feedback (AF) controller guarantees a precise, compliant, and stable control during the manipulation of objects. Therefore, this approach efficiently integrates a bio-inspired module (cerebellar circuitry) with a machine learning component (LWPR). The cerebellar-LWPR synergy makes the robot adaptable to changing conditions. We evaluate how this scheme scales for robot-arms of a high number of degrees of freedom (DOFs) using a simulated model of a robot arm of the new generation of light weight robots (LWRs)."
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
url_pdf = "tolu2013.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""
url_custom = [{name = "Journal", url = "http://www.worldscientific.com/doi/abs/10.1142/S012906571350010X "}]

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
