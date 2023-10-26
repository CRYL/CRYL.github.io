---
title: "Variational quantum algorithms for trace distance and fidelity estimation"
collection: publications
permalink: /publication/variational-metric-estimate
excerpt: 'Variational method for metric estimation'
date: 2021-12-22
venue: 'Quantum Science and Technology'
paperurl: 'https://iopscience.iop.org/article/10.1088/2058-9565/ac38ba/meta'
citation:
---

(This work was done when I was a research intern in [IQC, Baidu Research](https://quantum.baidu.com/about).)

Estimating the difference between quantum data is crucial in quantum computing. However, as typical characterizations of quantum data similarity, the trace distance and quantum fidelity are believed to be exponentially-hard to evaluate in general. In this work, we introduce hybrid quantum-classical algorithms for these two distance measures on near-term quantum devices where no assumption of input state is required. First, we introduce the Variational Trace Distance Estimation (VTDE) algorithm. We in particular provide the technique to extract the desired spectrum information of any Hermitian matrix by local measurement. A novel variational algorithm for trace distance estimation is then derived from this technique, with the assistance of a single ancillary qubit. Notably, VTDE could avoid the barren plateau issue with logarithmic depth circuits due to a local cost function. Second, we introduce the Variational Fidelity Estimation (VFE) algorithm. We combine Uhlmann's theorem and the freedom in purification to translate the estimation task into an optimization problem over a unitary on an ancillary system with fixed purified inputs. We then provide a purification subroutine to complete the translation. Both algorithms are verified by numerical simulations and experimental implementations, exhibiting high accuracy for randomly generated mixed states.

[Read paper here](https://arxiv.org/abs/2012.05768)
