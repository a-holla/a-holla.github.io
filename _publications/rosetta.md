---
title: "ROSETTA: ROM-Overlaid STT-MRAM for Efficient MVM and Softmax Operations Toward Accelerating Transformer Inference"
collection: publications
permalink: /publications/rosetta
excerpt: ' '
date: 2026-02-17
venue: 'IEEE Journal on Emerging and Selected Topics in Circuits and Systems'
paperurl: 'https://doi.org/10.1109/JETCAS.2026.3665635'
citation: 'Amod Holla, Mainakh Mukherjee, Anushka Mukherjee, and Kaushik Roy <br> <i>IEEE Journal on Emerging and Selected Topics in Circuits and Systems</i> <b>16</b>(2), 441-454, <b>2026</b> <br> DOI: 10.1109/JETCAS.2026.3665635'
---

**Abstract**: Compute-in-memory architectures can reduce the data-movement bottleneck of deep-learning accelerators by performing matrix-vector multiplications directly within memory arrays. Transformer inference, however, also requires nonlinear operations such as softmax, while conventional STT-MRAM compute-in-memory arrays face limitations from low device resistance, parasitic effects, and restricted row-level parallelism. ROSETTA introduces a 3T-2R STT-MRAM compute-in-memory bit-cell using series-resistance sensing and time-to-digital conversion for energy-efficient matrix-vector multiplication. An additional word line overlays ROM functionality onto the array, allowing lookup tables used for softmax to be stored without increasing bit-cell area. A palindromic input and weight encoding scheme mitigates data-dependent nonlinearity and enables substantially higher row parallelism. Compared with an equivalent ROM-overlaid 8T-SRAM implementation, the proposed macro reduces both area and MVM energy while maintaining comparable latency and accuracy.