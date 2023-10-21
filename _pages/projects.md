---
layout: archive
title : "Projects"
permalink: /projects/
author_profile: true
---

## 1. **Road Scene Completion with Geometry-Aware 3D Vehicle Placement** 
  *	Collaborated in a team of three to design a placement module and develop an augmentation strategy for dense 3D bounding box distribution.
  *	Showcased 22.6% improvement in Average Precision (AP40) metric on KITTI3D Object Detection benchmark.

## 2. **Learning Projections from Single Photon Cameras (SPC) for Stereo Depth Estimation** 
  *	Formulated a software-defined projection technique to estimate depth from SPC photon cube at low light.
  *	Incorporated exposure bracketing into ACVNet by selectively using multiple exposures for depth prediction.
  * Reduced D1 error by nearly 2% with learned-mask aided video compressive projection over multi-exposure.

## 3. **Unsupervised Low-Light Depth Estimation**
  *	Reviewed depth estimation on CFNet, GANet and PSMNet SOTA architectures by inferring the models on the KITTI benchmark dataset.
  *	Achieved a 1.5-2x speedup with Mixed Precision, as compared to default single precision, on computationally intensive models (Resnet50).
  *	Warped the input images from the disparity map of Mono and Stereo views to observe novel occlusion artifacts in the warped views.

  
## 4. **Model Pruning: Lottery Ticket Hypothesis** 
  *	Trained a lightweight model M1 and Resnet18 on CIFAR-10 to perform model pruning experiments in PyTorch.
  * Re-achieved original train accuracy within 1-2% error on iteratively pruning the models with 40-80% sparsity. Concluded that iterative pruning has better model generalizability and better accuracy on the validation set. 

  
 
