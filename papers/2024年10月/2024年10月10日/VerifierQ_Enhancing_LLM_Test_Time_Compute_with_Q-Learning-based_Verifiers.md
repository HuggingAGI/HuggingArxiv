# VerifierQ：利用基于 Q-Learning 的验证器提升 LLM 测试时的计算效率

发布时间：2024年10月10日

`LLM理论` `人工智能`

> VerifierQ: Enhancing LLM Test Time Compute with Q-Learning-based Verifiers

# 摘要

> 近期，通过验证器模型的应用，测试时间计算的进步大幅提升了大型语言模型（LLM）的推理能力。这种生成器-验证器模式与强化学习中的演员-评论家框架相似。然而，当前的LLM验证器模型多依赖监督微调，缺乏如Q-学习的时间差异学习。本文提出VerifierQ，一种将离线Q-学习融入LLM验证器的新方法。我们解决了三大挑战：处理话语级马尔可夫决策过程、管理大规模动作空间、减轻高估偏差。VerifierQ采用有界Q值的改良Bellman更新，结合隐式Q-学习高效管理动作空间，并引入保守Q-学习公式平衡Q值估计。此方法支持并行Q值计算，提升训练效率。尽管已有研究探索生成器的RL技术，如MCTS，但VerifierQ率先通过Q-学习研究LLM的验证器（评论家）方面。将RL原则融入验证器模型，不仅补充了生成器技术的进步，还可能使LLM推理更稳健、适应性更强。数学推理任务的实验结果显示，VerifierQ在效率、准确性和鲁棒性上均优于传统监督微调方法。通过强化生成与评估的协同作用，VerifierQ推动了AI系统在处理复杂认知任务方面的持续进化。

> Recent advancements in test time compute, particularly through the use of verifier models, have significantly enhanced the reasoning capabilities of Large Language Models (LLMs). This generator-verifier approach closely resembles the actor-critic framework in reinforcement learning (RL). However, current verifier models in LLMs often rely on supervised fine-tuning without temporal difference learning such as Q-learning. This paper introduces VerifierQ, a novel approach that integrates Offline Q-learning into LLM verifier models. We address three key challenges in applying Q-learning to LLMs: (1) handling utterance-level Markov Decision Processes (MDPs), (2) managing large action spaces, and (3) mitigating overestimation bias. VerifierQ introduces a modified Bellman update for bounded Q-values, incorporates Implicit Q-learning (IQL) for efficient action space management, and integrates a novel Conservative Q-learning (CQL) formulation for balanced Q-value estimation. Our method enables parallel Q-value computation and improving training efficiency. While recent work has explored RL techniques like MCTS for generators, VerifierQ is among the first to investigate the verifier (critic) aspect in LLMs through Q-learning. This integration of RL principles into verifier models complements existing advancements in generator techniques, potentially enabling more robust and adaptive reasoning in LLMs. Experimental results on mathematical reasoning tasks demonstrate VerifierQ's superior performance compared to traditional supervised fine-tuning approaches, with improvements in efficiency, accuracy and robustness. By enhancing the synergy between generation and evaluation capabilities, VerifierQ contributes to the ongoing evolution of AI systems in addressing complex cognitive tasks across various domains.

[Arxiv](https://arxiv.org/abs/2410.08048)