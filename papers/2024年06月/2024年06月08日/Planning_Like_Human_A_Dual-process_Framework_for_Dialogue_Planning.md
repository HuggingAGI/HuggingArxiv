# 对话规划的双过程框架：模拟人类思维

发布时间：2024年06月08日

`LLM应用` `人工智能` `对话系统`

> Planning Like Human: A Dual-process Framework for Dialogue Planning

# 摘要

> 摘要：主动对话的难点不仅在于回应生成，更在于引导对话达成预定目标，这对反应性较强的大型语言模型（LLMs）而言是一大挑战。传统提升对话规划的方法，如精细提示工程或政策网络整合，常遭遇效率低下或性能不佳的问题。借鉴心理学中的双过程理论，区分直觉（快速）与分析（慢速）两种思维模式，我们创新提出双过程对话规划（DPDP）框架。该框架通过本能政策模型（适用于熟悉情境）与深思蒙特卡洛树搜索（MCTS）机制（应对复杂新场景）两大互补系统，融合了离线强化学习与即时MCTS学习的新颖两阶段训练，巧妙平衡了效率与策略深度。实证评估显示，DPDP在各类对话任务中均表现卓越，既确保了对话质量，又提升了操作效率，显著超越了现有技术。

> 
Abstract:In proactive dialogue, the challenge lies not just in generating responses but in steering conversations toward predetermined goals, a task where Large Language Models (LLMs) typically struggle due to their reactive nature. Traditional approaches to enhance dialogue planning in LLMs, ranging from elaborate prompt engineering to the integration of policy networks, either face efficiency issues or deliver suboptimal performance. Inspired by the dualprocess theory in psychology, which identifies two distinct modes of thinking - intuitive (fast) and analytical (slow), we propose the Dual-Process Dialogue Planning (DPDP) framework. DPDP embodies this theory through two complementary planning systems: an instinctive policy model for familiar contexts and a deliberative Monte Carlo Tree Search (MCTS) mechanism for complex, novel scenarios. This dual strategy is further coupled with a novel two-stage training regimen: offline Reinforcement Learning for robust initial policy model formation followed by MCTS-enhanced on-the-fly learning, which ensures a dynamic balance between efficiency and strategic depth. Our empirical evaluations across diverse dialogue tasks affirm DPDP's superiority in achieving both high-quality dialogues and operational efficiency, outpacing existing methods.
    

![对话规划的双过程框架：模拟人类思维](../../../paper_images/2406.05374/x1.png)

![对话规划的双过程框架：模拟人类思维](../../../paper_images/2406.05374/x2.png)

![对话规划的双过程框架：模拟人类思维](../../../paper_images/2406.05374/x3.png)

[Arxiv](https://arxiv.org//pdf/2406.05374)