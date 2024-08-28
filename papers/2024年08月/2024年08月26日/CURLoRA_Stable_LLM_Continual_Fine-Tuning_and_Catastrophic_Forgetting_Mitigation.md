# CURLoRA：实现 LLM 稳定持续微调并缓解灾难性遗忘

发布时间：2024年08月26日

`LLM理论` `人工智能` `机器学习`

> CURLoRA: Stable LLM Continual Fine-Tuning and Catastrophic Forgetting Mitigation

# 摘要

> 本文提出 CURLoRA，一种利用低秩适应 (LoRA) 中 CUR 矩阵分解的 LLM 微调新方法。该方法有效解决了持续学习中的灾难性遗忘和参数数量过多的问题。通过独特的 CUR 分解改进，结合倒置概率选择和零初始化的 $U$ 矩阵微调，CURLoRA 在实验中展现出优于标准 LoRA 的性能，不仅稳定了模型表现，还大幅减少了可训练参数。研究结果表明，CURLoRA 在数据有限的情况下，仍能保持高准确性和低困惑度，为 LLM 微调提供了新的优化方向。

> This paper introduces CURLoRA, a novel approach to fine-tuning large language models (LLMs) that leverages CUR matrix decomposition in the context of Low-Rank Adaptation (LoRA). Our method addresses two critical challenges in LLM fine-tuning: mitigating catastrophic forgetting during continual learning and reducing the number of trainable parameters. We propose a unique modification to the CUR decomposition process, utilizing inverted probabilities for column and row selection which acts as an implicit regularization, and initializing the $U$ matrix as a zero matrix, and only fine-tuning it. We demonstrate through experiments on multiple datasets that CURLoRA outperforms standard LoRA in mitigating catastrophic forgetting. It maintains model stability and performance across tasks while significantly reducing the number of trainable parameters. Our results show that CURLoRA achieves very good and stable task accuracy while maintaining base model's perplexity scores fixed compared to LoRA upon continual fine-tuning, particularly in scenarios with limited data.

[Arxiv](https://arxiv.org/abs/2408.14572)