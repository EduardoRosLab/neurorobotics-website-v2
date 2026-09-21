---
# An instance of the Blank widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: blank

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title:
subtitle:

design:
  columns: '1'
  background:
#    image: coders.jpg
    image_darken: 0
    image_parallax: false
    image_position: center
#    image_size: cover
    text_color_light: false
  spacing:
    padding: ['20px', '0', '20px', '0']
advanced:
  css_class: fullscreen
---

## From brain models to adaptive machines

The **Applied Computational Neuroscience** (ACN) Group is part of the [Computer Engineering, Automation and Robotics Department](https://icar.ugr.es/) at [University of Granada](https://www.ugr.es). Led by Prof. Eduardo Ros, we develop computational tools to understand brain information processing and motor control.

{{< youtube aPaLzIzUFgU >}}

We are experts in simulating neural centres (such as cerebellum, inferior olive, basal ganglia and the visual system) both off-line (in large parallel computers) or in real-time (towards embedded simulations) with a robot on the loop (closed perception-action loops).

Among other potential application domains, rehabilitation, control schemes for robots interacting safely with humans and reverse engineering of human brain system are our focus.

## Research focus

### Computational neuroscience

We simulate biologically plausible neural systems at different levels of detail to contrast working hypotheses and evaluate how computational features are supported by the physiological substrate. We can run large-scale off-line simulations as well as medium-scale models for embedded systems and robotics. For this purpose, we use established simulators such as NEST and our own real-time simulator
([EDLUT](https://github.com/EduardoRosLab/edlut)) optimized for real-time (making intensive use of parallel computing at the CPU and GPU levels).

### Neurorobotics

Robots with low-power actuators and soft, flexible materials can be inherently safe, but their dynamics may lack an analytic reference model. We use biologically inspired adaptive control—based on model acquisition and retrieval—to embed safer control loops for robots interacting with people.
