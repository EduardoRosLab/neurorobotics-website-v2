+++
title = "On-chip semidense representation map for dense visual features driven by attention processes"
date = 2016-08-01T17:44:35+01:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Sara Granados", "Francisco Barranco", "Sonia Mota", "Javier Díaz", "Eduardo Ros"]
    
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
publication = "Journal of Real-Time Image Processing"
publication_short = "J. of Real-Time Imag. Proc."

# Abstract and optional shortened version.
abstract = "We describe an intelligent scheme to condense dense vision features, efficiently reducing the size of representation maps and keeping relevant information for further processing during subsequent stages. We have integrated our condensation algorithm in a low-level-vision system that obtains several vision-features in real-time working on an FPGA. Within this framework, our condensation algorithm allows for the transfer of information from the FPGA device (or processing chip) to any co-processor (from embedded ones to external PCs or DSPs) under technological constraints (such as bandwidth, memory and performance ones). Our condensation core processes 1024 × 1024 resolution images at up to 90 fps. Hence, our condensation module performs this process introducing an insignificant delay in the vision system. A hardware implementation usually implies a simplified version of the vision-feature extractor. Therefore, our condensation process inherently regularizes low-level-vision features, effectively reducing discontinuities and errors. The semidense representation obtained is compatible with mid-/high-level-vision modules, usually implemented as software components. In addition, our versatile semidense map is ready to receive feedback from attention processes, integrating task-driven attention (i.e. top-down information) in real time. Thus, the main advantages of this core are: real-time throughput, versatility, inherent regularization, scalability and feedback from other stages."
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
url_pdf = ""
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""
url_custom = [{name = "Journal", url = "https://link.springer.com/article/10.1007/s11554-012-0320-3" }]

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

