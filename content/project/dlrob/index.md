---
title: DLROB - Deep Learning for accurate movement of collaborative robotics
summary: The DLROB project is a national Spanish project funded by the Spanish National Research Agency  DLROB (TED2021-630 131294B-I00) funded by MCIN/AEI/ 10.13039/501100011033 and by European Union NextGenerationEU/PRTR.This project focuses on proposing a cobot dynamic modelling methodology and subsequent cobot control that are to be learnt rather than calculated, i.e., data-driven vs. equation-driven modelling and control.

tags:
  - Cobots
  - Deep-learning
  - Torque control
  - Non-rigid dynamics
date: '2023-02-26T10:57:53'

authors:
  - nluque

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Selecting the training data subset (a) Illustration of the trajectory sets to be used (b) Cobot Baxter whose dynamic model is learnt rather than analytically calculated
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

The International Federation of Robotics (IFR) reported around 3 million robots operating in 2020, a 10% increase compared to previous year. This ubiquitous robot presence makes the Human-Robot interaction (HRI) gradually become the focus of new robotic applications, in which a new generation of robots (collaborative robots) begins to coexist and physically interact with humans. Actually these collaborative robots, also known as cobots, are designed and intended to work with humans to reduce their burdens in lifting weights or doing laborious tasks leading the digital revolution in human-robot collaborative interaction. A cobot working hand in hand with a human entails a safe physical HRI, which implies the cobot´s performing in a complex unstructured environment in which human actions cannot be modelled. This demands the cobot behaviour to be autonomous, adaptive and safe. Achieving such behaviour can only be addressed considering the sensors, actuators and control architecture as a whole.

Importantly, we find the latest collaborative robot (cobot) generation incorporating elastic actuators to allow passive compliance and to help comply with safe HRI. But this makes cobot torque control with minimum force not suitable for classic control theory due to their complex non-linear dynamics. This project focuses on proposing a cobot dynamics modelling methodology and subsequent cobot control that are to be learnt rather than calculated, i.e., data-driven vs. equation-driven modelling and control. To that aim, we propose the integration of machine learning (ML) methods following a four stage methodology. (i) Cobot’s dynamic data acquisition, (ii) Neural Network architecture construction, (iii) Training & Validation, and (iv) Implementation of the solutions on a real cobot. To the best of our knowledge, DLROB is one of the first initiatives that apply ML to the development of dynamic models (direct and indirect) of cobots aiming the achievement of more robust and precise controllers and also simulators in complex robots with elastic joints (cobots) that allow safe HRI. This Model-Based approach will follow a dynamic modelling design following the constructive paradigm based on first Model-in-the-Loop (MIL) simulation through Software-in-the-Loop (SIL) simulation and finally Hardware-in-the-Loop (HIL) implementation. The final goal of this project aims to push current state-of-the-art safe human cobot interaction ensuring compliance torque control bringing cobots from factories to daily workplaces and social environments.
