# 视觉与语言的引导，实现动态多模态评估，灵活应对复杂性挑战。

发布时间：2024年10月11日

`LLM应用` `计算机视觉` `人工智能`

> Dynamic Multimodal Evaluation with Flexible Complexity by Vision-Language Bootstrapping

# 摘要

> 大型视觉-语言模型 (LVLMs) 在多模态任务中表现出色，但在静态基准上存在数据污染和复杂性固定的问题。为此，我们提出了视觉-语言引导 (VLB) 这一动态评估协议，通过多模态引导模块生成新样本，确保与原始样本一致，并提供多样化的复杂性评估。实验证明，VLB 有效减少数据污染，揭示了 LVLMs 的性能瓶颈。

> Large Vision-Language Models (LVLMs) have demonstrated remarkable capabilities across multimodal tasks such as visual perception and reasoning, leading to good performance on various multimodal evaluation benchmarks. However, these benchmarks keep a static nature and overlap with the pre-training data, resulting in fixed complexity constraints and data contamination issues. This raises the concern regarding the validity of the evaluation. To address these two challenges, we introduce a dynamic multimodal evaluation protocol called Vision-Language Bootstrapping (VLB). VLB provides a robust and comprehensive assessment for LVLMs with reduced data contamination and flexible complexity. To this end, VLB dynamically generates new visual question-answering samples through a multimodal bootstrapping module that modifies both images and language, while ensuring that newly generated samples remain consistent with the original ones by a judge module. By composing various bootstrapping strategies, VLB offers dynamic variants of existing benchmarks with diverse complexities, enabling the evaluation to co-evolve with the ever-evolving capabilities of LVLMs. Extensive experimental results across multiple benchmarks, including SEEDBench, MMBench, and MME, show that VLB significantly reduces data contamination and exposes performance limitations of LVLMs.

[Arxiv](https://arxiv.org/abs/2410.08695)