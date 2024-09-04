# 序列到序列奖励建模：借助语言反馈优化 RLHF

发布时间：2024年08月30日

`LLM理论` `人工智能`

> Sequence to Sequence Reward Modeling: Improving RLHF by Language Feedback

# 摘要

> 对齐大型语言模型 (LLM) 与人类意图和价值观仍是一大挑战。通过基于人类偏好训练奖励模型 (RM) 并微调 LLM 以最大化 RM 反馈，从人类反馈中进行强化学习 (RLHF) 是一种有效方法。然而，RLHF 易陷入局部优化，导致 RM 无法准确反映人类偏好，使 LLM 产生意外泛化，无法达成对齐目标。为此，我们提出了一种创新的序列到序列 (seq2seq) 奖励建模方法，通过从语言反馈而非标量反馈中学习，改进 RLHF 而无需额外注释。我们将奖励建模目标从二元最大似然估计 (MLE) 替换为序列 MLE，从而提供更丰富和细粒度的语言反馈。实验表明，该方法有效减少了单轮安全对话中的拒绝响应范式和文本摘要任务中的长响应偏差。进一步分析显示，seq2seq RM 在 3 个 NLP 任务上提高了 2B 和 7B LLM 的 RLHF 性能，平均胜率达 76.9%。此外，seq2seq RM 在分布外提示下仍能提升 RLHF 性能。

> Aligning the behavior of Large language models (LLMs) with human intentions and values remains a critical challenge. Reinforcement learning from human feedback (RLHF) aligns LLMs by training a reward model (RM) on human preferences and fine-tuning the LLMs to maximize RM feedback. Despite its effectiveness and popularity, RLHF is prone to biased local optimization. It means RM fails to provide feedback that accurately aligns with human preference, causing LLMs to explore unexpected generalizations, and failing to achieve alignment objectives. To mitigate this issue, we propose a novel \textit{sequence-to-sequence (seq2seq) reward modeling} method. Its key insight is that learning from language feedback rather than scalar feedback improves RLHF without additional annotations. We replaced the reward modeling target from binary maximum likelihood estimation (MLE) with sequence MLE. This method enables richer and fine-grained language feedback without additional annotations, models, or training stages. Our experiments demonstrated its effectiveness, specifically, reducing the refusal-to-response paradigm in single-turn safety dialogues and the long-response bias in text summarization tasks. We provide further analysis that seq2seq RM improves RLHF performance across 2B and 7B LLMs on 3 NLP tasks, achieving an average win rate of 76.9\%. We further show that seq2seq RM can still improve the performance of RLHF under out-of-distribution prompts.

[Arxiv](https://arxiv.org/abs/2409.00162)