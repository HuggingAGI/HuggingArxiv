# Agent Q：专为自主AI代理设计的高级推理与学习系统

发布时间：2024年08月13日

`Agent` `电子商务` `人工智能`

> Agent Q: Advanced Reasoning and Learning for Autonomous AI Agents

# 摘要

> 大型语言模型（LLM）在复杂推理的自然语言任务中表现出色，但在交互环境中的多步骤代理推理仍具挑战。传统监督预训练在动态环境如网页导航中难以实现自主决策。我们提出的框架结合了引导式蒙特卡洛树搜索和自我批评机制，通过迭代微调提升代理性能。在模拟的WebShop平台测试中，我们的方法不仅超越了传统基线，甚至在具备在线搜索能力时超越了人类平均表现。在实际预订场景中，我们的方法显著提升了模型的决策成功率，从18.6%跃升至81.7%，并在进一步优化后达到95.4%。这一进展标志着自主代理能力的重要突破，为现实世界中的复杂决策提供了更可靠的解决方案。

> Large Language Models (LLMs) have shown remarkable capabilities in natural language tasks requiring complex reasoning, yet their application in agentic, multi-step reasoning within interactive environments remains a difficult challenge. Traditional supervised pre-training on static datasets falls short in enabling autonomous agent capabilities needed to perform complex decision-making in dynamic settings like web navigation. Previous attempts to bridge this ga-through supervised fine-tuning on curated expert demonstrations-often suffer from compounding errors and limited exploration data, resulting in sub-optimal policy outcomes. To overcome these challenges, we propose a framework that combines guided Monte Carlo Tree Search (MCTS) search with a self-critique mechanism and iterative fine-tuning on agent interactions using an off-policy variant of the Direct Preference Optimization (DPO) algorithm. Our method allows LLM agents to learn effectively from both successful and unsuccessful trajectories, thereby improving their generalization in complex, multi-step reasoning tasks. We validate our approach in the WebShop environment-a simulated e-commerce platform where it consistently outperforms behavior cloning and reinforced fine-tuning baseline, and beats average human performance when equipped with the capability to do online search. In real-world booking scenarios, our methodology boosts Llama-3 70B model's zero-shot performance from 18.6% to 81.7% success rate (a 340% relative increase) after a single day of data collection and further to 95.4% with online search. We believe this represents a substantial leap forward in the capabilities of autonomous agents, paving the way for more sophisticated and reliable decision-making in real-world settings.

[Arxiv](https://arxiv.org/abs/2408.07199)