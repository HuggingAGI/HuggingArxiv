# 用于热光谱分布正则化红外图像超分辨率的 Contourlet 细化门框架

发布时间：2024年11月19日

`其他` `计算机视觉`

> Contourlet Refinement Gate Framework for Thermal Spectrum Distribution Regularized Infrared Image Super-Resolution

# 摘要

> 图像超分辨率（SR）是个经典且活跃的低级视觉问题，旨在由低分辨率（LR）图像重构高分辨率（HR）图像，是图像增强的关键技术。当下处理SR任务的方法，像基于Transformer和基于扩散的那些，要么专注于提取RGB图像特征，要么假定相似的退化模式，忽略了红外与可见光图像间固有的模态差异。直接用于红外图像SR任务时，这些方法必然会扭曲红外光谱分布，影响下游任务中的机器感知。在本工作中，我们重视红外光谱分布的保真度，提出了Contourlet细化门框架，在保持光谱分布保真度的同时恢复红外模态的特定特征。我们的方法从多尺度、多方向的红外光谱分解中捕获高通子带，通过门架构恢复红外退化信息。所提的光谱保真度损失在重建时规范了光谱频率分布，保证高频和低频成分得以保留，维持了红外特定特征的保真度。我们提出了两阶段的提示学习优化，引导模型从LR退化中学习红外HR特征。大量实验表明，我们的方法在视觉和感知任务中都比现有的图像SR模型出色，同时显著增强了下游任务中的机器感知。我们的代码可在https://github.com/hey-it-s-me/CoRPLE获取。

> Image super-resolution (SR) is a classical yet still active low-level vision problem that aims to reconstruct high-resolution (HR) images from their low-resolution (LR) counterparts, serving as a key technique for image enhancement. Current approaches to address SR tasks, such as transformer-based and diffusion-based methods, are either dedicated to extracting RGB image features or assuming similar degradation patterns, neglecting the inherent modal disparities between infrared and visible images. When directly applied to infrared image SR tasks, these methods inevitably distort the infrared spectral distribution, compromising the machine perception in downstream tasks. In this work, we emphasize the infrared spectral distribution fidelity and propose a Contourlet refinement gate framework to restore infrared modal-specific features while preserving spectral distribution fidelity. Our approach captures high-pass subbands from multi-scale and multi-directional infrared spectral decomposition to recover infrared-degraded information through a gate architecture. The proposed Spectral Fidelity Loss regularizes the spectral frequency distribution during reconstruction, which ensures the preservation of both high- and low-frequency components and maintains the fidelity of infrared-specific features. We propose a two-stage prompt-learning optimization to guide the model in learning infrared HR characteristics from LR degradation. Extensive experiments demonstrate that our approach outperforms existing image SR models in both visual and perceptual tasks while notably enhancing machine perception in downstream tasks. Our code is available at https://github.com/hey-it-s-me/CoRPLE.

[Arxiv](https://arxiv.org/abs/2411.12530)