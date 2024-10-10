# ModalPrompt：双模态引导提示助力大型多模态模型的持续学习

发布时间：2024年10月08日

`LLM应用` `人工智能` `计算机视觉`

> ModalPrompt:Dual-Modality Guided Prompt for Continual Learning of Large Multimodal Models

# 摘要

> 大型多模态模型 (LMMs) 通过联合学习混合数据集，展现出卓越的多任务处理能力。然而，在动态世界中，新任务不断涌现，持续微调 LMMs 往往导致性能下降。为应对灾难性遗忘，现有方法如数据回放或模型扩展，虽有其局限性。本文提出一种新颖的双模态引导提示学习框架 (ModalPrompt)，专为多模态持续学习设计，旨在有效学习新任务的同时减轻对先前知识的遗忘。具体而言，我们为每个任务学习原型提示，并基于图像-文本监督进行高效提示选择和知识转移的提示融合。实验证明，ModalPrompt 在 LMMs 持续学习基准测试中性能提升 20%，推理速度提升 1.42 倍，而训练成本并未随任务数量增加而线性增长。代码将公开发布。

> Large Multimodal Models (LMMs) exhibit remarkable multi-tasking ability by learning mixed datasets jointly. However, novel tasks would be encountered sequentially in dynamic world, and continually fine-tuning LMMs often leads to performance degrades. To handle the challenges of catastrophic forgetting, existing methods leverage data replay or model expansion, both of which are not specially developed for LMMs and have their inherent limitations. In this paper, we propose a novel dual-modality guided prompt learning framework (ModalPrompt) tailored for multimodal continual learning to effectively learn new tasks while alleviating forgetting of previous knowledge. Concretely, we learn prototype prompts for each task and exploit efficient prompt selection for task identifiers and prompt fusion for knowledge transfer based on image-text supervision. Extensive experiments demonstrate the superiority of our approach, e.g., ModalPrompt achieves +20% performance gain on LMMs continual learning benchmarks with $\times$ 1.42 inference speed refraining from growing training cost in proportion to the number of tasks. The code will be made publically available.

[Arxiv](https://arxiv.org/abs/2410.05849)