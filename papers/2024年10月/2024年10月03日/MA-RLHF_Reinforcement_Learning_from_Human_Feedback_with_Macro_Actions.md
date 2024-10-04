# MA-RLHF：通过宏动作进行的人类反馈强化学习

发布时间：2024年10月03日

`LLM理论` `人工智能`

> MA-RLHF: Reinforcement Learning from Human Feedback with Macro Actions

# 摘要

> 从人类反馈中进行强化学习（RLHF）在使大型语言模型（LLM）与人类偏好对齐方面表现出色。然而，token-level RLHF 在处理长序列时，由于奖励的延迟，难以准确评估每个动作的贡献，从而影响学习效率和收敛速度。为此，我们提出了 MA-RLHF，一个简单而高效的 RLHF 框架，它引入了宏动作（即 token 序列或更高层次的语言结构），以减少动作与奖励之间的时间距离，从而实现更快的信用分配。这种方法不仅提高了策略梯度的稳定性，还增强了每个 episode 中的学习效率，且不会增加训练或推理的计算负担。通过在文本摘要、对话生成、问答和程序合成等任务上的广泛实验，我们验证了 MA-RLHF 的有效性，其在多个任务中的性能提升显著，例如在文本摘要和代码生成任务中高达 30%，在对话任务中提升 18%，在问答任务中提升 8%。此外，MA-RLHF 在训练时间上比传统 RLHF 快 1.7 至 2 倍，且在进一步训练后仍能保持优势。我们将在 https://github.com/ernie-research/MA-RLHF 公开相关代码和数据。

> Reinforcement learning from human feedback (RLHF) has demonstrated effectiveness in aligning large language models (LLMs) with human preferences. However, token-level RLHF suffers from the credit assignment problem over long sequences, where delayed rewards make it challenging for the model to discern which actions contributed to successful outcomes. This hinders learning efficiency and slows convergence. In this paper, we propose MA-RLHF, a simple yet effective RLHF framework that incorporates macro actions -- sequences of tokens or higher-level language constructs -- into the learning process. By operating at this higher level of abstraction, our approach reduces the temporal distance between actions and rewards, facilitating faster and more accurate credit assignment. This results in more stable policy gradient estimates and enhances learning efficiency within each episode, all without increasing computational complexity during training or inference. We validate our approach through extensive experiments across various model sizes and tasks, including text summarization, dialogue generation, question answering, and program synthesis. Our method achieves substantial performance improvements over standard RLHF, with performance gains of up to 30% in text summarization and code generation, 18% in dialogue, and 8% in question answering tasks. Notably, our approach reaches parity with vanilla RLHF 1.7x to 2x faster in terms of training time and continues to outperform it with further training. We will make our code and data publicly available at https://github.com/ernie-research/MA-RLHF .

[Arxiv](https://arxiv.org/abs/2410.02743)