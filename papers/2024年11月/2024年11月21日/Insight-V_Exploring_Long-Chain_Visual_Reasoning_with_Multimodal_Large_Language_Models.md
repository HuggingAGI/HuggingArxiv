# Insight-V：借助多模态大型语言模型探索长链视觉推理

发布时间：2024年11月21日

`Agent` `多模态` `视觉语言`

> Insight-V: Exploring Long-Chain Visual Reasoning with Multimodal Large Language Models

# 摘要

> 大型语言模型（LLMs）凭借更多的推理展现出更强的能力与可靠性，从思维链提示进阶到如 OpenAI o1 这般的产品级解决方案。尽管为提升 LLM 推理能力付出诸多努力，但在视觉语言任务中，高质量的长链推理数据以及优化的训练流程仍未得到充分挖掘。本文中，我们推出了 Insight-V，这是早期的一次尝试，旨在 1）为复杂的多模态任务可扩展性地生成长期且稳固的推理数据，2）构建一个有效的训练流程来增强多模态大型语言模型（MLLMs）的推理能力。具体来说，为在无需人工操作的情况下创建长期且结构化的推理数据，我们设计了一个两步式流程，包含采用渐进策略生成足够长且多样的推理路径，以及运用多粒度评估方法保障数据质量。我们发现，直接用这类长且复杂的推理数据监督 MLLMs 无法获得理想的推理能力。为解决此问题，我们设计了一个多智能体系统，由专注于进行长链推理的推理智能体和负责判断及总结推理结果的总结智能体构成。我们还进一步引入了迭代 DPO 算法，以增强推理智能体的生成稳定性和质量。基于热门的 LLaVA-NeXT 模型和我们更强大的基础 MLLM，我们在需要视觉推理的具有挑战性的多模态基准测试中实现了显著的性能提升。得益于我们的多智能体系统，Insight-V 在以感知为重点的多模态任务中也能够轻松保持或提高性能。

> Large Language Models (LLMs) demonstrate enhanced capabilities and reliability by reasoning more, evolving from Chain-of-Thought prompting to product-level solutions like OpenAI o1. Despite various efforts to improve LLM reasoning, high-quality long-chain reasoning data and optimized training pipelines still remain inadequately explored in vision-language tasks. In this paper, we present Insight-V, an early effort to 1) scalably produce long and robust reasoning data for complex multi-modal tasks, and 2) an effective training pipeline to enhance the reasoning capabilities of multi-modal large language models (MLLMs). Specifically, to create long and structured reasoning data without human labor, we design a two-step pipeline with a progressive strategy to generate sufficiently long and diverse reasoning paths and a multi-granularity assessment method to ensure data quality. We observe that directly supervising MLLMs with such long and complex reasoning data will not yield ideal reasoning ability. To tackle this problem, we design a multi-agent system consisting of a reasoning agent dedicated to performing long-chain reasoning and a summary agent trained to judge and summarize reasoning results. We further incorporate an iterative DPO algorithm to enhance the reasoning agent's generation stability and quality. Based on the popular LLaVA-NeXT model and our stronger base MLLM, we demonstrate significant performance gains across challenging multi-modal benchmarks requiring visual reasoning. Benefiting from our multi-agent system, Insight-V can also easily maintain or improve performance on perception-focused multi-modal tasks.

[Arxiv](https://arxiv.org/abs/2411.14432)