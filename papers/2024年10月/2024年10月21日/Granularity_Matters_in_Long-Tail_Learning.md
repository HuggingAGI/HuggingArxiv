# 长尾学习中，粒度的把握至关重要。

发布时间：2024年10月21日

`LLM应用` `机器学习` `计算机视觉`

> Granularity Matters in Long-Tail Learning

# 摘要

> 在深度学习领域，如何平衡长尾数据分布一直是个难题。尽管重新加权和重新采样等方法能缓解不平衡问题，但样本多样性不足仍限制了模型对尾部类别特征的学习。我们提出了一种新视角，基于观察到细粒度数据集受不平衡影响较小。通过定量和定性研究，我们发现增加粒度能提升尾部类别特征的泛化能力。为此，我们提出通过引入视觉相似的开放集辅助类别来增加数据集粒度，以增强头部和尾部类别的表示学习。我们还利用大型语言模型自动搜索和检索辅助数据，并通过邻居沉默损失防止辅助类别干扰训练。在推理时，仅使用目标类别权重。实验表明，我们的方法在长尾基准上显著优于强基线方法。代码将公开。

> Balancing training on long-tail data distributions remains a long-standing challenge in deep learning. While methods such as re-weighting and re-sampling help alleviate the imbalance issue, limited sample diversity continues to hinder models from learning robust and generalizable feature representations, particularly for tail classes. In contrast to existing methods, we offer a novel perspective on long-tail learning, inspired by an observation: datasets with finer granularity tend to be less affected by data imbalance. In this paper, we investigate this phenomenon through both quantitative and qualitative studies, showing that increased granularity enhances the generalization of learned features in tail categories. Motivated by these findings, we propose a method to increase dataset granularity through category extrapolation. Specifically, we introduce open-set auxiliary classes that are visually similar to existing ones, aiming to enhance representation learning for both head and tail classes. This forms the core contribution and insight of our approach. To automate the curation of auxiliary data, we leverage large language models (LLMs) as knowledge bases to search for auxiliary categories and retrieve relevant images through web crawling. To prevent the overwhelming presence of auxiliary classes from disrupting training, we introduce a neighbor-silencing loss that encourages the model to focus on class discrimination within the target dataset. During inference, the classifier weights for auxiliary categories are masked out, leaving only the target class weights for use. Extensive experiments and ablation studies on three standard long-tail benchmarks demonstrate the effectiveness of our approach, notably outperforming strong baseline methods that use the same amount of data. The code will be made publicly available.

[Arxiv](https://arxiv.org/abs/2410.15980)