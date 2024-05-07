# 利用大型语言模型的启发式方法来提升 Q-Learning 的性能

发布时间：2024年05月06日

`Agent` `控制任务`

> Enhancing Q-Learning with Large Language Model Heuristics

# 摘要

> Q-学习在序列决策任务中通过反馈学习表现出色，但要实现显著提升，需要进行大量的采样。奖励塑形技术虽能提高学习效率，却可能带来影响代理表现的偏差。特别是基于潜力的奖励塑形，由于无法根据动作或最终状态调整奖励，其在复杂环境中的效果可能受限。大型语言模型（LLM）能够实现零样本学习，但这种能力通常只适用于简单任务，并且存在推理速度慢和偶尔产生幻觉的问题。为应对这些挑战，我们提出了**LLM辅助的Q-学习**方法，该方法使用LLM作为启发式工具来辅助强化学习中的Q函数学习。这种方法既融合了两种技术的优势，又不会带来性能上的偏差。理论上，LLM启发式能够提供动作级别的指导，并且我们的架构能够将幻觉的影响转化为探索成本。此外，我们的方法确保了收敛后的Q函数与MDP的最优Q函数相对应。实验结果显示，我们的算法能够有效避免无效探索，提升采样效率，并特别适合于复杂的控制任务。

> Q-learning excels in learning from feedback within sequential decision-making tasks but requires extensive sampling for significant improvements. Although reward shaping is a powerful technique for enhancing learning efficiency, it can introduce biases that affect agent performance. Furthermore, potential-based reward shaping is constrained as it does not allow for reward modifications based on actions or terminal states, potentially limiting its effectiveness in complex environments. Additionally, large language models (LLMs) can achieve zero-shot learning, but this is generally limited to simpler tasks. They also exhibit low inference speeds and occasionally produce hallucinations. To address these issues, we propose \textbf{LLM-guided Q-learning} that employs LLMs as heuristic to aid in learning the Q-function for reinforcement learning. It combines the advantages of both technologies without introducing performance bias. Our theoretical analysis demonstrates that the LLM heuristic provides action-level guidance. Additionally, our architecture has the capability to convert the impact of hallucinations into exploration costs. Moreover, the converged Q function corresponds to the MDP optimal Q function. Experiment results demonstrated that our algorithm enables agents to avoid ineffective exploration, enhances sampling efficiency, and is well-suited for complex control tasks.

[Arxiv](https://arxiv.org/abs/2405.03341)