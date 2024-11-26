# VersaTune：高效地微调多能力大型语言模型

发布时间：2024年11月24日

`LLM应用` `多领域`

> VersaTune: Harnessing Vertical Domain Insights for Multi-Ability LLM Supervised Fine-Tuning

# 摘要

> 大型语言模型（LLMs）凭借其涌现特性，在跨领域处理多项任务时展现出非凡的能力，且这一能力在监督微调（SFT）阶段得到进一步提升。然而，尽管潜力巨大，现有工作主要聚焦于微调期间的特定领域增强，其面临的挑战在于会对其他领域的知识产生灾难性遗忘。本研究推出了 VersaTune，这一全新的数据组合框架旨在微调阶段提升 LLMs 的整体多能力表现。我们把知识划分成不同领域，涵盖法律、医学、金融、科学、代码等。我们先是检测基础模型中特定领域知识的分布情况，接着构建与模型现有知识分布相符的训练数据。在微调过程中，依据不同领域的可学习潜力和遗忘程度动态调整其权重。实验结果显示，VersaTune 在多领域性能上实现了显著提升，综合多领域任务的表现提高了 35.21%。另外，在需要针对特定领域优化时，VersaTune 能将其他领域的性能下降幅度减少 38.77%，且不影响目标领域的训练成效。

> Large Language Models (LLMs) exhibit remarkable capabilities in handling multiple tasks across domains due to their emergent properties. These capabilities are further augmented during the Supervised Fine-Tuning (SFT) phase. Despite their potential, existing work mainly focuses on domain-specific enhancements during fine-tuning, the challenge of which lies in catastrophic forgetting of knowledge across other domains. In this study, we introduce VersaTune, a novel data composition framework designed for enhancing LLMs' overall multi-ability performances during fine-tuning. We categorize knowledge into distinct domains including law, medicine, finance, science, code. We begin with detecting the distribution of domain-specific knowledge within the base model, followed by the composition of training data that aligns with the model's existing knowledge distribution. During the fine-tuning process, weights of different domains are dynamically adjusted based on their learnable potential and forgetting degree. Experimental results demonstrate that VersaTune achieves significant improvements in multi-domain performance, with a 35.21% enhancement in comprehensive multi-domain tasks. Additionally, in scenarios where specific domain optimization is required, VersaTune reduces the degradation of performance in other domains by 38.77%, without compromising the target domain's training efficacy.

[Arxiv](https://arxiv.org/abs/2411.11266)