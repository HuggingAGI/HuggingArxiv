# QuadMamba：利用四叉树学习视觉状态空间模型的选择性扫描

发布时间：2024年10月09日

`LLM理论` `计算机视觉` `机器学习`

> QuadMamba: Learning Quadtree-based Selective Scan for Visual State Space Model

# 摘要

> 近期，Mamba 等状态空间模型在性能上超越了 Transformer，特别是在将计算复杂度从二次降至线性方面表现突出。然而，由于视觉数据的空间局部性和信息粒度差异，将 Mamba 应用于视觉任务面临挑战。现有方法或破坏图像局部性，或限制长程建模能力。为此，我们推出了 QuadMamba，通过四叉树分割和扫描，有效捕捉多粒度局部依赖。该模型保留二维局部性，自适应划分窗口，并采用全向窗口移动策略，提升特征完整性。结合 Gumbel-Softmax 的序列掩码策略，使四叉树分割可端到端训练。实验证明，QuadMamba 在图像分类、对象检测等多项视觉任务中达到顶尖水平。项目代码已开源至 https://github.com/VISIONSJTU/QuadMamba。

> Recent advancements in State Space Models, notably Mamba, have demonstrated superior performance over the dominant Transformer models, particularly in reducing the computational complexity from quadratic to linear. Yet, difficulties in adapting Mamba from language to vision tasks arise due to the distinct characteristics of visual data, such as the spatial locality and adjacency within images and large variations in information granularity across visual tokens. Existing vision Mamba approaches either flatten tokens into sequences in a raster scan fashion, which breaks the local adjacency of images, or manually partition tokens into windows, which limits their long-range modeling and generalization capabilities. To address these limitations, we present a new vision Mamba model, coined QuadMamba, that effectively captures local dependencies of varying granularities via quadtree-based image partition and scan. Concretely, our lightweight quadtree-based scan module learns to preserve the 2D locality of spatial regions within learned window quadrants. The module estimates the locality score of each token from their features, before adaptively partitioning tokens into window quadrants. An omnidirectional window shifting scheme is also introduced to capture more intact and informative features across different local regions. To make the discretized quadtree partition end-to-end trainable, we further devise a sequence masking strategy based on Gumbel-Softmax and its straight-through gradient estimator. Extensive experiments demonstrate that QuadMamba achieves state-of-the-art performance in various vision tasks, including image classification, object detection, instance segmentation, and semantic segmentation. The code is in https://github.com/VISIONSJTU/QuadMamba.

[Arxiv](https://arxiv.org/abs/2410.06806)