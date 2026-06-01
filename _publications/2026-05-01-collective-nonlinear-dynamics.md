---
title: "Collective Nonlinear Dynamics in Heterogeneous Swarms: A Reservoir Computing Perspective"
collection: publications
permalink: /publication/2026-05-01-collective-nonlinear-dynamics
excerpt: 'My Ph.D. dissertation on heterogeneous swarm dynamics as computational reservoirs, with a focus on temporal memory, nonlinear collective behavior, and reservoir computing.'
date: 2026-05-01
type: dissertation
venue: 'Ph.D. dissertation, The University of Tokyo'
citation: 'Lund, T. (2026). <i>Collective Nonlinear Dynamics in Heterogeneous Swarms: A Reservoir Computing Perspective</i>. Ph.D. dissertation, The University of Tokyo.'
---
My doctoral dissertation studies swarm-based reservoir computing, where a collective dynamical system serves as a reservoir for temporal information processing under a linear readout. The central question is what dynamical mechanisms make temporal information visible to readout and scalable in swarms whose interaction networks change over time.

The dissertation includes the work published in [State transitions unlock temporal memory in swarm-based reservoir computing](https://peerj.com/articles/cs-3763/) in <i>PeerJ Computer Science</i>.

A public dissertation link will be added when available.

Abstract
======
This work studies swarm-based reservoir computing, where a collective dynamical system serves as a reservoir for temporal information processing under a linear readout. Unlike fixed-topology reservoirs, a swarm's interaction network is inherently time-varying, and the central question is what dynamical mechanisms make temporal information readout-visible and scalable.

We introduce a two-state swarm architecture with hysteretic state transitions driven by a local "kinetic energy" signal, used here as a metaphor for neighborhood activity and implemented as mean neighbor speed, a speed-like local energy proxy. State-conditioned interaction parameters produce semi-stable macrostates that are detectable through observables invariant to permutation, translation, and rotation. Using pure memory capacity as the primary diagnostic, with linear readout and minimal feature expansion, we show that introducing a slow, history-dependent state variable yields large gains over single-state baselines and supports systematic scaling of memory capacity with swarm size under intact conditions.

We then probe robustness under structural perturbations using a "hole" protocol. This reveals a qualitative separation between intrinsic capacity, meaning information present in the reservoir features, and transfer performance, meaning a readout trained before perturbation. While intrinsic capacity can recover as the swarm reorganizes, fixed readouts are brittle under the resulting distribution shift; a practical mitigation ladder exists, but only brief retraining reliably restores performance close to intrinsic levels.

Finally, we connect capacity and legibility through regime design. Time/speed variants and a mode-switch demonstration, "fly -> compute -> fly", make explicit the trade-off between visually canonical flocking motion and computation-friendly, strongly coupled regimes.

Recommended citation: Lund, T. (2026). <i>Collective Nonlinear Dynamics in Heterogeneous Swarms: A Reservoir Computing Perspective</i>. Ph.D. dissertation, The University of Tokyo.
