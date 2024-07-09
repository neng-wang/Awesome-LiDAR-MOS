# Awesome-LiDAR-MOS [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
For anyone who wants to do research about 3D point cloud **Moving Object Segmentation (MOS)**

*Continuously updating!*

![mos](./pic/mos.gif)



## Benchmark

 ![img](https://miniodis-rproxy.lisn.upsaclay.fr/py3-public/logos/0d93e3ab-862f-4551-905e-9f8169eccaba/logo.png)        

 [SemanticKITTI: Moving Object Segmentation](https://codalab.lisn.upsaclay.fr/competitions/7088)

## Dataset

1. [SemanticKITTI](http://semantic-kitti.org/)

2. [KITTI-Road](https://github.com/haomo-ai/MotionSeg3D/blob/master/config/kitti_road_mos.md)

3. [Apollo](https://www.ipb.uni-bonn.de/html/projects/apollo_dataset/LiDAR-MOS.zip)

4. [nuScenes](https://github.com/PRBonn/MapMOS/blob/main/src/mapmos/datasets/nuscenes.py)

5. [KITTI-Tracking-19](https://www.ipb.uni-bonn.de/html/projects/kitti-tracking/post-processed/kitti-tracking.zip)

6. [SipailouCampus](https://drive.google.com/file/d/1GnX9CMaH0AjRkkjtOpPv9F5vzqIcUhxR/view)

## Papers

```
-  Recent papers (from 2019)
```

Application: __`out.`__: outdoor &emsp; | &emsp; __`ind.`__: indoor &emsp;   

Sensor:          __`pc.`__: point cloud &emsp; | &emsp; __`img.`__: image &emsp; | &emsp; __`rad.`__: radar 

Statistics:       :fire: code is available & stars >= 100 &emsp;|&emsp; :star: citation >= 50

### 2019

- [[CRV](https://ieeexplore.ieee.org/document/8781606)]Mapless Online Detection of Dynamic Objects in 3D Lidar.[__`out.`__ __`pc.`__] :star:

### 2020

- [[IROS](https://ieeexplore.ieee.org/abstract/document/9340856)]Remove, then Revert: Static Point cloud Map Construction using Multiresolution Range Images.[[code](https://github.com/gisbi-kim/removert)]![Github stars](https://img.shields.io/github/stars/gisbi-kim/removert.svg)[__`out.`__ __`pc.`__] :fire: :star:

### 2021

- [[RAL](https://ieeexplore.ieee.org/abstract/document/9468982)]Moving Object Segmentation in 3D LiDAR Data: A Learning-based Approach Exploiting Sequential Data. [[code](https://github.com/PRBonn/LiDAR-MOS)]![Github stars](https://img.shields.io/github/stars/PRBonn/LiDAR-MOS.svg)[__`out.`__ __`pc.`__] :fire: :star:
- [[RAL](https://ieeexplore.ieee.org/document/9361109)]ERASOR: Egocentric Ratio of Pseudo Occupancy-Based Dynamic Object Removal for Static 3D Point Cloud Map Building. [[code](https://github.com/LimHyungTae/ERASOR)]![Github stars](https://img.shields.io/github/stars/LimHyungTae/ERASOR.svg) [__`out.`__ __`pc.`__] :fire: :star:
- [[RAL](https://ieeexplore.ieee.org/document/9309360)]PointMoSeg: Sparse Tensor-Based End-to-End Moving-Obstacle Segmentation in 3-D Lidar Point Clouds for Autonomous Driving.[__`out.`__ __`pc.`__]
- [[ECMR](https://ieeexplore.ieee.org/document/9568799)]Mapping the Static Parts of Dynamic Scenes from 3D LiDAR Point Clouds Exploiting Ground Segmentation.[__`out.`__ __`pc.`__]

### 2022

- [[TPAMI](https://ieeexplore.ieee.org/document/9495168)]Cylindrical and Asymmetrical 3D Convolution Networks for LiDAR-Based Perception.[[code](https://github.com/xinge008/Cylinder3D)]![Github stars](https://img.shields.io/github/stars/xinge008/Cylinder3D.svg) :fire: :star:
- [[IROS](https://ieeexplore.ieee.org/document/9981210)]Efficient Spatial-Temporal Information Fusion for LiDAR-Based 3D Moving Object Segmentation.[[code](https://github.com/haomo-ai/MotionSeg3D)]![Github stars](https://img.shields.io/github/stars/haomo-ai/MotionSeg3D) [__`out.`__ __`pc.`__] :fire:
- [[IROS](https://ieeexplore.ieee.org/abstract/document/9981500)]PUA-MOS: End-to-End Point-wise Uncertainty Weighted Aggregation for Moving Object Segmentation.[[code](https://github.com/chengchi-qy/PUA-MOS)]![Github stars](https://img.shields.io/github/stars/chengchi-qy/PUA-MOS)[__`out.`__ __`pc.`__]
- [[RAL](https://ieeexplore.ieee.org/document/9806157)]RVMOS: Range-View Moving Object Segmentation Leveraged by Semantic and Motion Features.[__`out.`__ __`pc.`__]
- [[RAL](https://ieeexplore.ieee.org/document/9796597)]Receding Moving Object Segmentation in 3D LiDAR Data Using Sparse 4D Convolutions.[[code](https://github.com/PRBonn/4DMOS)]![Github stars](https://img.shields.io/github/stars/PRBonn/4DMOS) [__`out.`__ __`pc.`__] :fire:
- [[WACV](https://openaccess.thecvf.com/content/WACV2023/html/Kreutz_Unsupervised_4D_LiDAR_Moving_Object_Segmentation_in_Stationary_Settings_With_WACV_2023_paper.html)]Unsupervised 4D LiDAR Moving Object Segmentation in Stationary Settings with Multivariate Occupancy Time Series.[[code](https://github.com/thkreutz/umosmots?tab=readme-ov-file)]![Github stars](https://img.shields.io/github/stars/thkreutz/umosmots?tab=readme-ov-file) [__`out.`__ __`pc.`__]
- [[RAL](https://ieeexplore.ieee.org/document/9756222)]Automatic Labeling to Generate Training Data for Online LiDAR-Based Moving Object Segmentation.[[code](https://github.com/PRBonn/auto-mos)]![Github stars](https://img.shields.io/github/stars/PRBonn/auto-mos) [__`out.`__ __`pc.`__] :star:

### 2023

- [[IROS](https://ieeexplore.ieee.org/abstract/document/10342277)]InsMOS: Instance-Aware Moving Object Segmentation in LiDAR Data.[[code](https://github.com/nubot-nudt/InsMOS)]![Github stars](https://img.shields.io/github/stars/nubot-nudt/InsMOS.svg)  [__`out.`__ __`pc.`__] :fire:
- [[IROS](https://ieeexplore.ieee.org/document/10341426)]LiDAR-SGMOS: Semantics-Guided Moving Object Segmentation with 3D LiDAR.[__`out.`__ __`pc.`__]
- [[RAL](https://ieeexplore.ieee.org/abstract/document/10173578)]Building Volumetric Beliefs for Dynamic Environments Exploiting Map-Based Moving Object Segmentation.[[code](https://github.com/PRBonn/MapMOS)]![Github stars](https://img.shields.io/github/stars/PRBonn/MapMOS.svg)  [__`out.`__ __`pc.`__] :fire:
- [[RAL](https://ieeexplore.ieee.org/document/10287575)]MotionBEV: Attention-Aware Online LiDAR Moving Object Segmentation With Bird’s Eye View Based Appearance and Motion Features.[[code](https://github.com/xiekkki/motionbev)]![Github stars](https://img.shields.io/github/stars/xiekkki/motionbev.svg)[__`out.`__ __`pc.`__]
- [[RAL](https://ieeexplore.ieee.org/document/10218983)]Dynablox: Real-Time Detection of Diverse Dynamic Objects in Complex Environments.[[code](https://github.com/ethz-asl/dynablox)]![Github stars](https://img.shields.io/github/stars/ethz-asl/dynablox.svg)[__`out.`__ __`ind.`__ __`pc.`__] :fire:
- [[TRO](https://ieeexplore.ieee.org/document/10339905)]Radar Instance Transformer: Reliable Moving Instance Segmentation in Sparse Radar Point Clouds.[__`out.`__ __`rad.`__]
- [[ICCV](https://openaccess.thecvf.com/content/CVPR2023/html/Liu_MarS3D_A_Plug-and-Play_Motion-Aware_Model_for_Semantic_Segmentation_on_Multi-Scan_CVPR_2023_paper.html)]MarS3D: A Plug-and-Play Motion-Aware Model for Semantic Segmentation on Multi-Scan 3D Point Clouds.[[code](https://github.com/CVMI-Lab/MarS3D)]![Github stars](https://img.shields.io/github/stars/CVMI-Lab/MarS3D.svg)  [__`out.`__ __`pc.`__]
- [[Sensors](https://www.mdpi.com/1424-8220/23/1/547)]Real-Time LiDAR Point-Cloud Moving Object Segmentation for Autonomous Driving.[__`out.`__ __`pc.`__]
- [[IJAEOG](https://www.sciencedirect.com/science/article/pii/S1569843223003126)]An efficient image-guided-based 3D point cloud moving object segmentation with transformer-attention in autonomous driving.[__`out.`__ __`pc.`__ __`img.`__]
- [[Arxiv](https://arxiv.org/pdf/2307.09044)]3D-SeqMOS: A Novel Sequential 3D Moving Object Segmentation in Autonomous Driving.[__`out.`__ __`pc.`__]

### 2024

- [[ICRA](https://arxiv.org/abs/2401.17023)]MF-MOS: A Motion-Focused Model for Moving Object Segmentation.[[code](https://github.com/SCNU-RISLAB/MF-MOS)]![Github stars](https://img.shields.io/github/stars/SCNU-RISLAB/MF-MOS.svg)[__`out.`__ __`pc.`__]
- [[Arxiv](https://arxiv.org/abs/2404.12794)]MambaMOS: LiDAR-based 3D Moving Object Segmentation with Motion-aware State Space Model.[[code](https://github.com/Terminal-K/MambaMOS)]![Github stars](https://img.shields.io/github/stars/Terminal-K/MambaMOS.svg)[**`out.`** **`pc.`**]
- [[Arxiv](https://arxiv.org/abs/2402.14380)]RadarMOSEVE: A Spatial-Temporal Transformer Network for Radar-Only Moving Object Segmentation and Ego-Velocity Estimation.[[code](https://github.com/ORCA-Uboat/RadarMOSEVE)]![Github stars](https://img.shields.io/github/stars/ORCA-Uboat/RadarMOSEVE.svg)[__`out.`__ __`rad.`__]
- [[Arxiv](https://arxiv.org/abs/2406.16279)]SegNet4D: Effective and Efficient 4D LiDAR Semantic Segmentation in Autonomous Driving Environments.[[code](https://github.com/nubot-nudt/SegNet4D)]![Github stars](https://img.shields.io/github/stars/nubot-nudt/SegNet4D.svg)[**`out.`** **`pc.`**]

