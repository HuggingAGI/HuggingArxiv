# AtomThink：一个用于多模态数学推理的慢思考框架

发布时间：2024年11月18日

`LLM应用` `多模态`

> AtomThink: A Slow Thinking Framework for Multimodal Mathematical Reasoning

# 摘要

> 在本文中，我们把“慢思考”的能力融入多模态大型语言模型（MLLMs），以此应对多模态数学推理这一颇具挑战的任务。和那些依靠直接或快速思考的现有方法不同，我们的核心思路是以循序渐进的方式构建由原子动作构成的长思维链（CoT），引领 MLLMs 展开复杂推理。为此，我们设计了全新的 AtomThink 框架，它包含三个关键模块：（i）一个 CoT 标注引擎，能自动生成高质量的 CoT 标注，以弥补高质量视觉数学数据的缺失；（ii）一种原子步骤微调策略，对 MLLM 和策略奖励模型（PRM）进行联合优化，以实现逐步推理；（iii）四种不同的搜索策略，可与 PRM 配合完成推理。另外，我们还提出了 AtomMATH，这是一个大规模的长 CoTs 多模态数据集，以及用于数学任务的原子能力评估指标。大量实验结果显示，所提出的 AtomThink 大幅提升了基线 MLLMs 的性能，在 MathVista 上实现了约 50％的相对准确率增长，在 MathVerse 上达到了 120％的增长。为推动多模态慢思考模型的进步，我们会在 https://github.com/Quinn777/AtomThink 上公开我们的代码和数据集。

> In this paper, we address the challenging task of multimodal mathematical reasoning by incorporating the ability of ``slow thinking" into multimodal large language models (MLLMs). Contrary to existing methods that rely on direct or fast thinking, our key idea is to construct long chains of thought (CoT) consisting of atomic actions in a step-by-step manner, guiding MLLMs to perform complex reasoning. To this end, we design a novel AtomThink framework composed of three key modules: (i) a CoT annotation engine that automatically generates high-quality CoT annotations to address the lack of high-quality visual mathematical data; (ii) an atomic step fine-tuning strategy that jointly optimizes an MLLM and a policy reward model (PRM) for step-wise reasoning; and (iii) four different search strategies that can be applied with the PRM to complete reasoning. Additionally, we propose AtomMATH, a large-scale multimodal dataset of long CoTs, and an atomic capability evaluation metric for mathematical tasks. Extensive experimental results show that the proposed AtomThink significantly improves the performance of baseline MLLMs, achieving approximately 50\% relative accuracy gains on MathVista and 120\% on MathVerse. To support the advancement of multimodal slow-thinking models, we will make our code and dataset publicly available on https://github.com/Quinn777/AtomThink.

[Arxiv](https://arxiv.org/abs/2411.11930)