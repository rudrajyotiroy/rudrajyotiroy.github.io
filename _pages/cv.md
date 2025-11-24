---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
- **University of Michigan, Ann Arbor** - M.S. in Computer Science and Engineering (Aug 2024 - May 2026, GPA 4.0/4.0). Research with Satish Narayanasamy on hardware-enforced workload intent authorization and performance regulation for on-prem AI/HPC chips. Coursework: Advanced Computer Architecture, Advanced Compilers, Scalable Systems for GenAI, Privacy-Enhancing Tech.
- **IIT Kharagpur** - B.Tech in Electronics & Electrical Communication Engineering (Aug 2018 - May 2022, GPA 9.26/10). Minor in Computer Science; micro-specialization in Embedded Software Modeling & Design. Coursework: Algorithms, AI, Computer Architecture, CUDA/OpenMP Programming, Hardware Security, Advanced VLSI, Digital Design.

Work experience
======
- **Graduate Student Instructor (EECS183), University of Michigan** - Aug 2025 - Present. Manage labs and office hours for 805-student intro programming course; prepare/grade exams; drive curriculum and staff productivity improvements. Average student rating: 4.5/5.
- **HW System Modeling Engineer, Qualcomm** - Dec 2023 - Aug 2024. Built functional co-simulation model of the High-Performance Audio Engine in C++ and integrated with QEMU for RTL-agnostic audio driver testing. Enabled full register programmability with timing-accurate modeling to unblock software 6 months before RTL readiness; individually recognized by VP of Audio Systems.
- **Associate HW Verification Engineer, Qualcomm** - Jul 2022 - Nov 2023. Authored scalable ML framework for early deadlock detection and triage in long-running hardware simulations; integrated with CI/CD for automated deployment, cutting early debug time ~40%. Automated assertion generation/binding for post-reset memory checks, improving power-aware GLS sign-off TAT by ~25%. Owned testbench fixes and testcases for two audio IP blocks.
- **HW Engineering Intern, Qualcomm** - May 2021 - Jul 2021. Built secondary UVM monitor to detect AXI/AHB bus stalls via passive transaction tracking, achieving up to 80% stall detection with <5% false positives.

Projects
======
- **Attention As You Need It** (Sept 2025 - Present). Designing automated rewriting to generate tiled/fused attention kernel variants (FlexAttention-like) tuned to deployment constraints; translating PyTorch kernels into compute graphs followed by cost-constrained search to relieve compute/memory bottlenecks.
- **MirrorMaze: Compiler-guided control-flow obfuscation** (Jan 2025 - Apr 2025). LLVM extension that detects secret-dependent control-flow divergence (taint analysis) and inserts minimal dummy ops to equalize branch cost; ~4-5% faster than prior obfuscation methods while retaining security.
- **Contention Aware Task Scheduling** (Jul 2021 - Jul 2023). Framework for task-graph generation and scheduling on arbitrarily networked execution platforms; proposed heuristics for computation/communication scheduling under contention and evaluated via Monte Carlo simulations.
- **Future-Aware Dynamic Thermal Management** (Mar 2021 - Jun 2022). Supervisory control framework for real-time OpenCL workloads on embedded platforms; paired Newtonian thermal and analytical performance models with beam-search pruning, outperforming SOTA by ~14% on average.
- **Efficient GPGPU Parallelization of RCNN** (Feb 2021 - Apr 2021). Implemented CUDA convolution kernels via Fourier-domain GEMM using cuFFT/cuBLAS; applied Im2Col flattening, tiling, fusion, and memory coalescing to reach ~100x speedup over naive baselines.

Publications
======
- **Scheduling & Routing Strategies for Executing Task Graphs on AdHoc Networks** - Chhavi Chaudhury; Rudrajyoti Roy; Rajesh Devaraj; Arnab Sarkar. Ad Hoc Networks (Elsevier), DOI: 10.1016/j.adhoc.2025.104084, Nov 3 2025.
- **Harnessing Machine Learning in DTM in CPU-GPU Embedded Platforms** - Srijeeta Maity; Anirban Majumder; Rudrajyoti Roy; Soumyajit Dey; Ashish R. Hota. ACM TODAES, DOI: 10.1145/3708890 (Editor's Pick), Jan 10 2025.
- **ML Based Scalable Plug-and-Play Framework for Early Hang Detection** - Rudrajyoti Roy; Anshul Sengar; Ronak Shah. Qualcomm Global SoC Conference, IP-Cores track (Best Paper Award), May 8-9 2024, Bengaluru.
- **Future aware Dynamic Thermal Management in CPU-GPU Embedded Platforms** - Srijeeta Maity*; Rudrajyoti Roy*; Anirban Majumder; Soumyajit Dey; Ashish R. Hota. IEEE RTSS, DOI: 10.1109/RTSS55097.2022.00041, Dec 5-8 2022, Houston.
- **Selective detection of multiple VOCs employing ZnO nanorods and PCA** - Avik Sett; Tanisha Rana; Rudrajyoti Roy; Tufan Saha; Tarun Kanti Bhattacharyya. IEMENTech, DOI: 10.1109/IEMENTech51367.2020.9270117, Oct 2-4 2020, Kolkata.

Skills
======
- **Languages:** C, C++, Embedded C, CUDA, OpenCL, Python, SystemVerilog, SystemC, MATLAB, Shell, LLVM.
- **Tools:** UVM, Synopsys VCS, Verdi, gem5, SniperSim, gpgpuSim, Hexagon SDK, PyTorch, Docker, Git, ClearCase.

Activities
======
- **Robotics:** SWARM UG research group; runner-up at JLR (Inter-IIT Tech Meet) and Tessaract (team lead).
- **Sports & Cultural:** Chess, Table-Tennis, Badminton, Whitewater Kayaking, Vocal/Keyboard music.
- **Mentoring:** SWG peer mentor for undergraduates; tutored school students as NSS volunteer.
