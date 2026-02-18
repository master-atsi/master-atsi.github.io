---
layout: single
title: "Multi-Agent Systems"
sidebar:
  - title: "Teacher"
    text: "Ioannis Saras"
---

{% include control.button %}

## Course objective

Animal swarms, electric grids, autonomous vehicle formations, interconnected neurons, sensor networks… all these systems share a crucial feature: their overall behavior results from a local interaction among many agents. Here, “local” means that each agent typically interacts with its neighbors only. This course aims at providing the basics to both analyze and control such large-scale networks. In particular, it provides methodological tools to study interconnection between multiple dynamic agents. It addresses two fundamental features of such networks: consensus, in which the states of all agents converge to a common value, and synchronization, in which agents share a coherent behavior (possibly non-static). These notions will be illustrated via a selection of case studies.

At the end of the course, students will be able to:
- Derive graph-based models for multi-agent systems
- Analyze structural properties of graphs
- Predict the overall behavior of a large-scale system in terms of stability, robustness, consensus and synchronization
- Control a large-scale system based on local information only
- Use these methodologies in particular application fields, such as drone formation, autonomous vehicles, or sensor networks.

## Course content

- Lecture 1: Motivations and definitions
  - Based on real-world applications, starting with low dimension
  - Complex systems seen as an interconnection of simpler subsystems
  - Two crucial features: agents’ dynamics and interconnection
  - Definition of consensus and synchronization concepts
- Lecture 2: Graphs
  - Definitions: graph, vertices, edges, adjacency matrix
  - Linear consensus, symmetric and asymmetric
  - Notion of Laplacian, role of Laplacian eigenvalues, connectivity, spanning tree
- Lecture 3: Consensus
  - Variants on the interconnection: Time-varying interconnection gains and Time-varying topology
  - Variants on the agent’s dynamics: Double integrators and Generic linear systems
  - Other practical constraints: Communication delays, Communication protocol, Packet losses, Output constraints
  - Event-triggered
- Lecture 4: Synchronization
- Difference with respect to consensus: steady-state regime independent of initial state, steady state not necessarily static (limit cycle)
- Different types of synchronization: Master-slave, with links to trajectory tracking, and Mutual
- Oscillators synchronization: Linear harmonic oscillators, Kuramoto, Diffusive coupling
- Case study
Each year, one of the following application domains will be investigated through a case study:
  - Robot swarms
  - Drones
  - Sensor networks

## References

- W. Ren, Y. Cao. Distributed Coordination of Multi-agent Networks: Emergent Problems, Models, and Issues. Communications and Control Engineering, Springer-Verlag, London, 2011
- W. Ren, R.W. Beard, and E. M. Atkins. Information Consensus in Multivehicle Cooperative Control, IEEE Control Systems Magazine, Vol. 27, No. 2, April, 2007, pp. 71-82
- H. Nijmeijer, N. and A. Rodriguez-Angeles. Synchronization of mechanical systems (Vol. 46), World Scientific, 2003
- S.S Kia, B.VanScoy, J.Cortes, R.A. Freeman, K.M. Lynch, and S.Martinez. Tutorial on Dynamic Average Consensus The problem, its applications, and the algorithms, IEEE Control Systems Magazine 2018
- M. Mesbahi, M. Egerstedt. Graph Theoretic Methods in Multiagent Networks, Princeton University Press
