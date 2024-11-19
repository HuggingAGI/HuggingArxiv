# 借助混合偏好优化来提升多模态大型语言模型的推理能力

发布时间：2024年11月15日

`LLM应用` `多模态` `语言模型`

> Enhancing the Reasoning Ability of Multimodal Large Language Models via Mixed Preference Optimization

# 摘要

> 现有的开源多模态大型语言模型（MLLMs）通常要经历预训练和有监督微调这样的训练流程。但这些模型存在分布偏移的情况，这严重限制了它们的多模态推理能力，尤其是在思维链（CoT）性能方面。为解决此问题，我们引入了偏好优化（PO）流程来强化 MLLMs 的多模态推理能力。具体来说，（1）在数据方面，我们设计了自动化的偏好数据构建管道，创建出了高质量、大规模的多模态推理偏好数据集 MMPR。（2）在模型方面，我们探索将 PO 与 MLLMs 相融合，开发出一种简单却有效的方法，叫做混合偏好优化（MPO），它提升了多模态 CoT 性能。我们的方法在多个基准测试中都有出色表现，特别是在多模态推理任务里。特别要指出的是，我们的模型 InternVL2-8B-MPO 在 MathVista 上的准确率达 67.0，比 InternVL2-8B 高 8.7 个点，且性能可与大 10 倍的 InternVL2-76B 媲美。我们期望此研究能推动 MLLMs 取得更多进步。代码、数据和模型将会公开。

> Existing open-source multimodal large language models (MLLMs) generally follow a training process involving pre-training and supervised fine-tuning. However, these models suffer from distribution shifts, which limit their multimodal reasoning, particularly in the Chain-of-Thought (CoT) performance. To address this, we introduce a preference optimization (PO) process to enhance the multimodal reasoning capabilities of MLLMs. Specifically, (1) on the data side, we design an automated preference data construction pipeline to create MMPR, a high-quality, large-scale multimodal reasoning preference dataset. and (2) on the model side, we explore integrating PO with MLLMs, developing a simple yet effective method, termed Mixed Preference Optimization (MPO), which boosts multimodal CoT performance. Our approach demonstrates improved performance across multiple benchmarks, particularly in multimodal reasoning tasks. Notably, our model, InternVL2-8B-MPO, achieves an accuracy of 67.0 on MathVista, outperforming InternVL2-8B by 8.7 points and achieving performance comparable to the 10x larger InternVL2-76B. We hope this study could inspire further advancements in MLLMs. Code, data, and model shall be publicly released.

[Arxiv](https://arxiv.org/abs/2411.10442)