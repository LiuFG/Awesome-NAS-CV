# Awesome NAS CV
This repo is a curated list of NAS classified by CV tasks. It is may easier to study NAS for different CV fields.

Inspired by [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision), [awesome-adversarial-machine-learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning), [awesome-deep-learning-papers](https://github.com/terryum/awesome-deep-learning-papers), [awesome-architecture-search](https://github.com/markdtw/awesome-architecture-search) and [Awesome-NAS](https://github.com/D-X-Y/Awesome-NAS).

**Abbreviation** is same as [Awesome-NAS](https://github.com/D-X-Y/Awesome-NAS).

| Type        |       G        |           RL           |           EA            |    Other    |
| :---------- | :------------: | :--------------------: | :---------------------: | :---------: |
| Explanation | gradient-based | reinforcement learning | evaluationary algorithm | other types |

The code is recorded only if it includes search stage instead of only train and inference. 

The line is copied if the paper is efficient for several CV tasks.

> Classification is out of list. Because almost all basic NAS algorithm are tested on Classification task.

## Table of Contents

- [Segmentation](#segmentation)
  * [2020](#2020)
  * [2019](#2019)
- [2D Detection](#2d-detection)
  * [2020](#2020-1)
  * [2019](#2019-1)
- [Mobile](#Mobile)
  * [2020](#2020-2)
  * [2019](#2019-2)

## Segmentation

### 2020

| Title                                                        | Venue | Type  |                         Code                          | Blog |
| :----------------------------------------------------------- | :---: | :---: | :---------------------------------------------------: | :--: |
| [Fast Neural Network Adaptation via Parameter Remapping and Architecture Search](https://arxiv.org/abs/2001.02525) | ICLR  |   G   |                                                       |      |
| [FasterSeg: Searching for Faster Real-time Semantic Segmentation](https://arxiv.org/abs/1912.10917) | ICLR  | Other |   [Github](https://github.com/TAMU-VITA/FasterSeg)    |      |
| [Graph-guided Architecture Search for Real-time Semantic Segmentation](https://arxiv.org/abs/1909.06793) | CVPR  | Other | [Github(wait)](https://github.com/L-Lighter/LightNet) |      |
| [Learning Dynamic Routing for Semantic Segmentation](https://arxiv.org/abs/2003.10401) | CVPR  |       | [Github](https://github.com/yanwei-li/DynamicRouting) |      |

### 2019

| Title                                                        |                            Venue                             | Type |                        Code                         | Blog |
| :----------------------------------------------------------- | :----------------------------------------------------------: | :--: | :-------------------------------------------------: | :--: |
| [SqueezeNAS: Fast neural architecture search for faster semantic segmentation](https://arxiv.org/abs/1908.01748) |                        ICCV Workshop                         |  G   |  [Github](https://github.com/ashaw596/squeezenas)   |      |
| [SegNAS3D: Network Architecture Search with Derivative-Free Global Optimization for 3D Image Segmentation](https://arxiv.org/abs/1909.05962?context=cs) | [Smart Materials and Structures](https://iopscience.iop.org/journal/0964-1726) |      |                          -                          |      |
| [Auto-DeepLab: Hierarchical Neural Architecture Search for Semantic Image Segmentation](https://arxiv.org/abs/1901.02985) |                             CVPR                             |  G   | [Github](https://github.com/MenghaoGuo/AutoDeeplab) |      |
| [Customizable architecture search for semantic segmentation](https://arxiv.org/abs/1908.09550) |                             CVPR                             |      |                                                     |      |
| [Partial Order Pruning: for Best Speed/Accuracy Trade-off in Neural Architecture Search](https://arxiv.org/abs/1903.03777) |                             CVPR                             |  EA  |                                                     |      |

## 2D Detection

### 2020

| Title                                                        | Venue | Type  |                       Code                       | Blog |
| :----------------------------------------------------------- | :---: | :---: | :----------------------------------------------: | :--: |
| [NAS-FCOS: Fast Neural Architecture Search for Object Detection](https://arxiv.org/abs/1906.04423) | CVPR  |  RL   |                        -                         |      |
| [SM-NAS: Structural-to-Modular Neural Architecture Search for Object Detection](https://arxiv.org/abs/1911.09929) | AAAI  |  EA   |                        -                         |      |
| [EfficientDet: Scalable and Efficient Object Detection](https://arxiv.org/abs/1911.09070) | CVPR  |  RL   |                                                  |      |
| [Computation Reallocation for Object Detection](https://openreview.net/forum?id=SkxLFaNKwB) | ICLR  | Other |                        -                         |      |
| [Fast Neural Network Adaptation via Parameter Remapping and Architecture Search](https://arxiv.org/abs/2001.02525) | ICLR  |   G   |                                                  |      |
| [SpineNet: Learning Scale-Permuted Backbone for Recognition and Localization](https://arxiv.org/abs/1912.05027) | CVPR  |       |                                                  |      |
| [Computation Reallocation for Object Detection](https://openreview.net/forum?id=SkxLFaNKwB) | ICLR  |  EA   |                                                  |      |
| [MobileDets: Searching for Object Detection Architectures for Mobile Accelerators](https://arxiv.org/abs/2004.14525) |       |       |                                                  |      |
| [Hit-Detector: Hierarchical Trinity Architecture Search for Object Detection](https://arxiv.org/abs/2003.11818) | CVPR  |       | [Github](https://github.com/ggjy/HitDet.pytorch) |      |
| [SP-NAS: Serial-to-Parallel Backbone Search for Object Detection](http://openaccess.thecvf.com/content_CVPR_2020/papers/Jiang_SP-NAS_Serial-to-Parallel_Backbone_Search_for_Object_Detection_CVPR_2020_paper.pdf) | CVPR  |       |                                                  |      |
### 2019

| Title                                                        |  Venue  | Type |                       Code                       |   Blog    |
| :----------------------------------------------------------- | :-----: | :--: | :----------------------------------------------: | :-------: |
| [DetNAS: Backbone Search for ObjectDetection](https://arxiv.org/abs/1903.10979) | NeurIPS |  EA  | [Github](https://github.com/megvii-model/DetNAS) | [zh]/[en] |
| [NAS-FPN: Learning Scalable Feature Pyramid Architecture for Object Detection](https://arxiv.org/abs/1904.07392) |  CVPR   |  RL  |                        -                         |           |
| [Auto-FPN: Automatic Network Architecture Adaptation for Object Detection](http://openaccess.thecvf.com/content_ICCV_2019/papers/Xu_Auto-FPN_Automatic_Network_Architecture_Adaptation_for_Object_Detection_Beyond_Classification_ICCV_2019_paper.pdf) |  ICCV   |  G   |                                                  |           |
| [Efficient Neural Architecture Transformation Search in Channel-Level for Object Detection](https://arxiv.org/abs/1909.02293) | NeurIPS |  G   |                                                  |           |
| [MnasFPN : Learning Latency-aware Pyramid Architecture for Object Detection on Mobile Devices](https://arxiv.org/abs/1912.01106) |  Arxiv  |      |                                                  |           |
|                                                              |         |      |                                                  |           |

## Mobile

### 2020

| Title                                                        | Venue  | Type |                         Code                          | Blog |
| :----------------------------------------------------------- | :----: | :--: | :---------------------------------------------------: | ---- |
| [Once for All: Train One Network and Specialize it for Efficient Deployment](https://arxiv.org/abs/1908.09791) |  ICLR  |      | [Github](https://github.com/mit-han-lab/once-for-all) |      |
| [MoGA: Searching Beyond MobileNetV3](https://arxiv.org/abs/1908.01314) | ICASSP |      |    [Github](https://github.com/xiaomi-automl/MoGA)    |      |
| [FBNetV2: Differentiable Neural Architecture Search for Spatial and Channel Dimensions](https://arxiv.org/abs/2004.05565) |        |      |                                                       |      |
| [FBNetV3: Joint Architecture-Recipe Search using Neural Acquisition Function](https://arxiv.org/abs/2006.02049) |        |      |                                                       |      |
| [MobileDets: Searching for Object Detection Architectures for Mobile Accelerators](https://arxiv.org/abs/2004.14525) |        |      |                                                       |      |
| [Neural Architecture Search for Lightweight Non-Local Networks](https://cs.jhu.edu/~alanlab/Pubs20/li2020neural.pdf) |  CVPR  |      |     [Github](https://github.com/LiYingwei/AutoNL)     |      |

### 2019

| Title                                                        | Venue | Type |                          Code                           | Blog |
| :----------------------------------------------------------- | :---: | :--: | :-----------------------------------------------------: | ---- |
| [ProxylessNAS: Direct Neural Architecture Search on Target Task and Hardware](https://arxiv.org/abs/1812.00332) | ICLR  |  G   |  [Github](https://github.com/mit-han-lab/proxylessnas)  |      |
| [Searching for MobileNetV3](https://arxiv.org/abs/1905.02244) | ICCV  |      | [Github](https://github.com/xiaolai-sqlai/mobilenetv3)  |      |
| [MnasNet: Platform-Aware Neural Architecture Search for Mobile](https://arxiv.org/abs/1807.11626) | CVPR  |      | [Github](https://github.com/AnjieCheng/MnasNet-PyTorch) |      |
| [FBNet: Hardware-Aware Efficient ConvNet Design via Differentiable Neural Architecture Search](https://arxiv.org/abs/1812.03443) |       |      |    [Github](https://github.com/AnnaAraslanova/FBNet)    |      |
|                                                              |       |      |                                                         |      |

