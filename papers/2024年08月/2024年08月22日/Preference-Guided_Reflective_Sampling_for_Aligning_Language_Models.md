# 偏好引导反射采样技术，旨在优化语言模型的对齐效果。

发布时间：2024年08月22日

`LLM应用` `人工智能`

> Preference-Guided Reflective Sampling for Aligning Language Models

# 摘要

> 通过人类反馈的强化学习 (RLHF)，大型语言模型 (LLM) 能够与人类偏好对齐。在此过程中，有效的数据采样至关重要，它直接影响模型训练的效率，确保模型从高质量样本中学习。为此，我们提出了一种名为偏好引导反射采样 (PRS) 的新方法，该方法将响应生成视为一个优化过程，旨在满足用户以自然语言明确表达的偏好。PRS 利用基于树的生成框架，通过偏好引导生成方向，并借助自适应自我改进机制，更有效地探索采样空间。PRS 不仅能够使 LLM 适应多样化的用户偏好，还在指令遵循和关键词聚焦文档摘要等任务中展现出优越性能。研究结果显示，PRS 生成的训练数据在不同 LLM 策略下均能获得比传统方法更高的奖励，且在 RL 后的训练阶段同样表现优异。

> Large language models (LLMs) are aligned with human preferences by reinforcement learning from human feedback (RLHF). Effective data sampling is crucial for RLHF, as it determines the efficiency of model training, ensuring that models learn from the informative samples. To achieve better data generation, we propose a new sampling method called Preference-Guided Reflective Sampling (PRS). PRS frames the response generation as an optimization process to the explicitly specified user preference described in natural language. It employs a tree-based generation framework to enable an efficient sampling process, which guides the direction of generation through preference and better explores the sampling space with adaptive self-refinement. Notably, PRS can align LLMs to diverse preferences. We study preference-controlled text generation for instruction following and keyword-focused document summarization. Our findings indicate that PRS, across different LLM policies, generates training data with much higher rewards than strong baselines. PRS also excels in post-RL training.

[Arxiv](https://arxiv.org/abs/2408.12163)