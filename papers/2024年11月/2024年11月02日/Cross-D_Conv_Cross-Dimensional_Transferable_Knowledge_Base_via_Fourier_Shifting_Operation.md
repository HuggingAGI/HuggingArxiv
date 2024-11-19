# Cross-D Conv: 借助傅里叶变换操作实现的跨维度可转移知识库

发布时间：2024年11月02日

`其他` `生物医学` `医学成像`

> Cross-D Conv: Cross-Dimensional Transferable Knowledge Base via Fourier Shifting Operation

# 摘要

> 在生物医学成像分析领域，2D 与 3D 数据的二分现象构成了重大挑战。3D 数据虽在现实应用中更具优势，但其在各模态中的可用性较低，大规模训练难度大，而 2D 样本数量多却不够全面。本文引入了 Cross-D Conv 操作，这一创新方法通过在傅里叶域学习相移来缩小维度差距。我们的方法能让 2D 和 3D 卷积操作实现无缝权重转移，有力推动了跨维度学习。所提出的架构借助丰富的 2D 训练数据提升 3D 模型性能，为解决 3D 医学模型预训练中的多模态数据稀缺难题提供了实用方案。在 RadImagenet（2D）和多模态（3D）数据集上的实验验证显示，我们的方法在特征质量评估方面的表现与传统方法相当甚至更优。增强的卷积操作为医学成像中开发高效的分类和分割模型创造了新契机。此项工作标志着跨维度和多模态医学图像分析的进步，为在 3D 模型预训练中运用 2D 先验知识或反之提供了坚实框架，同时还保持了计算效率。

> In biomedical imaging analysis, the dichotomy between 2D and 3D data presents a significant challenge. While 3D volumes offer superior real-world applicability, they are less available for each modality and not easy to train in large scale, whereas 2D samples are abundant but less comprehensive. This paper introduces the Cross-D Conv operation, a novel approach that bridges the dimensional gap by learning the phase shifting in the Fourier domain. Our method enables seamless weight transfer between 2D and 3D convolution operations, effectively facilitating cross-dimensional learning. The proposed architecture leverages the abundance of 2D training data to enhance 3D model performance, offering a practical solution to the multimodal data scarcity challenge in 3D medical model pretraining. Experimental validation on the RadImagenet (2D) and multimodal (3D) sets demonstrates that our approach achieves comparable or superior performance in feature quality assessment comparable to conventional methods. The enhanced convolution operation presents new opportunities for developing efficient classification and segmentation models in medical imaging. This work represents an advancement in cross-dimensional and multi-modal medical image analysis, offering a robust framework for utilizing 2D priors in 3D model pretraining or vice versa while maintaining computational efficiency.

[Arxiv](https://arxiv.org/abs/2411.02441)