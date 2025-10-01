---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

Here are some selected projects I have worked on.

## Controlled analytic continuation of Matsubara correlation functions using minimal information principle
<div style="width: 80%; display: flex; justify-content: flex-start; gap: 10px;">
  <img src="/images/mpm1.png" style="width: 33%; object-fit: cover;">
  <img src="/images/mpm2.png" style="width: 33%; object-fit: cover;">
  <img src="/images/mpm3.png" style="width: 33%; object-fit: cover;">
</div>

Analytic continuation is a crucial step in the simulation of finite-temperature field theories, where numerically obtained Matsubara data is extended to the real frequency axis for physical interpretation. However, numerical analytic continuation is an ill-posed problem, as uncertainties in the Matsubara axis are exponentially amplified. In this work, we introduce a systematic and controlled approach that approximates any Matsubara function---whether scalar- or matrix-valued---using a minimal pole representation within a predefined precision. We demonstrate systematic convergence to the exact spectral function on the real axis as a function of our control parameter across various physically relevant scenarios. Additionally, we compare results for real material systems against state-of-the-art methodologies. Our approach is robust against noise, offering a reliable path for analytic continuation in many-body theory, while providing direct access to the analytic structure of functions for deeper theoretical interpretation of physical properties.

Recommended citation: 1. Original paper: <strong>Lei Zhang</strong> & Emanuel Gull, <u>Phys. Rev. B</u> 110, 035154 (2024) [[link]](https://doi.org/10.1103/PhysRevB.110.035154). 2. Technical details and matrix-valued generalization: <strong>Lei Zhang</strong>, Yang Yu & Emanuel Gull, <u>Phys. Rev. B</u> 110, 235131 (2024) [[link]](https://doi.org/10.1103/PhysRevB.110.235131) [<strong>Editors’ Suggestion</strong>].

## Loop-Cluster Coupling and Algorithm for Classical Statistical Models
<div style="text-align: left;">
  <img src="/images/loop_cluster.png" width = "75%">
</div>

Potts spin systems play a fundamental role in statistical mechanics and quantum field theory, and can be studied within the spin, the Fortuin-Kasteleyn (FK) bond or the $$q$$-flow (loop) representation. We introduce a Loop-Cluster (LC) joint model of bond-occupation variables interacting with $$q$$-flow variables, and formulate a LC algorithm that is found to be in the same dynamical universality as the celebrated Swendsen-Wang algorithm. This leads to a theoretical unification for all the representations, and numerically, one can apply the most efficient algorithm in one representation and measure physical quantities in others. Moreover, by using the LC scheme, we construct a hierarchy of geometric objects that contain as special cases the $$q$$-flow clusters and the backbone of FK clusters, the exact values of whose fractal dimensions in two dimensions remain as an open question. Our work not only provides a unified framework and an efficient algorithm for the Potts model, but also brings new insights into rich geometric structures of the FK clusters.

Recommended citation: <strong>Lei Zhang</strong>, Manon Michel, Eren M. Elçi & Youjin Deng, <u>Phys. Rev. Lett.</u> 125, 200603 (2020) [[link]](https://doi.org/10.1103/PhysRevLett.125.200603).

## Graphical Representations and Worm Algorithms for the O($$N$$) Spin Model
<div style="text-align: left;">
  <img src="/images/ON_worm.png" width = "75%">
</div>

We present a family of graphical representations for the O($$N$$) spin model, where $$N ≥ 1$$ represents the spin dimension, and $$N =$$ 1, 2, 3 corresponds to the Ising, $$XY$$ and Heisenberg models, respectively. With an integer parameter $$0 \leq \ell \leq N/2$$, each configuration is the coupling of $$\ell$$ copies of subgraphs consisting of directed flows and $$N − 2\ell$$ copies of subgraphs constructed by undirected loops, which we call the $$XY$$ and Ising subgraphs, respectively. On each lattice site, the $$XY$$ subgraphs satisfy the Kirchhoff flow-conservation law and the Ising subgraphs obey the Eulerian bond condition. Then, we formulate worm-type algorithms and simulate the O($$N$$) model on the simplecubic lattice for $$N$$ from 2 to 6 at all possible $$\ell$$. It is observed that the worm algorithm has much higher efficiency than the Metropolis method, and, for a given $$N$$, the efficiency is an increasing function of $$\ell$$. Beside Monte Carlo simulations, we expect that these graphical representations would provide a convenient basis for the study of the O($$N$$) spin model by other state-of-the-art methods like the tensor network renormalization.

Recommended citation: Longxiang Liu\*, <strong>Lei Zhang</strong>\*, Xiaojun Tan & Youjin Deng, <u>Commun. Theor. Phys.</u> 75, 115702 (2023) [[link]](https://iopscience.iop.org/article/10.1088/1572-9494/acfbdf/meta) [\*: <strong>equal contribution</strong>].
