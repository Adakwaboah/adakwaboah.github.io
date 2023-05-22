---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

* Neuromorphics
==========

  * Algorithmic and Hardware Co-Design of Event-based Local Synaptic Plasticity  
  --------
  The human brain expends a mere 20 watts<sup>[[1]](https://doi.org/10.1109/MCSE.2017.33)</sup> in learning and inference, exponentially lower than state-of-the-art large language models ([GPT-3](https://doi.org/10.48550/arXiv.2005.14165) and [LaMDA](https://doi.org/10.48550/arXiv.2201.08239)). There is the need to innovate sustainable AI hardware as the 3.4x compute doubling per month has drastically outpaced the Moore's law, i.e., a 2-year transistor doubling<sup>[[2]](https://openai.com/blog/ai-and-compute/)</sup>. Efforts here are geared towards realizing biologically plausible learning rules such as the Hebb's rule based Spike-Timing-Dependent Plasticity (STDP) algorithmically and corresponding in low-power neuromorphic circuits and systems implemented in mixed analog-digital VLSI. Analog subthreshold current-mode computation offers convenient realization of addition and multiplication arithmetic. Moreso, current-mode memory elements such as dynamic current mirrors can be leverage to arrive at low-power learning engines.
  On the Algorithmic front, we have developed [LODeNNS](https://doi.org/10.1145/3546790.3546793), a linearly optimized Dendrocentric Nearest Neighbor STDP suitable for existing large-scale digital neuromorphic platforms such as the Intel Loihi and can be deployed in spatiotemporal signal applications such as object tracking and audio recognition. Future work on this include validation and application on event-based data.
  On the hardware front, insights from the algorithmic level are being translated in mixed signal VLSI with implications for learning at the edge and on-the-fly, i.e. low-power intelligent sensors.
  ![STDP Hardware and circuit](/images/SynapseFig.png)
  * VLSI implementation of Synaptic Memory Consolidation for Lifelong Learning
  ----------------
  Our brains are capable of learning new information quickly and retaining them over long periods - from days to years. This plasticity-rigidity property is lacking in present day Machine Learning models as they are often riddled with catatrosphic forgetting arising from vanishing and exploding gradients. The goal here is implement computational prinicples (the Linear Chain Bicascade model) behind synaptic memory consolidation (SMC) presented by Benna and Fusi<sup>[[3]](https://doi.org/10.1038/nn.4401)</sup> in mixed signal VLSI. Ultimately, deploying an array of synapse equipped with such a property will be useful for realizing energy-efficient hardware for continual learning.
  ![Synaptic Memory Consolidation](/images/smc_circ.png)
  {% comment %}
  <img align="right" width="500" height="500" src="/images/smc.png">
  {% endcomment %}

  * Efficient Deep Neural Network by Saliency-gated Dropout
  ----------------

* Neural Interfaces
===========

  * HermEIS: A Parallel Multichannel Electrochemical Impedance Spectrometer for Rapid Neural Electrode Characterization
  -----------------