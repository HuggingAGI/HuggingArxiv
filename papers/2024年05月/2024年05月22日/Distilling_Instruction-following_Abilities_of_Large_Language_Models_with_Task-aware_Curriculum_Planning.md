# 利用任务感知的课程规划，精炼大型语言模型的指令遵循能力

发布时间：2024年05月22日

`Agent

理由：这篇论文主要介绍了一个名为TAPIR的框架，该框架通过多轮蒸馏实现任务分布平衡和难度动态调整，以提升学生模型的能力。这个框架涉及到自主选择和调整任务以适应学生模型的能力，这涉及到代理（Agent）的行为，即自主地执行任务和决策以达到特定目标。因此，这篇论文更符合Agent分类，因为它描述了一个系统如何自主地优化和调整以提高性能，而不是直接关于LLM的应用或理论。` `机器学习`

> Distilling Instruction-following Abilities of Large Language Models with Task-aware Curriculum Planning

# 摘要

> 指令调优让大型语言模型更好地响应开放领域指令和人类偏好。尽管已有研究尝试从如ChatGPT这样的强大模型中自主提取指令，但往往忽略了任务分布和指令难度的差异，这可能导致小型模型知识能力不均和泛化能力弱。为此，我们提出了TAPIR框架，它通过多轮蒸馏实现任务分布平衡和难度动态调整，利用oracle LLM挑选适合学生模型的挑战性指令，并通过课程规划逐步提升难度，系统增强学生模型的能力。在AlpacaEval 2.0和MT-Bench等基准测试中，我们的方法使学生模型在较少训练数据下，尤其在逻辑推理和代码生成等复杂任务中，超越了大型指令调优模型和蒸馏基线。

> The process of instruction tuning aligns pre-trained large language models (LLMs) with open-domain instructions and human-preferred responses. While several studies have explored autonomous approaches to distilling and annotating instructions from more powerful proprietary LLMs, such as ChatGPT, they often neglect the impact of task distributions and the varying difficulty of instructions of the training sets. This oversight can lead to imbalanced knowledge capabilities and poor generalization powers of small student LLMs. To address this challenge, we introduce Task-Aware Curriculum Planning for Instruction Refinement (TAPIR), a multi-round distillation framework with balanced task distributions and dynamic difficulty adjustment. This approach utilizes an oracle LLM to select instructions that are difficult for a student LLM to follow and distill instructions with balanced task distributions. By incorporating curriculum planning, our approach systematically escalates the difficulty levels, progressively enhancing the student LLM's capabilities. We rigorously evaluate TAPIR using two widely recognized benchmarks, including AlpacaEval 2.0 and MT-Bench. The empirical results demonstrate that the student LLMs, trained with our method and less training data, outperform larger instruction-tuned models and strong distillation baselines. The improvement is particularly notable in complex tasks, such as logical reasoning and code generation.

[Arxiv](https://arxiv.org/abs/2405.13448)