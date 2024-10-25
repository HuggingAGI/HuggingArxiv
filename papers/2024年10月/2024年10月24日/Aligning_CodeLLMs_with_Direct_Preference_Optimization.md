# 将 CodeLLMs 与直接偏好优化对齐

发布时间：2024年10月24日

`LLM应用` `模型训练`

> Aligning CodeLLMs with Direct Preference Optimization

# 摘要

> 去年见证了大型语言模型（LLMs）在不同领域的快速进步。其中，CodeLLMs 已经引起了特别的关注，因为它们不仅能够协助完成各种编程任务，而且还代表了 LLMs 的决策和逻辑推理能力。然而，当前的 CodeLLMs 主要集中在预训练和有监督的微调场景，对于后训练 LLMs 重要的对齐阶段研究不足。这项工作首先指出，常用的 PPO 算法对于 CodeLLM 的对齐可能不是最优的，因为所涉及的奖励规则通常是粗粒度的并且可能存在缺陷。然后我们主张使用 DPO 算法来解决这个问题。仅基于偏好数据对，DPO 可以自动使模型对数据进行排序，产生比人工干预更强大的细粒度奖励模式。我们还为在 CodeLLMs 上收集 DPO 的偏好对贡献了一个管道。研究表明，我们的方法显著提高了现有 CodeLLMs 在诸如 MBPP 和 HumanEval 等基准上的性能。

> The last year has witnessed the rapid progress of large language models (LLMs) across diverse domains. Among them, CodeLLMs have garnered particular attention because they can not only assist in completing various programming tasks but also represent the decision-making and logical reasoning capabilities of LLMs. However, current CodeLLMs mainly focus on pre-training and supervised fine-tuning scenarios, leaving the alignment stage, which is important for post-training LLMs, under-explored. This work first identifies that the commonly used PPO algorithm may be suboptimal for the alignment of CodeLLM because the involved reward rules are routinely coarse-grained and potentially flawed. We then advocate addressing this using the DPO algorithm. Based on only preference data pairs, DPO can render the model rank data automatically, giving rise to a fine-grained rewarding pattern more robust than human intervention. We also contribute a pipeline for collecting preference pairs for DPO on CodeLLMs. Studies show that our method significantly improves the performance of existing CodeLLMs on benchmarks such as MBPP and HumanEval.

[Arxiv](https://arxiv.org/abs/2410.18585)