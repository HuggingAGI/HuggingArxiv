# Hi-SLAM：通过分层分类高斯平滑技术，在 SLAM 中大幅提升语义扩展能力

发布时间：2024年09月19日

`LLM应用` `机器人` `计算机视觉`

> Hi-SLAM: Scaling-up Semantics in SLAM with a Hierarchically Categorical Gaussian Splatting

# 摘要

> 我们推出了 Hi-SLAM，这是一种创新的语义 3D 高斯 Splatting SLAM 方法，通过分层类别表示，实现了精准的 3D 语义地图构建、扩展能力以及 3D 世界中的语义标签预测。随着环境复杂性的提升，语义 SLAM 系统的参数需求激增，使得场景理解既具挑战性又成本高昂。为此，我们设计了一种分层表示，将语义信息高效编码至 3D 高斯 Splatting 中，充分利用了大型语言模型的优势。同时，我们引入了一种新的语义损失函数，通过层间与跨层优化，进一步提升语义信息的处理效率。此外，我们对整个 SLAM 系统进行了优化，显著提升了跟踪与地图构建的性能。实验表明，Hi-SLAM 在地图构建与跟踪精度上超越了现有方法，操作速度提升了一倍。在小型合成场景的语义分割渲染中，Hi-SLAM 表现出色，存储与训练时间大幅减少。渲染速度更是惊人，语义信息下达到 2,000 FPS，无语义信息时高达 3,000 FPS。最引人注目的是，Hi-SLAM 能够处理包含超过 500 个语义类别的复杂现实场景，展现了其强大的扩展潜力。

> We propose Hi-SLAM, a semantic 3D Gaussian Splatting SLAM method featuring a novel hierarchical categorical representation, which enables accurate global 3D semantic mapping, scaling-up capability, and explicit semantic label prediction in the 3D world. The parameter usage in semantic SLAM systems increases significantly with the growing complexity of the environment, making it particularly challenging and costly for scene understanding. To address this problem, we introduce a novel hierarchical representation that encodes semantic information in a compact form into 3D Gaussian Splatting, leveraging the capabilities of large language models (LLMs). We further introduce a novel semantic loss designed to optimize hierarchical semantic information through both inter-level and cross-level optimization. Furthermore, we enhance the whole SLAM system, resulting in improved tracking and mapping performance. Our Hi-SLAM outperforms existing dense SLAM methods in both mapping and tracking accuracy, while achieving a 2x operation speed-up. Additionally, it exhibits competitive performance in rendering semantic segmentation in small synthetic scenes, with significantly reduced storage and training time requirements. Rendering FPS impressively reaches 2,000 with semantic information and 3,000 without it. Most notably, it showcases the capability of handling the complex real-world scene with more than 500 semantic classes, highlighting its valuable scaling-up capability.

[Arxiv](https://arxiv.org/abs/2409.12518)