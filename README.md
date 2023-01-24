# Awesome RGB-D Fusion: [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome resources regarding the fusion of rigid surface reconstruction from depth maps on-the-fly (online). 

This list focues ONLY on works that produce dense surface reconstruction, not only camera tracking (SLAM). Also, mainly methods that work in real-time and in online, on-the-fly use-case are included here, with some notable exceptions in [Offline](#offline) section of the [Papers](#papers). 

## Table of Contents

 - [Surveys](#surveys)
 - [Papers](#papers)
 - [Implementations](#implementations)
 - [Datasets](#datasets)

## Surveys
* [An Overview on Visual SLAM: From Tradition to Semantic](https://www.mdpi.com/2072-4292/14/13/3010). JRS'2022
* [High-quality indoor scene 3D reconstruction with RGB-D cameras: A brief review](https://dc.tsinghuajournals.com/computational-visual-media/vol8/iss3/3/). CVM'2022
* [3D indoor scene modeling from RGB-D data: a survey](https://dc.tsinghuajournals.com/computational-visual-media/vol1/iss4/6/). CVM'2015

## Papers

#### Traditional
* [HRBF-Fusion: Accurate 3D reconstruction from RGB-D data using on-the-fly implicits](https://arxiv.org/abs/2202.01829). TOG'2022
* [SurfelMeshing: Online Surfel-Based Mesh Reconstruction](https://github.com/puzzlepaint/surfelmeshing). PAMI'2019
* [PSDF Fusion: Probabilistic Signed Distance Function for On-the-fly 3D Data Fusion and Scene Reconstruction](https://arxiv.org/abs/1807.11034). ECCV'2018
* [Real-time High-accuracy 3D Reconstruction with Consumer RGB-D Cameras](https://cg.cs.tsinghua.edu.cn/papers/TOG-2018-reconstruction.pdf). TOG'2018
* [BundleFusion: Real-time Globally Consistent 3D Reconstruction using Online Surface Re-integration](http://graphics.stanford.edu/projects/bundlefusion/). TOG'2017
* [InfiniTAM](https://www.robots.ox.ac.uk/~victor/infinitam/cite.html). ECCV'2016
* [ElasticFusion: Dense SLAM Without A Pose Graph](https://www.imperial.ac.uk/dyson-robotics-lab/downloads/elastic-fusion/). RSS'2015
* [Real-time 3D Reconstruction in Dynamic Scenes using Point-based Fusion](https://reality.cs.ucl.ac.uk/projects/kinect/keller13realtime.html). 3DV'2013
* [Real-time 3D Reconstruction at Scale using Voxel Hashing](http://www.niessnerlab.org/projects/niessner2013hashing.html). TOG'2013
* [KinectFusion: Real-time dense surface mapping and tracking](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/ismar2011.pdf). ISMAR'2011

#### Data-driven
* [BNV-Fusion: Dense 3D Reconstruction using Bi-level Neural Volume Fusion](https://github.com/likojack/bnv_fusion). CVPR'2022
* [DI-Fusion: Online Implicit 3D Reconstruction with Deep Priors](https://cg.cs.tsinghua.edu.cn/papers/CVPR-2021-DI-Fusion.pdf). CVPR'2021
* [NeuralFusion: Online Depth Fusion in Latent Space](https://www.silvanweder.com/publications/neural-fusion/). CVPR'2021
* [RoutedFusion: Learning Real-time Depth Map Fusion](https://www.silvanweder.com/publications/routed-fusion/). CVPR'2020

#### Offline
* [DFusion: Denoised TSDF Fusion of Multiple Depth Maps with Sensor Pose Noises](https://www.researchgate.net/publication/358758460_DFusion_Denoised_TSDF_Fusion_of_Multiple_Depth_Maps_with_Sensor_Pose_Noises). Sensors'2022
* [OctNetFusion: Learning Depth Fusion from Data](https://github.com/griegler/octnetfusion). 3DV'2017

#### Non-rigid
* [DoubleFusion: Real-time Capture of Human Performances with Inner Body Shapes from a Single Depth Sensor](http://www.liuyebin.com/doublefusion/doublefusion.htm). CVPR'2018
* [Fusion4D: Real-time Performance Capture of Challenging Scenes](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/11/a114-dou.pdf). TOG'2016

## Implementations
* [Volumetric TSDF Fusion of RGB-D Images in Python](https://github.com/andyzeng/tsdf-fusion-python).
* [KinectFusion implemented in Python with PyTorch](https://github.com/JingwenWang95/KinectFusion).

## Datasets
* [TUM Dataset](https://vision.in.tum.de/data/datasets/rgbd-dataset/download).
* [NYU Depth Dataset V2](https://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html/).

## Licenses
License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
