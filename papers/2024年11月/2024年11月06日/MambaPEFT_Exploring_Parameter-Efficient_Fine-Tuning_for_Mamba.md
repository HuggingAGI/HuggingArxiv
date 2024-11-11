# MambaPEFT：探索用于 Mamba 的参数高效微调

发布时间：2024年11月06日

`其他` `模型微调`

> MambaPEFT: Exploring Parameter-Efficient Fine-Tuning for Mamba

# 摘要

> 基于 Transformer 的模型的生态系统已经通过使用大量数据构建大型模型而建立。参数高效微调（PEFT）是一种关键技术，用于以最小的成本将这些模型部署到下游任务中，同时实现有效的性能。最近，基于状态空间模型（SSM）的 Mamba 模型作为 Transformer 的潜在替代品引起了关注。虽然已经提出了许多基于大规模 Mamba 的模型，但如何有效地将预训练的基于 Mamba 的模型适应下游任务仍未得到探索。在本文中，我们对 Mamba 的 PEFT 方法进行了探索性分析。我们研究了将现有的用于 Transformer 的 PEFT 方法应用于 Mamba 时的有效性。我们还对这些方法进行了修改，以更好地与 Mamba 架构对齐。此外，我们提出了利用 Mamba 独特结构的新的特定于 Mamba 的 PEFT 方法。我们的实验表明，PEFT 对 Mamba 比对 Transformer 更有效。最后，我们展示了如何有效地组合多种 PEFT 方法，并提供了一个优于以前工作的框架。为确保可重复性，我们将在发表后发布代码。

> An ecosystem of Transformer-based models has been established by building large models with extensive data. Parameter-efficient fine-tuning (PEFT) is a crucial technology for deploying these models to downstream tasks with minimal cost while achieving effective performance. Recently, Mamba, a State Space Model (SSM)-based model, has attracted attention as a potential alternative to Transformers. While many large-scale Mamba-based models have been proposed, efficiently adapting pre-trained Mamba-based models to downstream tasks remains unexplored. In this paper, we conduct an exploratory analysis of PEFT methods for Mamba. We investigate the effectiveness of existing PEFT methods for Transformers when applied to Mamba. We also modify these methods to better align with the Mamba architecture. Additionally, we propose new Mamba-specific PEFT methods that leverage the distinctive structure of Mamba. Our experiments indicate that PEFT performs more effectively for Mamba than Transformers. Lastly, we demonstrate how to effectively combine multiple PEFT methods and provide a framework that outperforms previous works. To ensure reproducibility, we will release the code after publication.

[Arxiv](https://arxiv.org/abs/2411.03855)