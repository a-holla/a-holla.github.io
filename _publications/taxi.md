---
title: "TAXI: Traveling Salesman Problem Accelerator with X-Bar-Based Ising Macros Powered by SOT-MRAMs and Hierarchical Clustering"
collection: publications
permalink: /publications/taxi
excerpt: ' '
date: 2025-11-26
venue: '62nd ACM/IEEE Design Automation Conference (DAC)'
paperurl: 'https://doi.org/10.1109/DAC63849.2025.11132522'
citation: 'Sangmin Yoo, Amod Holla, Sourav Sanyal, Dong Eun Kim, Francesca Iacopi, Dwaipayan Biswas, James Myers, and Kaushik Roy <br> <i>62nd ACM/IEEE Design Automation Conference (DAC)</i>, Article 60, pp. 1-7, <b>2025</b> <br> DOI: 10.1109/DAC63849.2025.11132522'
---

**Abstract**: Ising solvers combined with hierarchical clustering provide a promising approach for solving large-scale Traveling Salesman Problems (TSPs), but existing approaches suffer from degrading solution quality as problem size increases and often fail to fully exploit the underlying hardware. TAXI is an in-memory-computing TSP accelerator based on crossbar Ising macros. Hierarchical clustering decomposes a large TSP into sub-problems that are solved independently and in parallel within the macros, minimizing data movement. Spin-orbit-torque (SOT) devices embedded in the architecture provide compact stochasticity for annealing. Through hardware-algorithm co-design, TAXI improves solution quality, latency, and energy efficiency for TSP instances containing up to 85,900 cities. The architecture demonstrates substantially improved execution speed over prior clustering-based Ising solvers while maintaining high-quality solutions for very large problem instances.