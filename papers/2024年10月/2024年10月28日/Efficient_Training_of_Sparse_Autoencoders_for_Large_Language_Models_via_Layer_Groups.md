# 通过层组实现大型语言模型稀疏自编码器的高效训练

发布时间：2024年10月28日

`LLM理论` `语言模型` `机器学习`

> Efficient Training of Sparse Autoencoders for Large Language Models via Layer Groups

# 摘要

> 稀疏自编码器（SAEs）近来被当作一种无监督方式，用于探究大型语言模型（LLMs）的内在运作机制。它们借助可解释特征的稀疏线性组合来重构模型的激活。不过，训练 SAEs 的计算量颇为庞大，特别是在模型规模和复杂度增大时。为应对此挑战，我们提出了一种新颖的训练策略，将每层一个的训练 SAEs 数量减少为一组连续层一个。我们在 Pythia 160M 上的实验结果表明，在不损害重构质量和下游任务性能的前提下，速度最多可提升 6 倍。所以，层聚类是在现代 LLMs 中训练 SAEs 的高效途径。

> Sparse AutoEnocders (SAEs) have recently been employed as an unsupervised approach for understanding the inner workings of Large Language Models (LLMs). They reconstruct the model's activations with a sparse linear combination of interpretable features. However, training SAEs is computationally intensive, especially as models grow in size and complexity. To address this challenge, we propose a novel training strategy that reduces the number of trained SAEs from one per layer to one for a given group of contiguous layers. Our experimental results on Pythia 160M highlight a speedup of up to 6x without compromising the reconstruction quality and performance on downstream tasks. Therefore, layer clustering presents an efficient approach to train SAEs in modern LLMs.

[Arxiv](https://arxiv.org/abs/2410.21508)