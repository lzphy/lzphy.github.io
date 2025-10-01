---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

Here are some selected projects I have worked on.

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
