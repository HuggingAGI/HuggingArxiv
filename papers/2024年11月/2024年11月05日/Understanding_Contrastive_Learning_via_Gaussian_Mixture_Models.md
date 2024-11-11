# 通过高斯混合模型理解对比学习

发布时间：2024年11月05日

`LLM理论` `机器学习` `数据分析`

> Understanding Contrastive Learning via Gaussian Mixture Models

# 摘要

> 对比学习试图从未标记的数据中学习表示；它通过一种损失函数来实现，该损失函数鼓励一个点的嵌入与其增强的嵌入接近，而与随机其他点的嵌入远离。这个简单的想法表现得非常好，但理论上还不清楚为什么会这样。在本文中，我们在一个自然的背景下分析对比学习（特别是 InfoNCE 损失）：高斯混合模型中的降维。至关重要的是，我们将数据点的增强定义为从相同的底层混合组件中另一个独立的抽取。我们表明，即使高斯不是各向同性的，普通的 InfoNCE 也能够找到最优的低维子空间——这是普通的频谱技术无法做到的。我们进一步将我们的分析扩展到多模态对比学习算法（例如，CLIP）。在这种情况下，我们表明对比学习学习到了费希尔最优子空间的子集，有效地从学习到的表示中过滤掉了所有的噪声。

> Contrastive learning attempts to learn representations from un-labeled data; it does so via a loss function that encourages the embedding of a point to be close to that of its augmentations, and far from the embeddings of random other points. This simple idea performs remarkably well, yet it is not precisely theoretically understood why this is the case. In this paper we analyze contrastive learning (specifically, the InfoNCE loss) in a natural context: dimensionality reduction in Gaussian Mixture Models. Crucially, we define an augmentation of a data point as being another independent draw from the same underlying mixture component. We show that vanilla InfoNCE is able to find the optimal lower-dimensional subspace even when the Gaussians are not isotropic -- something that vanilla spectral techniques cannot do. We further extend our analyses to multi-modal contrastive learning algorithms (e.g., CLIP). In this setting we show that contrastive learning learns the subset of fisher-optimal subspace, effectively filtering out all the noise from the learnt representations.

[Arxiv](https://arxiv.org/abs/2411.03517)