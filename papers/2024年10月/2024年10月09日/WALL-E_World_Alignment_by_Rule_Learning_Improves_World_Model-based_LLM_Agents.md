# WALL-E：借助规则学习，提升基于世界模型的 LLM 代理的世界对齐能力

发布时间：2024年10月09日

`Agent` `人工智能` `游戏开发`

> WALL-E: World Alignment by Rule Learning Improves World Model-based LLM Agents

# 摘要

> 大型语言模型 (LLM) 能否直接成为基于模型的代理的强大世界模型？尽管 LLM 的先验知识与特定环境的动态之间存在差距，但我们的研究表明，通过将 LLM 与其部署环境对齐，这些差距可以被弥合，而这种“世界对齐”可以通过在 LLM 上进行规则学习高效实现。鉴于 LLM 丰富的先验知识，只需少数额外规则即可将 LLM 预测与特定环境动态对齐。为此，我们提出了一种神经符号方法，通过 LLM 无梯度地学习这些规则，通过比较代理探索的轨迹和世界模型预测来诱导、更新和修剪规则。生成的世界模型由 LLM 和学习的规则组成。我们的具身 LLM 代理“WALL-E”基于模型预测控制 (MPC) 构建。通过基于精确世界模型优化前瞻动作，MPC 显著提高了探索和学习效率。与现有 LLM 代理相比，WALL-E 的推理仅需要少数主要规则，而不是冗长的缓冲轨迹包含在 LLM 输入中。在 Minecraft 和 ALFWorld 的开放世界挑战中，WALL-E 的成功率高于现有方法，且在重规划时间和用于推理的令牌数量上成本更低。在 Minecraft 中，WALL-E 的成功率超过基线 15-30%，同时减少了 8-20 次重规划轮次，仅使用 60-80% 的令牌。在 ALFWorld 中，其成功率在仅 6 次迭代后飙升至 95% 的新纪录。

> Can large language models (LLMs) directly serve as powerful world models for model-based agents? While the gaps between the prior knowledge of LLMs and the specified environment's dynamics do exist, our study reveals that the gaps can be bridged by aligning an LLM with its deployed environment and such "world alignment" can be efficiently achieved by rule learning on LLMs. Given the rich prior knowledge of LLMs, only a few additional rules suffice to align LLM predictions with the specified environment dynamics. To this end, we propose a neurosymbolic approach to learn these rules gradient-free through LLMs, by inducing, updating, and pruning rules based on comparisons of agent-explored trajectories and world model predictions. The resulting world model is composed of the LLM and the learned rules. Our embodied LLM agent "WALL-E" is built upon model-predictive control (MPC). By optimizing look-ahead actions based on the precise world model, MPC significantly improves exploration and learning efficiency. Compared to existing LLM agents, WALL-E's reasoning only requires a few principal rules rather than verbose buffered trajectories being included in the LLM input. On open-world challenges in Minecraft and ALFWorld, WALL-E achieves higher success rates than existing methods, with lower costs on replanning time and the number of tokens used for reasoning. In Minecraft, WALL-E exceeds baselines by 15-30% in success rate while costing 8-20 fewer replanning rounds and only 60-80% of tokens. In ALFWorld, its success rate surges to a new record high of 95% only after 6 iterations.

[Arxiv](https://arxiv.org/abs/2410.07484)