# AriGraph：利用情景记忆为 LLM 代理学习知识图谱世界模型，以增强其性能

发布时间：2024年07月05日

`Agent` `人工智能` `游戏开发`

> AriGraph: Learning Knowledge Graph World Models with Episodic Memory for LLM Agents

# 摘要

> 生成式AI的发展为大型语言模型（LLM）在自主代理开发中的应用开辟了新天地。要实现真正的自主，关键在于积累并更新从环境互动中获得的知识，并有效运用。目前，基于LLM的方法通过利用完整的观察历史、总结或检索增强来借鉴过往经验。然而，这些非结构化的记忆方式并不利于复杂决策所需的推理和规划。为此，我们提出了AriGraph方法，代理在探索环境的同时构建一个融合语义与情节记忆的图结构。这种图结构能高效地关联检索与代理当前状态和目标相关的概念，从而形成一个强大的环境模型，提升代理的探索与规划能力。实验证明，配备此记忆架构的Ariadne LLM代理，在TextWorld环境中以零-shot方式出色地完成了复杂任务，包括烹饪挑战、房屋清洁及拼图寻宝等，显著超越了传统方法。

> Advancements in generative AI have broadened the potential applications of Large Language Models (LLMs) in the development of autonomous agents. Achieving true autonomy requires accumulating and updating knowledge gained from interactions with the environment and effectively utilizing it. Current LLM-based approaches leverage past experiences using a full history of observations, summarization or retrieval augmentation. However, these unstructured memory representations do not facilitate the reasoning and planning essential for complex decision-making. In our study, we introduce AriGraph, a novel method wherein the agent constructs a memory graph that integrates semantic and episodic memories while exploring the environment. This graph structure facilitates efficient associative retrieval of interconnected concepts, relevant to the agent's current state and goals, thus serving as an effective environmental model that enhances the agent's exploratory and planning capabilities. We demonstrate that our Ariadne LLM agent, equipped with this proposed memory architecture augmented with planning and decision-making, effectively handles complex tasks on a zero-shot basis in the TextWorld environment. Our approach markedly outperforms established methods such as full-history, summarization, and Retrieval-Augmented Generation in various tasks, including the cooking challenge from the First TextWorld Problems competition and novel tasks like house cleaning and puzzle Treasure Hunting.

[Arxiv](https://arxiv.org/abs/2407.04363)