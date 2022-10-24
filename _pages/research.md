---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

1. Algorithmic and Hardware Co-Design of Event-based Local Synaptic Plasticity
--------
The human brain expends a mere 20 watts<sup>[[1]](https://doi.org/10.1109/MCSE.2017.33)</sup> in learning and inference, several orders of magnitude lower than the state-of-the-art (SOTA) large language models ([GPT-3](https://doi.org/10.48550/arXiv.2005.14165) and [LaMDA](https://doi.org/10.48550/arXiv.2201.08239)). There is the need to innovate sustainable AI hardware as the 3.4x compute doubling per month has outpaced the Moore's law, i.e., a 2-year transistor doubling<sup>[[2]](https://openai.com/blog/ai-and-compute/)</sup>. Efforts here are geared towards realizing biologically plausible learning rules such as the Hebb's rule based Spike-Timing-Dependent Plasticity (STDP) algorithmically and corresponding in low-power neuromorphic circuits and systems implemented in mixed analog-digital VLSI. Analog subthreshold current-mode computation offers convenient realization of addition and multiplication arithmetic. Moreso current-mode memory elements such as dynamic current mirrors can be leverage to arrive at low-power learning engines.
On the Algorithmic front, we have developed [LODeNNS](https://doi.org/10.1145/3546790.3546793), a linearly optimized Dendrocentric Nearest Neighbor STDP suitable for state-of-the-art large-scale digital neuromorphic platforms such as the Intel Loihi for spatiotemporal signal applications such as tracking and audio recognition. Future work on this include validation and application on event-based data.
On the hardware front, insights from the algorithmic level are being translated in mixed signal VLSI with implications for learning at the edge and on-the-fly, i.e. low-power intelligent sensors.

1. VLSI implementation of Synaptic Memory Consolidation
----------------