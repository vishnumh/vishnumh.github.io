---
title: "SIMD-kernel-for-QR-decompostion (3D-Reconstruction)"
excerpt: "SIMD kernel and results <br/><img src='/images/qr.png'>" 
collection: portfolio
---

Fundamental Matrix Estimation is the heaviest part of the 3D reconstruction. In this work, we use QR decomposition and explore different ways to reduce computations, have a better data layout and parallelize them.

[code and presentation](https://github.com/vishnumh/SIMD-kernel-for-QR-decompostion_3D-Reconstruction)

Learning outcomes: 
1. Basics of SIMD Kernels, OpenMP. 
2. Architecture based kernel datalayout.
3. Optimization of Latency for Haswell architecture.


Programming Language:
C, SIMD