---
title: BrainScaleS 2
description: The BrainScaleS-2 is an accelerated spiking neuromorphic system-on-chip integrating 512 adaptive integrate-and-fire neurons, 212k plastic synapses, embedded processors, and event routing. It enables fast emulation of complex neural dynamics and exploration of synaptic plasticity rules. The architecture supports training of deep spiking and non-spiking neural networks using hybrid techniques like surrogate gradients.
active_product: False
product:
  chip_type: Mixed-signal
  neurons: 512
  synapses: 130000
  on_chip_learning: True
  power: ~1 W
  software: BrainScaleS OS
  applications: Edge processing, robotics
  status:
    announced: true
    released: true
    retired: true
  announced_date:
  release_date:
image: brainscales-2.jpg
organization:
- org_name: Universität Heidelberg
  org_logo:
  org_website:
  group_name:
  social_media_links:
    linkedin:
    twitter:
    wikipedia:
  product_page_link:
draft: false
---

The BrainScaleS-2 accelerated neuromorphic system is an integrated circuit architecture for emulating biologically-inspired spiking neural networks. It was developed by researchers at the Heidelberg University and collaborators. Key features of the BrainScaleS-2 system include:

## System Architecture
- Single-chip ASIC integrating a custom analog core with 512 neuron circuits, 212k plastic synapses, analog parameter storage, embedded processors for digital control and plasticity, and an event routing network
- Processor cores run a software stack with a C++ compiler and support hybrid spiking and non-spiking neural network execution
- Capable as a unit of scale for larger multi-chip or wafer-scale systems

## Neural and Synapse Circuits
- Implements the Adaptive Exponential Integrate-and-Fire (AdEx) neuron model with individually configurable model parameters
- Supports advanced neuron features like multi-compartments and structured neurons
- On-chip synapse correlation and plasticity measurement enable programmable spike-timing dependent plasticity 

## Hybrid Plasticity Processing
- Digital control processors allow flexible implementation of plasticity rules bridging multiple timescales
- Massively parallel readout of analog observables enables gradient-based and surrogate gradient optimization approaches

## Applications and Experiments
- Accelerated emulation of complex spiking neuron dynamics, multi-compartment models, and path integration circuits
- Exploration of synaptic plasticity models and critical network dynamics at biological timescales
- Training of deep spiking neural networks using surrogate gradient techniques
- Non-spiking neural network execution leveraging synaptic crossbar for analog matrix multiplication

The accelerated operation and flexible architecture facilitate applications in computational neuroscience research and novel machine learning approaches. The system design serves as a scalable basis for future large-scale neuromorphic computing platforms.

## Related publications

| Date | Title | Authors  | Venue/Source |
|------|-------|----------|------------- |
| January 2022 | [The BrainScaleS-2 accelerated neuromorphic system with hybrid plasticity](https://arxiv.org/abs/2201.11063) | Christian Pehle, Sebastian Billaudelle, Benjamin Cramer, Jakob Kaiser, Korbinian Schreiber, Yannik Stradmann, Johannes Weis, Aron Leibfried, Eric Müller, Johannes Schemmel | arXiv |