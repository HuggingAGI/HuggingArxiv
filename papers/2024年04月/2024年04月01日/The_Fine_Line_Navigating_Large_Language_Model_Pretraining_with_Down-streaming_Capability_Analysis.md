# 《探寻平衡：借助下游能力分析来引导大型语言模型的预训练》

发布时间：2024年04月01日

`LLM理论` `预训练` `大规模语言模型`

> The Fine Line: Navigating Large Language Model Pretraining with Down-streaming Capability Analysis

# 摘要

> 发现能预示最终模型表现的早期指标对于大规模预训练至关重要。目前遵循的扩展法则揭示了预训练损失与训练运算之间的幂律关系，这成为衡量大型语言模型训练状况的关键指标。然而，这一原则过于侧重模型对训练数据的压缩能力，与提升下游任务性能的能力并不一致。尽管有些研究尝试将扩展法则应用于更复杂的指标（例如超参数），但在分析预训练过程中各种能力动态变化方面仍显不足。为了克服这些局限，本文对比了不同预训练阶段的模型能力。分析结果表明，不同规模的模型在训练动态上存在共性，参数量可达670亿。我们不仅重现了Amber和OpenLLaMA模型，并公开了它们的中间检查点，为研究社区提供了宝贵资源，也便于开源研究者验证和探索LLM的预训练。此外，我们还提供了实证总结，涵盖不同模型和能力的性能比较，以及各训练阶段关键指标的指导。基于这些成果，我们提出了一种更为友好的评估优化状态的策略，旨在为建立稳定的预训练流程提供参考。

> Uncovering early-stage metrics that reflect final model performance is one core principle for large-scale pretraining. The existing scaling law demonstrates the power-law correlation between pretraining loss and training flops, which serves as an important indicator of the current training state for large language models. However, this principle only focuses on the model's compression properties on the training data, resulting in an inconsistency with the ability improvements on the downstream tasks. Some follow-up works attempted to extend the scaling-law to more complex metrics (such as hyperparameters), but still lacked a comprehensive analysis of the dynamic differences among various capabilities during pretraining. To address the aforementioned limitations, this paper undertakes a comprehensive comparison of model capabilities at various pretraining intermediate checkpoints. Through this analysis, we confirm that specific downstream metrics exhibit similar training dynamics across models of different sizes, up to 67 billion parameters. In addition to our core findings, we've reproduced Amber and OpenLLaMA, releasing their intermediate checkpoints. This initiative offers valuable resources to the research community and facilitates the verification and exploration of LLM pretraining by open-source researchers. Besides, we provide empirical summaries, including performance comparisons of different models and capabilities, and tuition of key metrics for different training phases. Based on these findings, we provide a more user-friendly strategy for evaluating the optimization state, offering guidance for establishing a stable pretraining process.

[Arxiv](https://arxiv.org/abs/2404.01204)