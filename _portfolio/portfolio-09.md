---
title: "SIMD-kernel-for-QR-decompostion (3D-Reconstruction)"
excerpt: "SIMD kernel and results <br/><img src='/images/qr.png' >" 
collection: portfolio
---

Fundamental Matrix Estimation is the heaviest part of the 3D reconstruction. In this work, we use QR decomposition and explore data layouts and techniques to reduce computations and parallelize them.

[code and presentation](https://github.com/vishnumh/SIMD-kernel-for-QR-decompostion_3D-Reconstruction)

Topic Covered: 
1. Basics of SIMD Kernels, OpenMP. 
2. Architecture based kernel datalayout.
3. Optimization of Latency for Haswell architecture.


Programming Language:
C, SIMD
