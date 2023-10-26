---
title: "Near-term Efficient Quantum Algorithms for Entanglement Analysis"
collection: publications
permalink: /publication/variational-entanglement-analysis
excerpt: 'Variational method for entanglement analysis'
date: 2021-09-22
venue: 'Phys. Rev. Applied'
paperurl: 'https://journals.aps.org/prapplied/accepted/6e076A7dMc617c09c386393282878ffba4dd7104b'
citation:
---

This work was done when I was a research intern in [IQC, Baidu Research](https://quantum.baidu.com/about).

Entanglement plays a crucial role in quantum physics and is the key resource in quantum information processing. However, entanglement detection and quantification are believed to be hard due to the operational impracticality of existing methods. This work proposes three near-term efficient algorithms exploiting the hybrid quantum-classical technique to address this difficulty. The first algorithm finds the Schmidt decomposition--a powerful tool to analyze the properties and structure of entanglement--for bipartite pure states. While the logarithm negativity can be calculated from the Schmidt decomposition, we propose the second algorithm to estimate the logarithm negativity for bipartite pure states, where the width of the parameterized quantum circuits is further reduced. Finally, we generalize our framework for mixed states, leading to our third algorithm which detects entanglement on specific families of states, and determines disdillability in general. All three algorithms share a similar framework where the optimizations are accomplished by maximizing a cost function utilizing local parameterized quantum circuits, with better hardware efficiency and practicality compared to existing methods. The experimental implementation on Quantum Leaf using the IoP CAS superconducting quantum processor exhibits the validity and practicality of our methods for analyzing and quantifying entanglement on near-term quantum devices

[Read paper here](https://arxiv.org/abs/2109.10785)