# 蒙特卡洛树搜索（MCTS）通过不断迭代的偏好学习，显著提升了推理能力。

发布时间：2024年05月01日

`分类：LLM理论` `人工智能`

> Monte Carlo Tree Search Boosts Reasoning via Iterative Preference Learning

# 摘要

> 本文提出了一种新方法，通过模仿 AlphaZero 的迭代偏好学习策略，以提升大型语言模型（LLMs）的推理能力。该方法采用蒙特卡洛树搜索（MCTS）技术，逐步搜集偏好数据，并通过前瞻性分析将奖励细化到每一步，从而增强了处理过程中的连贯性。结合结果验证和分步自我评估，我们不断优化新数据的质量评估。新算法运用直接偏好优化（DPO）技术，根据这些细化的偏好数据来调整 LLMs 的策略。理论分析显示，使用策略内抽样数据对于自我提升至关重要。在多项算术和常识推理任务上的测试表明，该方法相较于现有模型，如 Mistral-7B 监督式微调（SFT）基线，在 GSM8K、MATH 和 SciQ 等任务上均取得了显著的性能提升，准确率分别提升了 4.8%、3.3% 和 7.7%。此外，本研究还探讨了训练与推理计算之间的平衡，揭示了我们的方法如何高效地实现性能最大化。

> We introduce an approach aimed at enhancing the reasoning capabilities of Large Language Models (LLMs) through an iterative preference learning process inspired by the successful strategy employed by AlphaZero. Our work leverages Monte Carlo Tree Search (MCTS) to iteratively collect preference data, utilizing its look-ahead ability to break down instance-level rewards into more granular step-level signals. To enhance consistency in intermediate steps, we combine outcome validation and stepwise self-evaluation, continually updating the quality assessment of newly generated data. The proposed algorithm employs Direct Preference Optimization (DPO) to update the LLM policy using this newly generated step-level preference data. Theoretical analysis reveals the critical importance of using on-policy sampled data for successful self-improving. Extensive evaluations on various arithmetic and commonsense reasoning tasks demonstrate remarkable performance improvements over existing models. For instance, our approach outperforms the Mistral-7B Supervised Fine-Tuning (SFT) baseline on GSM8K, MATH, and SciQ, with substantial percentage increases in accuracy to $80.7\%$ (+$4.8\%$), $32.2\%$ (+$3.3\%$), and $88.5\%$ (+$7.7\%$), respectively. Additionally, our research delves into the training and inference compute tradeoff, providing insights into how our method effectively maximizes performance gains.

[Arxiv](https://arxiv.org/abs/2405.00451)