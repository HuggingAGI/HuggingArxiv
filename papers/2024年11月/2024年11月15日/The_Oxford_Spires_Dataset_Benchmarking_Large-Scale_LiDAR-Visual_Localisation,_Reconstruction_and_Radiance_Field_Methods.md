# 《牛津尖顶数据集：对大规模激光雷达视觉定位、重建及辐射场方法的基准测评》

发布时间：2024年11月15日

`其他` `地理信息` `计算机视觉`

> The Oxford Spires Dataset: Benchmarking Large-Scale LiDAR-Visual Localisation, Reconstruction and Radiance Field Methods

# 摘要

> 本文介绍了一个在牛津知名地标及其周边采集的大规模多模态数据集，该数据集通过定制的多传感器感知单元以及地面激光雷达扫描仪（TLS）提供的毫米级精确地图获取。感知单元涵盖了三个同步的全局快门彩色相机、一个汽车 3D 激光雷达扫描仪以及一个惯性传感器，且均经过精准校准。我们还为定位、重建和新视图合成等任务设立了基准，借此能够对同时定位和映射（SLAM）方法、运动结构（SfM）、多视图立体（MVS）方法以及诸如神经辐射场（NeRF）和 3D 高斯喷溅等辐射场方法进行评估。为评估 3D 重建效果，以 TLS 3D 模型作为标准。通过将移动激光雷达扫描与 TLS 3D 模型进行注册来计算定位标准。对辐射场方法的评估，不仅采用从输入轨迹采样的姿态，还使用来自远离训练姿态的轨迹的视点。我们的评估揭示了当下先进辐射场方法的一个关键局限：表明它们易于过度拟合训练姿态/图像，对非顺序姿态的泛化能力欠佳。与使用相同视觉输入的 MVS 系统相比，其在 3D 重建方面表现逊色。我们的数据集和基准旨在推动辐射场方法与 SLAM 系统更优地融合。原始及处理后的数据，连同用于解析和评估的软件，均可在 https://dynamic.robots.ox.ac.uk/datasets/oxford-spires/ 获取。

> This paper introduces a large-scale multi-modal dataset captured in and around well-known landmarks in Oxford using a custom-built multi-sensor perception unit as well as a millimetre-accurate map from a Terrestrial LiDAR Scanner (TLS). The perception unit includes three synchronised global shutter colour cameras, an automotive 3D LiDAR scanner, and an inertial sensor - all precisely calibrated. We also establish benchmarks for tasks involving localisation, reconstruction, and novel-view synthesis, which enable the evaluation of Simultaneous Localisation and Mapping (SLAM) methods, Structure-from-Motion (SfM) and Multi-view Stereo (MVS) methods as well as radiance field methods such as Neural Radiance Fields (NeRF) and 3D Gaussian Splatting. To evaluate 3D reconstruction the TLS 3D models are used as ground truth. Localisation ground truth is computed by registering the mobile LiDAR scans to the TLS 3D models. Radiance field methods are evaluated not only with poses sampled from the input trajectory, but also from viewpoints that are from trajectories which are distant from the training poses. Our evaluation demonstrates a key limitation of state-of-the-art radiance field methods: we show that they tend to overfit to the training poses/images and do not generalise well to out-of-sequence poses. They also underperform in 3D reconstruction compared to MVS systems using the same visual inputs. Our dataset and benchmarks are intended to facilitate better integration of radiance field methods and SLAM systems. The raw and processed data, along with software for parsing and evaluation, can be accessed at https://dynamic.robots.ox.ac.uk/datasets/oxford-spires/.

[Arxiv](https://arxiv.org/abs/2411.10546)