# 强化学习用于让大型语言模型代理与交互式环境相适配：对提示过拟合进行量化与缓解

发布时间：2024年10月29日

`LLM应用` `语言模型`

> Reinforcement Learning for Aligning Large Language Models Agents with Interactive Environments: Quantifying and Mitigating Prompt Overfitting

# 摘要

> 强化学习（RL）是让大型语言模型（LLM）知识与顺序决策任务相契合的一种颇具前景的方法。然而，针对在特定环境中用 RL 对 LLM 代理能力进行微调所产生的影响，鲜少有研究进行深入探究。在本文中，我们提出了一个新颖的框架，用于分析 LLM 在文本环境中完成 RL 训练后对提示公式的敏感度。我们的研究结果显示，当面对与 RL 训练阶段所用不同的提示公式时，LLM 的性能会降低。此外，我们通过审视模型的内部表征和显著标记来剖析这种敏感度的根源。最后，我们提议采用对比损失来降低这种敏感度，提升 LLM 的稳健性和泛化能力。

> Reinforcement learning (RL) is a promising approach for aligning large language models (LLMs) knowledge with sequential decision-making tasks. However, few studies have thoroughly investigated the impact on LLM agents capabilities of fine-tuning them with RL in a specific environment. In this paper, we propose a novel framework to analyze the sensitivity of LLMs to prompt formulations following RL training in a textual environment. Our findings reveal that the performance of LLMs degrades when faced with prompt formulations different from those used during the RL training phase. Besides, we analyze the source of this sensitivity by examining the model's internal representations and salient tokens. Finally, we propose to use a contrastive loss to mitigate this sensitivity and improve the robustness and generalization capabilities of LLMs.

[Arxiv](https://arxiv.org/abs/2410.19920)