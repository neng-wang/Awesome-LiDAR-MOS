# Awesome-LiDAR-MOS [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
For anyone who wants to do research about 3D point cloud **Moving Object Segmentation (MOS)**

*Continuously updating!*

![mos](./pic/mos.gif)

## Benchmark

<div align="center">

| [SemanticKITTI](https://codalab.lisn.upsaclay.fr/competitions/708) | [MOE](https://codalab.lisn.upsaclay.fr/competitions/18028) |
| :----------------------------------------------------------: | :--------------------------------------------------------: |
| <img src="./pic/semantickitti.png" width="150" height="120"> |     <img src="./pic/moe.png" width="140" height="120">     |

</div>

## Dataset

1. [SemanticKITTI](http://semantic-kitti.org/)       (From [LMNet](https://github.com/PRBonn/LiDAR-MOS))
2. [KITTI-Road](https://github.com/haomo-ai/MotionSeg3D/blob/master/config/kitti_road_mos.md)             (From [MotionSeg3D](https://github.com/haomo-ai/MotionSeg3D))
3. [Apollo](https://www.ipb.uni-bonn.de/html/projects/apollo_dataset/LiDAR-MOS.zip)                     (From [MapMOS](https://github.com/PRBonn/MapMOS))
4. [nuScenes](https://github.com/PRBonn/MapMOS/blob/main/src/mapmos/datasets/nuscenes.py)               (From [MapMOS](https://github.com/PRBonn/MapMOS))
5. [KITTI-Tracking-19](https://www.ipb.uni-bonn.de/html/projects/kitti-tracking/post-processed/kitti-tracking.zip) (From [MapMOS](https://github.com/PRBonn/MapMOS))
6. [SipailouCampus](https://drive.google.com/file/d/1GnX9CMaH0AjRkkjtOpPv9F5vzqIcUhxR/view)   (From [MotionBEV](https://github.com/xiekkki/motionbev))
6. [HeLiMOS](https://sites.google.com/view/helimos/dataset)               (From [HeLiMOS](https://ieeexplore.ieee.org/document/10801938))
6. [MOE-Dataset](https://sites.google.com/view/moe-dataset)        (From [MOE](https://ieeexplore.ieee.org/document/10802513))

## Leader Board

- **SemanticKITTI**

| Method                | Val IoU[%] | Test IoU[%] |
| --------------------- | ---------- | ----------- |
| [Auto-MOS](#auto-mos) | -          | 62.3        |
| LMNet                 | 67.1       | 62.5        |
| 4DMOS                 | 71.9       | 65.2        |
| MotionSeg3D           | 68.1       | 70.2        |
| RVMOS                 | 71.2       | 74.7        |
| InsMOS                | 73.2       | 75.6        |
| MF-MOS                |            |             |
|                       |            |             |
|                       |            |             |
|                       |            |             |
|                       |            |             |
|                       |            |             |
|                       |            |             |
|                       |            |             |



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
- [[RAL](https://ieeexplore.ieee.org/document/9756222)]<a id="auto-mos"></a>Automatic Labeling to Generate Training Data for Online LiDAR-Based Moving Object Segmentation.[[code](https://github.com/PRBonn/auto-mos)]![Github stars](https://img.shields.io/github/stars/PRBonn/auto-mos) [__`out.`__ __`pc.`__] :star:

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
- [[TITS](https://ieeexplore.ieee.org/document/10529942)]3D-SeqMOS: A Novel Sequential 3D Moving Object Segmentation in Autonomous Driving.[__`out.`__ __`pc.`__]
- [[sensors](https://www.mdpi.com/1424-8220/23/1/547)]Real-Time LiDAR Point-Cloud Moving Object Segmentation for Autonomous Driving.[__`out.`__ __`pc.`__]   

### 2024

- [[ICRA](https://arxiv.org/abs/2401.17023)]MF-MOS: A Motion-Focused Model for Moving Object Segmentation.[[code](https://github.com/SCNU-RISLAB/MF-MOS)]![Github stars](https://img.shields.io/github/stars/SCNU-RISLAB/MF-MOS.svg)[__`out.`__ __`pc.`__]
- [[Arxiv](https://arxiv.org/abs/2402.14380)]RadarMOSEVE: A Spatial-Temporal Transformer Network for Radar-Only Moving Object Segmentation and Ego-Velocity Estimation.[[code](https://github.com/ORCA-Uboat/RadarMOSEVE)]![Github stars](https://img.shields.io/github/stars/ORCA-Uboat/RadarMOSEVE.svg)[__`out.`__ __`rad.`__]
- [[TASE](https://arxiv.org/abs/2406.16279)]SegNet4D: Efficient Instance-Aware 4D  Semantic Segmentation for LiDAR Point Cloud.[[code](https://github.com/nubot-nudt/SegNet4D)]![Github stars](https://img.shields.io/github/stars/nubot-nudt/SegNet4D.svg)[**`out.`** **`pc.`**]
- [[[TIM](CV-MOS: A Cross-View Model for Motion Segmentation)]CV-MOS: A Cross-View Model for Motion Segmentation.[[code](https://github.com/SCNU-RISLAB/CV-MOS)]![Github stars](https://img.shields.io/github/stars/SCNU-RISLAB/CV-MOS.svg)[__`out.`__ __`pc.`__]
- [[ACM MM](https://dl.acm.org/doi/abs/10.1145/3664647.3680578)]MambaMOS: LiDAR-based 3D Moving Object Segmentation with Motion-aware State Space Model.[[code](https://github.com/Terminal-K/MambaMOS)]![Github stars](https://img.shields.io/github/stars/Terminal-K/MambaMOS.svg)[__`out.`__ __`pc.`__]
- [[Nature Communications](https://www.nature.com/articles/s41467-023-44554-8)]Moving event detection from LiDAR point streams.[[code](https://github.com/hku-mars/M-detector)]![Github stars](https://img.shields.io/github/stars/hku-mars/M-detector.svg)[__`out.`__ __`pc.`__]
- [[TITS](https://ieeexplore.ieee.org/abstract/document/10623536)]Joint Scene Flow Estimation and Moving Object Segmentation on Rotational LiDAR Data.[[code](https://github.com/nubot-nudt/SFEMOS)]![Github stars](https://img.shields.io/github/stars/nubot-nudt/SFEMOS.svg)[__`out.`__ __`pc.`__]
- [[IROS](https://ieeexplore.ieee.org/document/10801938)]HeLiMOS: A Dataset for Moving Object Segmentation in 3D Point Clouds From Heterogeneous LiDAR Sensors.[[code](https://github.com/url-kaist/HeLiMOS-PointCloud-Toolbox)]![Github stars](https://img.shields.io/github/stars/url-kaist/HeLiMOS-PointCloud-Toolbox.svg)[__`out.`__ __`pc.`__]
- [[TIV](https://ieeexplore.ieee.org/document/10640268)]AWV-MOS-LIO: Adaptive Window Visibility based Moving Object Segmentation with LiDAR Inertial Odometry.[[code](https://github.com/KimSeongJun-kr/AWV-MOS)]![Github stars](https://img.shields.io/github/stars/KimSeongJun-kr/AWV-MOS.svg)[__`out.`__ __`pc.`__]
- [[IEEE Sens. J](https://ieeexplore.ieee.org/abstract/document/10700628)]Moving Object Segmentation Network for Multiview Fusion of Vehicle-Mounted LiDAR.[__`out.`__ __`pc.`__]
- [[IROS](https://ieeexplore.ieee.org/document/10802513)]MOE: A Dense LiDAR MOving Event Dataset, Detection Benchmark and LeaderBoard.[[code](https://github.com/DeepDuke/MOE-Dataset)]![Github stars](https://img.shields.io/github/stars/DeepDuke/MOE-Dataset.svg)[__`out.`__ __`pc.`__]
- [[TIM](https://ieeexplore.ieee.org/abstract/document/10399869)]SSF-MOS: Semantic Scene Flow Assisted Moving Object Segmentation for Autonomous Vehicles.[__`out.`__ __`pc.`__]
- [[RAL](https://ieeexplore.ieee.org/document/10777056)]4D-CS: Exploiting Cluster Prior for 4D Spatio-Temporal LiDAR Semantic Segmentation.[[code](https://github.com/NEU-REAL/4D-CS)]![Github stars](https://img.shields.io/github/stars/NEU-REAL/4D-CS.svg)[__`out.`__ __`pc.`__]

### 2025

- [[TIM](https://ieeexplore.ieee.org/abstract/document/10906374)]Real-Time Moving Object Detection for 3-D LiDAR Using Occlusion Accumulation in Range Image.[[code](https://github.com/JunhaAgu/Mapless_Moving)]![Github stars](https://img.shields.io/github/stars/JunhaAgu/Mapless_Moving.svg)[__`out.`__ __`pc.`__]
- [[IEEE IOT](https://ieeexplore.ieee.org/abstract/document/10930735)]FP-MOS: Frame-to-Frame Prediction for Dynamic Object Segmentation with LiDAR Data.[__`out.`__ __`pc.`__]
- [[Remote Sensing](https://www.mdpi.com/2072-4292/17/2/195)] Gradient  Enhancement Techniques and Motion Consistency Constraints for Moving  Object Segmentation in 3D LiDAR Point Clouds.[__`out.`__ __`pc.`__]
