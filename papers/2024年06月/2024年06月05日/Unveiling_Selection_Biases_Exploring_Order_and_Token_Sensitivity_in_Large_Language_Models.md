# 揭秘选择偏差：探究大型语言模型对顺序与令牌的敏感性

发布时间：2024年06月05日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）中的选择偏差问题，分析了选项顺序和令牌使用对模型决策的影响，并提出了一系列缓解策略。这些内容更偏向于理论分析和模型改进，而不是具体的应用案例或Agent的设计，也不涉及RAG（Retrieval-Augmented Generation）框架。因此，将其归类为LLM理论是合适的。` `机器学习`

> Unveiling Selection Biases: Exploring Order and Token Sensitivity in Large Language Models

# 摘要

> 本文探讨了大型语言模型（LLMs）中的选择偏差问题，特别是模型在有序序列中挑选最佳选项时所面临的挑战。我们分析了选项顺序和令牌使用对模型决策的显著影响，并通过多模型和任务的实证研究量化了这些偏差。为了提升模型性能，我们提出了一系列缓解策略。我们的研究成果主要包括：1）精确评估选项顺序和令牌对LLMs的影响；2）制定策略以降低对令牌和顺序的敏感性，增强模型的稳健性；3）深入分析了不同模型和任务中的敏感性，为开发更稳定、可靠的LLM应用提供了指导。

> In this paper, we investigate the phenomena of "selection biases" in Large Language Models (LLMs), focusing on problems where models are tasked with choosing the optimal option from an ordered sequence. We delve into biases related to option order and token usage, which significantly impact LLMs' decision-making processes. We also quantify the impact of these biases through an extensive empirical analysis across multiple models and tasks. Furthermore, we propose mitigation strategies to enhance model performance. Our key contributions are threefold: 1) Precisely quantifying the influence of option order and token on LLMs, 2) Developing strategies to mitigate the impact of token and order sensitivity to enhance robustness, and 3) Offering a detailed analysis of sensitivity across models and tasks, which informs the creation of more stable and reliable LLM applications for selection problems.

![揭秘选择偏差：探究大型语言模型对顺序与令牌的敏感性](../../../paper_images/2406.03009/x1.png)

![揭秘选择偏差：探究大型语言模型对顺序与令牌的敏感性](../../../paper_images/2406.03009/x2.png)

![揭秘选择偏差：探究大型语言模型对顺序与令牌的敏感性](../../../paper_images/2406.03009/x3.png)

![揭秘选择偏差：探究大型语言模型对顺序与令牌的敏感性](../../../paper_images/2406.03009/x4.png)

![揭秘选择偏差：探究大型语言模型对顺序与令牌的敏感性](../../../paper_images/2406.03009/x5.png)

[Arxiv](https://arxiv.org/abs/2406.03009)