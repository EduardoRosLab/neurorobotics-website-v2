+++
title = "Event-Driven Simulation Scheme for Spiking Neural Networks Using Lookup Tables to Characterize Neuronal Dynamics"
date = "2006-12-01"
authors = ['E. Ros', 'R. Carrillo', 'E.M. Ortigosa', 'B. Barbour', 'R. Agís']
publication_types = ["2"]
publication = "Neural Computation"
abstract = "Nearly all neuronal information processing and interneuronal communication in the brain involves action potentials, or spikes, which drive the short-term synaptic dynamics of neurons, but also their long-term dynamics, via synaptic plasticity. In many brain structures, action potential activity is considered to be sparse. This sparseness of activity has been exploited to reduce the computational cost of large-scale network simulations, through the development of event-driven simulation schemes. However, existing event-driven simulations schemes use extremely simplified neuronal models. Here, we implement and evaluate critically an event-driven algorithm (ED-LUT) that uses precalculated look-up tables to characterize synaptic and neuronal dynamics. This approach enables the use of more complex (and realistic) neuronal models or data in representing the neurons, while retaining the advantage of high-speed simulation. We demonstrate the method's application for neurons containing exponential synaptic conductances, thereby implementing shunting inhibition, a phenomenon that is critical to cellular computation. We also introduce an improved two-stage event-queue algorithm, which allows the simulations to scale efficiently to highly connected networks with arbitrary propagation delays. Finally, the scheme readily accommodates implementation of synaptic plasticity mechanisms that depend on spike timing, enabling future simulations to explore issues of long-term learning and adaptation in large-scale networks."
selected = false
tags = ["EDLUT"]
url_pdf = ""
url_custom = [{name = "Journal", url = "https://doi.org/10.1162/neco.2006.18.12.2959"}]
+++
