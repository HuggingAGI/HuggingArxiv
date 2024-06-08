# 语言化表示：探索解释性的信息理论框架

发布时间：2024年06月04日

`LLM理论

这篇论文主要探讨了大型神经模型的可解释性问题，特别是如何理解模型从句子到表示的学习过程，并提出了一种新的信息理论度量来预测模型的泛化能力。这些研究内容涉及模型的内部机制和泛化性能，属于对大型语言模型（LLM）的理论研究。因此，将其归类为LLM理论。` `机器学习`

> Representations as Language: An Information-Theoretic Framework for Interpretability

# 摘要

> 大型神经模型在众多语言任务中表现出色，但它们大多仍是难以解读的黑盒子，生成的输入向量难以理解。这限制了我们洞察其学习内容和时机，以及哪些表示在分布外泛化良好的能力。为此，我们提出了一种新的可解释性方法，将模型从句子到表示的学习视为一种独特的语言。我们引入的信息理论度量，快速且基于语言学，能预测模型的泛化能力。这些度量揭示了变压器训练的两个阶段：首先是减少任务损失的分布内学习，随后是表示对噪声变得鲁棒的阶段。泛化性能在第二阶段提升，揭示了泛化与对噪声的鲁棒性之间的联系。此外，我们发现模型越大，其表示空间压缩得越彻底。

> Large scale neural models show impressive performance across a wide array of linguistic tasks. Despite this they remain, largely, black-boxes - inducing vector-representations of their input that prove difficult to interpret. This limits our ability to understand what they learn, and when the learn it, or describe what kinds of representations generalise well out of distribution. To address this we introduce a novel approach to interpretability that looks at the mapping a model learns from sentences to representations as a kind of language in its own right. In doing so we introduce a set of information-theoretic measures that quantify how structured a model's representations are with respect to its input, and when during training that structure arises. Our measures are fast to compute, grounded in linguistic theory, and can predict which models will generalise best based on their representations. We use these measures to describe two distinct phases of training a transformer: an initial phase of in-distribution learning which reduces task loss, then a second stage where representations becoming robust to noise. Generalisation performance begins to increase during this second phase, drawing a link between generalisation and robustness to noise. Finally we look at how model size affects the structure of the representational space, showing that larger models ultimately compress their representations more than their smaller counterparts.

![语言化表示：探索解释性的信息理论框架](../../../paper_images/2406.02449/cover_fig.png)

![语言化表示：探索解释性的信息理论框架](../../../paper_images/2406.02449/information.png)

![语言化表示：探索解释性的信息理论框架](../../../paper_images/2406.02449/pos_regularity.png)

![语言化表示：探索解释性的信息理论框架](../../../paper_images/2406.02449/token_regularity.png)

![语言化表示：探索解释性的信息理论框架](../../../paper_images/2406.02449/bigram_regularity.png)

![语言化表示：探索解释性的信息理论框架](../../../paper_images/2406.02449/token_disentanglement.png)

![语言化表示：探索解释性的信息理论框架](../../../paper_images/2406.02449/bigram_disentanglement.png)

![语言化表示：探索解释性的信息理论框架](../../../paper_images/2406.02449/loss_vs_measures.png)

[Arxiv](https://arxiv.org/abs/2406.02449)