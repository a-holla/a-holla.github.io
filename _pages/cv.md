---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
A compact PDF version of the CV can be found [here](/files/CV_public.pdf) (Last update: June 2026).

Education
======
* **Ph.D. in Electrical and Computer Engineering**, Purdue University, West Lafayette, expected May 2029
  * Advisor: Prof. Kaushik Roy
  * GPA: 4/4
  * Research: Advanced node memory design; mixed-signal circuit design for compute-in-memory; circuit design with emerging embedded memory technologies; hardware-algorithm co-design for efficient computing

* **B.Tech. in Electrical Engineering**, Indian Institute of Technology Delhi, May 2024
  * GPA: 9.15/10
  * Department Rank: 4/192
  * Best Bachelor Thesis in Electrical Engineering (advisor: Prof: Debanjan Bhowmik)


Research Experience
======
* **Tapeout of a 22nm MRAM-Based Compute-in-Memory Accelerator**  
  _Collaboration with imec, Belgium_ (August 2025 - May 2026)
  * Part of a four-chip magnetoresistive RAM (MRAM) compute-in-memory prototype tapeout for accelerating DNN matrix-vector multiplications in GlobalFoundries (GF) 22nm.
  * Designed and laid out one of the four chips, including MRAM arrays, sensing peripherals, and calibration circuits for correcting analog non-idealities.
  * Built the shared tapeout infrastructure used across all four chips, including the GF 22nm RTL-to-GDSII flow for digital logic and a custom I/O pad ring.

* **Ternary Gain-cell Compute-in-Memory Macro in 22nm** (January 2026 - May 2026)
  * Developed a high-density gain-cell analog compute-in-memory macro with ternary bit-cell storage for highly quantized matrix-vector multiplications, reducing ADC conversion overhead for DNN acceleration.
  * Designed and laid out a 64×64 all-NMOS 3T gain-cell array with compute peripherals and self-calibration circuitry to mitigate transistor-mismatch-induced non-idealities.
  * Achieved 2.6× higher density than 8T-SRAM for equivalent compute-in-memory functionality.

* **In-Memory Probabilistic Computing for Combinatorial Optimization**  
  _Collaboration with imec, Belgium_ (April 2025 - July 2025)
  * Developed a compute-in-memory architecture for accelerating NP-hard large-scale routing problems.
  * Designed 8T-SRAM arrays and sense amplifiers integrating spin-based devices for probabilistic computing.
  * Developed control logic to execute in-memory optimization cycles for large-scale routing problems.
  * Cycle-accurate evaluations of the ASIC implementation project 7 and 14 orders-of-magnitude improvement in time-to-solution and energy efficiency, respectively, compared with a CPU, with <15% quality loss.


Current Research
======
* **In-Memory Boolean Operations in 2nm Nanosheet FET Technology**  
  _Collaboration with imec, Belgium_ (August 2026 - Present)
  * Developing 8T-SRAM arrays and supporting digital logic in imec 2nm nanosheet FET technology for in-memory Boolean operations, targeting accelerated k-nearest-neighbor search in graph-based combinatorial optimization.


Technical Skills
======
* **EDA Tools:** Cadence Virtuoso, Genus, Innovus
* **HDLs & Programming:** Verilog, SystemVerilog, Python, C
* **Circuit & VLSI Design:** Custom circuit design and layout, synthesis, PNR, STA, RTL-to-GDSII flow, tapeout


Relevant Coursework
======
* MOS VLSI Design, Advanced VLSI Design, Solid State Devices, AI Hardware, CMOS Analog IC Design


Work and Research Positions
======
* August 2024 - Present: Graduate Research Assistant, Purdue University
  * Supervisor: Prof. Kaushik Roy

* December 2021 - June 2024: Research Assistant, NAITS Group
  * IIT Delhi / IIT Bombay
  * Supervisor: Prof. Debanjan Bhowmik

* July 2023 - December 2023: Research Assistant, CSNDL Lab
  * IIT Delhi
  * Supervisor: Prof. Saurabh Gandhi

* Summer 2023: Data Scientist, Ripik AI

* Winter 2022: Hardware Engineer Intern, Aeronautical Development Establishment, DRDO

* Summer 2022: Research Assistant, CAN Lab (remote)
  * The University of Hong Kong
  * Supervisor: Prof. Can Li


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Additional Interests
======
* Hiking, Traveling, Gardening, Lifting, Cooking, Aviation

