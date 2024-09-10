# 稀疏奖励也能自我训练对话代理

发布时间：2024年09月06日

`LLM应用` `人工智能` `对话系统`

> Sparse Rewards Can Self-Train Dialogue Agents

# 摘要

> 近期，SOTA 大型语言模型（LLM）在多轮对话任务中的突破，主要得益于监督微调和高质量的人类反馈。但随着基础 LLM 的不断进步，获取有意义的人类反馈变得愈发困难且昂贵。在某些领域，LLM 甚至可能超越人类，使得传统反馈方法不再实用。为此，我们提出了一种新的自我改进模式，让 LLM 无需外部反馈即可自主提升性能。我们的 Juxtaposed Outcomes for Simulation Harvesting (JOSH) 算法，通过稀疏奖励模拟环境，提取理想行为并自我训练。我们还推出了 ToolWOZ，一个基于 MultiWOZ 的稀疏奖励工具调用环境。实验表明，JOSH 训练的模型在工具交互上显著提升，同时保持了广泛的通用能力。代码和数据已在 GitHub 公开。

> Recent advancements in state-of-the-art (SOTA) Large Language Model (LLM) agents, especially in multi-turn dialogue tasks, have been primarily driven by supervised fine-tuning and high-quality human feedback. However, as base LLM models continue to improve, acquiring meaningful human feedback has become increasingly challenging and costly. In certain domains, base LLM agents may eventually exceed human capabilities, making traditional feedback-driven methods impractical. In this paper, we introduce a novel self-improvement paradigm that empowers LLM agents to autonomously enhance their performance without external human feedback. Our method, Juxtaposed Outcomes for Simulation Harvesting (JOSH), is a self-alignment algorithm that leverages a sparse reward simulation environment to extract ideal behaviors and further train the LLM on its own outputs. We present ToolWOZ, a sparse reward tool-calling simulation environment derived from MultiWOZ. We demonstrate that models trained with JOSH, both small and frontier, significantly improve tool-based interactions while preserving general model capabilities across diverse benchmarks. Our code and data are publicly available on GitHub.

[Arxiv](https://arxiv.org/abs/2409.04617)