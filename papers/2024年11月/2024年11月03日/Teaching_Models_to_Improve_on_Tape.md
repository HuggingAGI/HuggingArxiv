# 教导模型以优化磁带

发布时间：2024年11月03日

`LLM应用`

> Teaching Models to Improve on Tape

# 摘要

> 大型语言模型（LLMs）在特定约束条件下生成内容时往往举步维艰。不过，在这类情形中，判断这些约束是得到满足还是被违背通常较为容易。近期的研究成果显示，LLMs 能够从这种“纠正反馈”中获益。在此，我们宣称通过训练能够显著提升 LLMs 的这一技能。我们引入了一个强化学习框架，用于教导模型运用此类奖励，通过模拟交互过程，并依据模型满足约束的能力给予奖励。我们将此方法称为 CORGI（用于引导交互的强化学习控制生成），并使用未标注的训练数据在各类控制生成任务中对其进行评估。我们发现 CORGI 始终优于未融入会话反馈的基线强化学习方法。此外，CORGI 的交互框架支持元学习，让 LLM 能够在新任务的引导交互中更好地泛化。我们的结果清晰表明，会话优化与强化学习相结合，极大地提高了 LLMs 在控制生成场景中的有效性。

> Large Language Models (LLMs) often struggle when prompted to generate content under specific constraints. However, in such cases it is often easy to check whether these constraints are satisfied or violated. Recent works have shown that LLMs can benefit from such ``corrective feedback''. Here we claim that this skill of LLMs can be significantly enhanced via training. We introduce an RL framework for teaching models to use such rewards, by simulating interaction sessions, and rewarding the model according to its ability to satisfy the constraints. We refer to our method as CORGI (Controlled Generation with RL for Guided Interaction), and evaluate it on a variety of controlled generation tasks using unlabeled training data. We find that CORGI consistently outperforms the baseline reinforcement learning method that does not incorporate conversational feedback. Furthermore, CORGI's interactive framework enables meta-learning, allowing the LLM to generalize better to guided interaction in new tasks. Our results clearly show that conversational optimization, when combined with reinforcement learning, significantly improves the effectiveness of LLMs in controlled generation contexts.

[Arxiv](https://arxiv.org/abs/2411.01483)