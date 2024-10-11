# Optima：提升基于 LLM 的多智能体系统效能与效率

发布时间：2024年10月10日

`Agent` `人工智能` `多智能体系统`

> Optima: Optimizing Effectiveness and Efficiency for LLM-Based Multi-Agent System

# 摘要

> 基于 LLM 的多智能体系统 (MAS) 在协作问题解决中潜力巨大，但仍面临通信效率低、扩展性差和参数更新优化不足等挑战。为此，我们推出了 Optima 框架，通过 LLM 训练大幅提升 MAS 的通信效率和任务效果。Optima 采用生成、排序、选择和训练的迭代模式，并结合奖励函数平衡任务性能、标记效率和通信可读性。我们研究了多种强化学习算法，包括监督微调、直接偏好优化及其混合方法，揭示了它们的效果-效率权衡。我们还引入了蒙特卡洛树搜索技术，将对话轮次视为树节点，探索多样交互路径。在信息不对称问答和复杂推理等常见多智能体任务中，Optima 相比单智能体基线和普通 MAS 表现显著提升，信息交换任务中性能高达 2.8 倍，标记使用不到 10%。Optima 的效率提升为更有效利用推理计算开辟了新途径，改进了推理时间扩展定律。通过解决 MAS 的基本问题，Optima 展现了向高效、可扩展 MAS 发展的潜力（https://chenweize1998.github.io/optima-project-page）。

> Large Language Model (LLM) based multi-agent systems (MAS) show remarkable potential in collaborative problem-solving, yet they still face critical challenges: low communication efficiency, poor scalability, and a lack of effective parameter-updating optimization methods. We present Optima, a novel framework that addresses these issues by significantly enhancing both communication efficiency and task effectiveness in LLM-based MAS through LLM training. Optima employs an iterative generate, rank, select, and train paradigm with a reward function balancing task performance, token efficiency, and communication readability. We explore various RL algorithms, including Supervised Fine-Tuning, Direct Preference Optimization, and their hybrid approaches, providing insights into their effectiveness-efficiency trade-offs. We integrate Monte Carlo Tree Search-inspired techniques for DPO data generation, treating conversation turns as tree nodes to explore diverse interaction paths. Evaluated on common multi-agent tasks, including information-asymmetric question answering and complex reasoning, Optima shows consistent and substantial improvements over single-agent baselines and vanilla MAS based on Llama 3 8B, achieving up to 2.8x performance gain with less than 10\% tokens on tasks requiring heavy information exchange. Moreover, Optima's efficiency gains open new possibilities for leveraging inference-compute more effectively, leading to improved inference-time scaling laws. By addressing fundamental challenges in LLM-based MAS, Optima shows the potential towards scalable, efficient, and effective MAS (https://chenweize1998.github.io/optima-project-page).

[Arxiv](https://arxiv.org/abs/2410.08115)