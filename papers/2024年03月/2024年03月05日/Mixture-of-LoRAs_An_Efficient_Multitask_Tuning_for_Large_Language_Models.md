# [Mixture-of-LoRAs 是一项创新技术，专为大型语言模型设计的高效多任务调优方案。](https://arxiv.org/abs/2403.03432)

发布时间：2024年03月05日

`LLM应用`

> Mixture-of-LoRAs: An Efficient Multitask Tuning for Large Language Models

> 指令调优有望激活并提升LLMs的特殊功能，但关键在于找到合适的数据平衡点，避免灾难性遗忘及任务间相互干扰的问题。为了应对这些挑战并增强训练弹性，我们创新地提出了MoA（Mixture-of-LoRAs）结构，这是一种针对LLMs多任务学习而设计的新颖高效参数调优方法。研究初期，我们利用各自对应的监督文本数据单独训练了多个专业领域的LoRA模块，这些模块的设计原理借鉴了MoE（混合专家）模式。接下来，通过明确的路由策略整合多个LoRA模块，并引入领域标签以支持多任务学习，有效防止不同任务间的相互影响，进而显著提升每个独立任务的表现力。更值得一提的是，每个LoRA模型都能灵活迭代适应新的领域，实现快速的专业领域定制化。多元任务实验证明了这种方法的强大稳定性能，有望大力推动领域特定LLMs的大范围应用。

> Instruction Tuning has the potential to stimulate or enhance specific capabilities of large language models (LLMs). However, achieving the right balance of data is crucial to prevent catastrophic forgetting and interference between tasks. To address these limitations and enhance training flexibility, we propose the Mixture-of-LoRAs (MoA) architecture which is a novel and parameter-efficient tuning method designed for multi-task learning with LLMs. In this paper, we start by individually training multiple domain-specific LoRA modules using corresponding supervised corpus data. These LoRA modules can be aligned with the expert design principles observed in Mixture-of-Experts (MoE). Subsequently, we combine the multiple LoRAs using an explicit routing strategy and introduce domain labels to facilitate multi-task learning, which help prevent interference between tasks and ultimately enhances the performance of each individual task. Furthermore, each LoRA model can be iteratively adapted to a new domain, allowing for quick domain-specific adaptation. Experiments on diverse tasks demonstrate superior and robust performance, which can further promote the wide application of domain-specific LLMs.

[Arxiv](https://arxiv.org/abs/2403.03432)