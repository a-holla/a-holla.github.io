---
title: "LIMO: Low-power in-memory-annealer and matrix-multiplication primitive for edge computing"
collection: publications
permalink: /publications/limo
excerpt: ' '
date: 2026-02-28
venue: 'npj Unconventional Computing'
paperurl: 'https://doi.org/10.1038/s44335-026-00054-8'
citation: 'Amod Holla, Sumedh Chatterjee, Sutanu Sen, Anushka Mukherjee, Fernando García-Redondo, Dwaipayan Biswas, Francesca Iacopi, and Kaushik Roy <br> <i>npj Unconventional Computing</i> <b>3</b>, Article 10, <b>2026</b> <br> DOI: 10.1038/s44335-026-00054-8'
---

**Abstract**: Large combinatorial optimization problems such as the Traveling Salesman Problem are challenging for conventional processors because of both their computational complexity and the cost of repeated data movement. LIMO is a programmable mixed-signal compute-in-memory primitive designed to accelerate annealing-based optimization while also supporting neural-network inference. The architecture combines an 8T-SRAM compute core with a hardware-aware annealing algorithm and STT-MTJ-based stochastic circuitry. A refinement-based divide-and-conquer strategy enables the system to scale to TSP instances containing as many as 85,900 cities while improving solution quality and time-to-solution relative to prior hardware annealers. The same compute macro can perform vector-matrix multiplications, enabling its reuse for neural-network workloads. Hardware-aware training allows image-classification and face-detection workloads to achieve software-comparable accuracy while reducing latency and energy relative to baseline compute-in-memory architectures.