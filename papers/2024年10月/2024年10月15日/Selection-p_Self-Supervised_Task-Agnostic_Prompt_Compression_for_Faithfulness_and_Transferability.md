# Selection-p: 自监督任务无关提示压缩，旨在提升忠实度和可迁移性

发布时间：2024年10月15日

`LLM理论` `机器学习`

> Selection-p: Self-Supervised Task-Agnostic Prompt Compression for Faithfulness and Transferability

# 摘要

> LLM 在利用 in-context learning 时，展现了在 NLP 任务中的强大能力。为了降低 in-context learning 的计算和成本负担，研究者提出了多种 prompt 压缩方法。然而，这些方法因模型特定压缩或依赖外部数据（如 GPT-4）而面临可转移性问题。本文探讨了 LLM 开发统一压缩方法的能力，通过自监督预训练技术离散化非信息性 tokens。提出的 Selection-p 在持续预训练中引入少量参数，为每个 token 生成保留或丢弃的概率。实验显示，Selection-p 在多项分类任务中达到最先进水平，压缩率高达 10 倍，性能仅下降 0.8%。此外，它在模型间的可转移性优于以往方法。我们还分析了 Selection-p 如何在长上下文中保持 in-context learning 的性能。

> Large Language Models (LLMs) have demonstrated impressive capabilities in a wide range of natural language processing tasks when leveraging in-context learning. To mitigate the additional computational and financial costs associated with in-context learning, several prompt compression methods have been proposed to compress the in-context learning prompts. Despite their success, these methods face challenges with transferability due to model-specific compression, or rely on external training data, such as GPT-4. In this paper, we investigate the ability of LLMs to develop a unified compression method that discretizes uninformative tokens, utilizing a self-supervised pre-training technique. By introducing a small number of parameters during the continual pre-training, the proposed Selection-p produces a probability for each input token, indicating whether to preserve or discard it. Experiments show Selection-p achieves state-of-the-art performance across numerous classification tasks, achieving compression rates of up to 10 times while experiencing only a marginal 0.8% decrease in performance. Moreover, it exhibits superior transferability to different models compared to prior work. Additionally, we further analyze how Selection-p helps maintain performance on in-context learning with long contexts.

[Arxiv](https://arxiv.org/abs/2410.11786)