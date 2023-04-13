---
title: "SMPLX regression from images"
excerpt: "SMPLX fitting results <br/><img src='/images/smplx.gif'  width="200" height="100">" 
collection: portfolio
---

SMPL is an articulated model to represent under-clothed human. SMPLX is an extension of SMPL, which includes an articulated expressive model for hands in SMPL. I worked on implementing State of the art models for fitting SMPLX onto reference images and regressing COCO 3D key points for a downstream task.

Learning outcomes: 
1. Parametric modelling of Pose (55 rotational poses - 22 joints for the body, 30 for the finger and 3 jaw joints).
2. Copy-Paste integration for including hand-articulated models into SMPL.

Programming Language:
Pytorch, Python