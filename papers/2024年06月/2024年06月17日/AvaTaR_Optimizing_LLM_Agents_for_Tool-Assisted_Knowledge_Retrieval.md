# AvaTaR：精调 LLM 代理，助力工具辅助知识检索

发布时间：2024年06月17日

`Agent

理由：这篇论文介绍了一种名为AvaTaR的创新自动化框架，旨在优化大型语言模型代理（LLM），使其能更有效地利用外部工具和知识。这种框架通过设计一个比较器模块来提供深入且全面的提示，从而在特定任务或领域中提升LLM代理的表现。这表明论文主要关注的是如何通过自动化技术来增强LLM代理的能力，属于Agent的范畴。` `多模态检索` `自动化优化`

> AvaTaR: Optimizing LLM Agents for Tool-Assisted Knowledge Retrieval

# 摘要

> 大型语言模型代理（LLM）已证明能有效利用外部工具和知识，提升准确性并减少错误。但开发此类提示技术却是一项既需直觉又耗时的任务。为此，我们推出了AvaTaR，一种创新的自动化框架，旨在优化LLM代理，使其能更有效地运用外部工具，进而在特定任务或领域中提升表现。在优化过程中，我们设计了一个比较器模块，通过分析训练数据中的正负样本，向LLM代理提供深入且全面的提示。我们在四个包含文本、视觉和关系信息的复杂多模态检索数据集上验证了AvaTaR的效果。结果显示，AvaTaR在所有四个挑战性任务中均超越了现有技术，并在处理新案例时展现出卓越的泛化能力，平均在Hit@1指标上提升了14%。相关代码和数据集已公开于https://github.com/zou-group/avatar。

> Large language model (LLM) agents have demonstrated impressive capability in utilizing external tools and knowledge to boost accuracy and reduce hallucinations. However, developing the prompting techniques that make LLM agents able to effectively use external tools and knowledge is a heuristic and laborious task. Here, we introduce AvaTaR, a novel and automatic framework that optimizes an LLM agent to effectively use the provided tools and improve its performance on a given task/domain. During optimization, we design a comparator module to iteratively provide insightful and holistic prompts to the LLM agent via reasoning between positive and negative examples sampled from training data. We demonstrate AvaTaR on four complex multimodal retrieval datasets featuring textual, visual, and relational information. We find AvaTaR consistently outperforms state-of-the-art approaches across all four challenging tasks and exhibits strong generalization ability when applied to novel cases, achieving an average relative improvement of 14% on the Hit@1 metric. Code and dataset are available at https://github.com/zou-group/avatar.

[Arxiv](https://arxiv.org/abs/2406.11200)