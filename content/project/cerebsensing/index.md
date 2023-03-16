---
title: CEREBSENSING - Cerebellar Distributed Plasticity Towards Active Sensing and Motor Control
summary: CEREBSENSING is a H2020 Marie Sklodowska-Curie Action (IF) aiming to understand how the cerebellum processes sensorial information coming from the cerebral cortex by using computational models embedded in realistic perception-action simulations.
tags:
  - Cerebellum
  - Neurorobotics
date: '2015-02-17T10:57:53'

authors:
  - jgarrido

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
#  caption: Photo by rawpixel on Unsplash
#  focal_point: Smart

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ''
---

Although robotic system capabilities have experienced a remarkable boost in the last decades, their movements still remain far from looking dexterous (expect fast and repetitive and mainly open-loop industrial approaches in well controlled conditions). If state-of-the-art robotic systems could operate outside the highly constrained environments they are currently restricted to, a wide-variety of applications in manufacturing, medicine, elderly support and general domestic applications would open up. A crucial capability is still missing: the ability to perceive, understand and discriminate relevant information in complex own movement realizations. Late experimentation in humans has evidenced that the cerebellum enhances proprioception through the so-called active sensing. Thus, active proprioception takes advantage of previously stored dynamics models of movements and efferent copies of the motor commands to predict the sensorial consequences of the actions, outperforming in this way the passive-sensing counterpart. Interestingly, the cerebellar forward model suggests that this sensorial prediction may enhance the motor control by avoiding the effect of the sensorial feedback delay (estimated around 100ms).

Computational models of the cerebellum have been proposed mainly in motor control, but experimental studies in the last years have shown that the cerebellum is also involved in other cognitive processes such as attention, language, or even sensorial integration and discrimination. Specifically, the Marr-Albus’ model in late 1960s proposed that cerebellar learning capabilities emerged from the existence of plasticity in the parallel fibers (PFs) to Purkinje cell (PCs) synapses. According to that theory, PF-PC plasticity is driven by a teaching signal reaching the PCs through the climbing fibers (CF) from the Inferior Olive (IO). This model has provided the basis for solving simple associative tasks such as eye-blink conditioning or ocular reflexes and more complex manipulation tasks. However, two experimental discoveries have recently questioned this simple model: (i) late anatomical studies have shown that cerebellar granular layer cells (granule -GrCs-  and Golgi -GoCs- ) receive multimodal convergent connections carrying separate sensory (proprioceptive) and motor-related information (supporting the cerebellar role in sensory processing) and, (ii) synaptic sites in the cerebellar granular layer and deep cerebellar nuclei (DCN) (additionally to the originally proposed PF-PC) have shown traces of plasticity. Computational models have emerged as a powerful tool in order to explain the role of these additional plasticity sites. Indeed, plasticity in the mossy fibers (MF) - DCN connection (driven by the PC activity) and PC-DCN synapses has been proposed to support learning consolidation.

The cerebellar granular layer (that paradoxically has received considerably less attention in computational modelling) seems to play a major role in sensorial and motor information processing. Early studies proposed the granular layer to perform sparse recoding of the MF incoming signals, likely as a result of the combinatorial connection of the MF afferents. Recently, experiments have supported the existence of plasticity in the MF-GrC synapses, but computational models have failed on proposing new theories about its role.

CEREBSENSING aims to understand how the cerebellum processes sensorial information coming from the cerebral cortex by using computational models embedded in realistic perception-action simulations. More specifically, this project has created computational models of the cerebellum including plasticity at the cerebellar granular layer. Our simulations suggest that plasticity at the inhibitory interneuron afferents (namely, the Golgi cells) is especially effective in creating sparse representations of the cerebellar input information. The enhanced sensorial representation at the granular layer provides the basis for forward sensorial consequence estimation at the subsequent layer (Purkinje cells) as it emerges from the integration of the granular layer in a whole-cerebellum model controlling the saccade movements. Finally, the application of the granular layer structure into a visual digit classification task has evidenced how this neuronal network can be applied for real-life applications.

This project has been funded by the European Commission as part of the H2020 Marie Sklowdowsca-Curie Actions (MSCA-IF-2014-653019).
