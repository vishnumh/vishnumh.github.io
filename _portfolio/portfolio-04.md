---
title: "TensorRT deployment for Birds Eye View Representation in AVs"
excerpt: "<br/><img src='/images/bev.gif' >" 
collection: portfolio
---

Deployed a Bird’s Eye View Representation algorithm for self-driving cars in Jetson Xavier aarch64 machine. The algorithm provides road segmentation in the birds’ eye view and involves EfficientNet-b0 feature extraction model for encoding the camera and lidar input from Nu-Scenes.

Accelerated the algorithm by exporting the EfficientNet feature extraction model and ResNet model into TensorRT engine via Onnx to achieve 15x speedup.

[Sample code](https://github.com/vishnumh/TensorRT)

Topic Covered: 
1. Basics of Onnx and TensorRT. 
2. Datasets- Kitti, Nuscenes (with Lidar).
3. Experience with Jetson devices



Programming Language:
Python, Pytorch
