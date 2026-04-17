---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently a Master’s student in Electronic Engineering at Nanyang Technological University. I once served as a research assistant at the Institute of Microelectronics (IME), A*STAR, supervised by Prof. Wang Ling Goh and Prof. An Tuan Do. I received the Bachelor degree of Bachelor of Electronic Information Engineering from Wuhan University, Wuhan, China, in Jul. 2020. My research interest is hardware–software co-design to improve system efficiency. You can find more information through my CV.

# 🧭 Research Tracks

Research interests in high-performance computing architectures, efficient hardware acceleration, and task scheduling.

# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCAD 2026</div><img src='images/publication/pace.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A CGRA with SIMD and AGU]

R. Harish, V. P. Nambiar, **<u>Y. Liu</u>**, Y. S. Chong, W. L. Goh, R. Dutta, A. T. Do

*International Conference on Computer-Aided Design (ICCAD), 2026 (In preparation)*

<details>
<summary>Abstract</summary>
Coarse-Grained Reconfigurable Arrays (CGRAs) balance low power and flexible computation, making them ideal for edge devices. Traditional CGRAs allocate some Processing Elements (PEs) for memory-access tasks, reducing compute utilization. Our design introduces a Memory Address Generation Unit (AGU) to handle data fetch/store operations, freeing PEs and improving hardware utilization. Simulations show AGU integration can double CGRA utilization, depending on workload. The architecture also supports SIMD for parallel computation, boosting energy efficiency by up to 3.96×. Implemented in 12 nm FinFET, post-layout simulations achieve 1 GHz and a peak energy efficiency of 1.31 TOPS/W, 3.4× higher than state-of-the-art designs.

</details>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">HPCA 2026</div><img src='images/publication/fractal.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Fractal-Inspired Techniques for High-Resolution Image Generation]

**<u>Y. Liu</u>**, C. Zhou

*International Symposium on High-Performance Computer Architecture (HPCA), 2026 (In preparation)*

<details>
<summary>Abstract</summary>
Diffusion models generate images via upsampling, but background regions take lots of computation while contributing little to output quality, creating structured redundancy that existing accelerators cannot exploit. We propose an adaptive fractal execution framework that partitions each resolution level into a quadtree and selectively expands only active patches using an activity-ranking unit, maintaining an iso-compute budget across levels. To support this space-adaptive dataflow, we design an SoC accelerator with an inter-level task scheduler and a sparse patch-packing engine—capabilities.
</details>

<!-- </div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[KV Cache for Point Transformer]

**<u>Y. Wu</u>**, Z. Guo, **<u>Y. Liu</u>**, C. Zhou

*CVPR, 2026 (In preparation)*

<details>
<summary>Abstract</summary>
Abstract placeholder...

</details> -->

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISCAS 2025</div><img src='images/publication/qubit.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Qubit-State Discrimination using Neural Networks with Rapid and Energy-Efficient Compute Arrays]

**<u>Y. Liu</u>**, Y. S. Chong, B. Lienhard, M. Fan, W. L. Goh, V. P. Nambiar, and A. T. Do

*IEEE International Symposium on Circuits and Systems (ISCAS), 2025*

<details>
<summary>Abstract</summary>
Neural networks (NNs) implemented on field-programmable gate arrays (FPGAs) provide fast, high-fidelity solutions for processing readout signals from quantum information processors. However, application-specific integrated circuits (ASICs) instead of FPGAs hold the potential for improved performance, a largely unexplored path. This work proposes specialized hardware for NN-based qubit-state discrimination. We optimize the NN architecture to minimize resource requirements by reducing the layer width, employing linear activation functions, and weight quantization. Quantization-aware training is used to preserve accuracy despite these optimizations. Next, a compute array employing output stationary dataflow is chosen to process the NN workload. The compute array with abundant multipliers and adders can complete one NN inference in 63 ns, which makes it a good candidate for real-time qubit-state discrimination.

</details>

</div>
</div>

# 🔬 Project
<div class='paper-box'><div class='paper-box-image'><div><img src='images/publication/Fornax.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Fornax: A Lightweight, Energy-Efficient Diffusion Model Accelerator Chip]

High-Performance Computing Chip Scheduler Engineer

<details>
<summary>Abstract</summary>
Designed a lightweight, energy-efficient diffusion-model accelerator chip aimed at high-performance inference of point cloud and deep-learning tasks, with specialized hardware units for parallel computation and memory-efficient data handling. Within this project, developed a flexible and high-efficiency task scheduler that optimizes execution under complex task-dependency constraints, supports execution in parallel, ensuring maximal utilization of the chip’s resources while maintaining low energy consumption.

</details>

</div>
</div>


# 🎖 Honors and Awards
- *2023.08* Second prize, National Undergraduate Electronics Design Contest.
- *2022.08* Second prize, National College Student Integrated Circuit Innovation and Entrepreneurship Competition (Hubei Division).

# 📖 Educations
- *2024.08 - 2026.01 (now)*, Master of Electronics, Nanyang Technological University, Singrapore.
- *2020.09 - 2024.06*, Bachelor of Engineering in Bachelor of Electronic Information Engineering, Wuhan University, Wuhan, China.

# 💻 Internships
- *2025.09 - 2026.01*, Institute of Microelectronics (IME), A*STAR, Singapore.