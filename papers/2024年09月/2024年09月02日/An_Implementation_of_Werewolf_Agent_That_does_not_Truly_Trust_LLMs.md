# 实现了一个狼人代理，它对大型语言模型持保留态度。

发布时间：2024年09月02日

`Agent` `人工智能`

> An Implementation of Werewolf Agent That does not Truly Trust LLMs

# 摘要

> 狼人杀游戏因其信息不完全性，在设计计算机玩家时面临诸多挑战，如无法理解情境和进行个性化表达。为此，我们提出了一种结合大型语言模型（LLM）和规则算法的狼人代理，通过分析对话历史，代理能从LLM或预设模板中选择合适的输出，从而在特定情境下反驳、判断对话结束时机并展现个性。这一方法不仅减少了对话不连贯，还增强了表达的逻辑性。定性评估显示，我们的代理比未经调整的LLM更接近人类行为。该代理现已免费开放，旨在推动狼人杀游戏研究的进步。

> Werewolf is an incomplete information game, which has several challenges when creating a computer agent as a player given the lack of understanding of the situation and individuality of utterance (e.g., computer agents are not capable of characterful utterance or situational lying). We propose a werewolf agent that solves some of those difficulties by combining a Large Language Model (LLM) and a rule-based algorithm. In particular, our agent uses a rule-based algorithm to select an output either from an LLM or a template prepared beforehand based on the results of analyzing conversation history using an LLM. It allows the agent to refute in specific situations, identify when to end the conversation, and behave with persona. This approach mitigated conversational inconsistencies and facilitated logical utterance as a result. We also conducted a qualitative evaluation, which resulted in our agent being perceived as more human-like compared to an unmodified LLM. The agent is freely available for contributing to advance the research in the field of Werewolf game.

[Arxiv](https://arxiv.org/abs/2409.01575)