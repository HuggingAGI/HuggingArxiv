# LFSamba：将 SAM 与 Mamba 相结合用于光场显著目标检测

发布时间：2024年11月10日

`其他` `机器人视觉` `虚拟现实`

> LFSamba: Marry SAM with Mamba for Light Field Salient Object Detection

# 摘要

> 一个光场相机可以使用包含丰富空间几何信息的捕获多焦点图像重建 3D 场景，增强了在立体摄影、虚拟现实和机器人视觉中的应用。在这项工作中，引入了一种用于多焦点光场图像的最先进的显著目标检测模型，称为 LFSamba，以强调四个主要见解：（a）高效特征提取，其中 SAM 用于提取模态感知的判别特征；（b）切片间关系建模，利用 Mamba 捕获跨多个焦点切片的长程依赖关系，从而提取隐式深度线索；（c）模态间关系建模，利用 Mamba 整合全焦点和多焦点图像，实现相互增强；（d）弱监督学习能力，从现有的像素级掩码数据集中开发一个涂鸦注释数据集，为光场显著目标检测建立了第一个涂鸦监督基线。https://github.com/liuzywen/LFScribble

> A light field camera can reconstruct 3D scenes using captured multi-focus images that contain rich spatial geometric information, enhancing applications in stereoscopic photography, virtual reality, and robotic vision. In this work, a state-of-the-art salient object detection model for multi-focus light field images, called LFSamba, is introduced to emphasize four main insights: (a) Efficient feature extraction, where SAM is used to extract modality-aware discriminative features; (b) Inter-slice relation modeling, leveraging Mamba to capture long-range dependencies across multiple focal slices, thus extracting implicit depth cues; (c) Inter-modal relation modeling, utilizing Mamba to integrate all-focus and multi-focus images, enabling mutual enhancement; (d) Weakly supervised learning capability, developing a scribble annotation dataset from an existing pixel-level mask dataset, establishing the first scribble-supervised baseline for light field salient object detection.https://github.com/liuzywen/LFScribble

[Arxiv](https://arxiv.org/abs/2411.06652)