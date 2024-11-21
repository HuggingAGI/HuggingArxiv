# 通过视觉线索增强和双重低秩适应来进行高效的视觉指令微调

发布时间：2024年11月19日

`LLM应用` `多模态` `语言模型`

> Visual Cue Enhancement and Dual Low-Rank Adaptation for Efficient Visual Instruction Fine-Tuning

# 摘要

> 微调多模态大型语言模型（MLLMs）面临诸多严峻挑战，比如依赖高级视觉特征致使细粒度细节理解受限，还有任务复杂引发的数据冲突。为应对这些难题，我们提出了一个高效的微调框架，其中包含两种新颖的方法：视觉线索增强（VCE）和双低秩适应（Dual-LoRA）。VCE 通过融合多层次视觉线索来强化视觉投影仪，提升模型捕捉细粒度视觉特征的能力。Dual-LoRA 为指令调整引入双低秩结构，将学习过程解耦为技能和任务空间，从而能够对各类任务进行精准控制和高效适应。我们的方法简化了操作，增强了视觉理解，还提高了适应性。在下游任务和通用基准上的实验均表明了我们所提方法的有效性。

> Fine-tuning multimodal large language models (MLLMs) presents significant challenges, including a reliance on high-level visual features that limits fine-grained detail comprehension, and data conflicts that arise from task complexity. To address these issues, we propose an efficient fine-tuning framework with two novel approaches: Vision Cue Enhancement (VCE) and Dual Low-Rank Adaptation (Dual-LoRA). VCE enhances the vision projector by integrating multi-level visual cues, improving the model's ability to capture fine-grained visual features. Dual-LoRA introduces a dual low-rank structure for instruction tuning, decoupling learning into skill and task spaces to enable precise control and efficient adaptation across diverse tasks. Our method simplifies implementation, enhances visual comprehension, and improves adaptability. Experiments on both downstream tasks and general benchmarks demonstrate the effectiveness of our proposed approach.

[Arxiv](https://arxiv.org/abs/2411.12787)