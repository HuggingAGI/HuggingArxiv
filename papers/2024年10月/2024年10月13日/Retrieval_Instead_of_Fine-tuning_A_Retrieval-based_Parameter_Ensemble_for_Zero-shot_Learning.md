# 用检索取代微调：探索基于检索的参数集成在零-shot 学习中的应用

发布时间：2024年10月13日

`RAG` `人工智能`

> Retrieval Instead of Fine-tuning: A Retrieval-based Parameter Ensemble for Zero-shot Learning

# 摘要

> 基础模型在深度学习中占据重要地位，低秩适应 (LoRA) 等技术为大型模型提供了高效的微调方法。同样，检索增强生成 (RAG) 利用向量化数据库，通过结合外部信息显著提升了模型性能。然而，这些方法通常需要大量训练或标注数据，限制了其在资源有限环境中的应用。为此，我们提出了基于检索的参数集成 (RPE)，通过创建 LoRA 的向量化数据库，实现高效的任务适应。RPE 无需大量训练和标注数据，特别适合零-shot 学习，并在医疗等隐私敏感领域表现出色。在医疗报告生成和图像分割等任务中，RPE 不仅高效，还在某些情况下超越了传统监督微调方法，展现了其在提升计算效率和保护隐私方面的巨大潜力。

> Foundation models have become a cornerstone in deep learning, with techniques like Low-Rank Adaptation (LoRA) offering efficient fine-tuning of large models. Similarly, methods such as Retrieval-Augmented Generation (RAG), which leverage vectorized databases, have further improved model performance by grounding outputs in external information. While these approaches have demonstrated notable success, they often require extensive training or labeled data, which can limit their adaptability in resource-constrained environments. To address these challenges, we introduce Retrieval-based Parameter Ensemble (RPE), a new method that creates a vectorized database of LoRAs, enabling efficient retrieval and application of model adaptations to new tasks. RPE minimizes the need for extensive training and eliminates the requirement for labeled data, making it particularly effective for zero-shot learning. Additionally, RPE is well-suited for privacy-sensitive domains like healthcare, as it modifies model parameters without accessing raw data. When applied to tasks such as medical report generation and image segmentation, RPE not only proved effective but also surpassed supervised fine-tuning methods in certain cases, highlighting its potential to enhance both computational efficiency and privacy in deep learning applications.

[Arxiv](https://arxiv.org/abs/2410.09908)