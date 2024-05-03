# FLAME：为大型语言模型打造的事实感知对齐技术

发布时间：2024年05月02日

`LLM应用` `人工智能`

> FLAME: Factuality-Aware Alignment for Large Language Models

# 摘要

> 对齐技术用于优化预训练的大型语言模型（LLMs），使其能够更好地遵循自然语言指令，充当智能AI助手。但我们发现，传统对齐方法并未有效提升LLMs的事实准确性，反而可能产生更多错误信息。本文深入探讨了如何提升LLM对齐过程的事实性，首先分析了在监督式微调（SFT）和强化学习（RL）两个对齐步骤中导致幻觉现象的因素。我们发现，对LLM进行新知识或不熟悉文本的训练可能会诱发幻觉，这降低了SFT的事实准确性，因为它依赖于对LLM而言可能是新奇的人类标注数据。此外，标准RL中的奖励机制也可能促进幻觉，因为它倾向于引导LLM提供更长、更详细的响应，以适应多样化的指令需求。针对这些问题，我们提出了一种新的事实性感知对齐方法，包括事实性感知SFT和通过直接偏好优化的事实性感知RL。实验结果表明，该方法能够有效提升LLMs生成事实性响应的能力，同时不损害其遵循指令的能力。

> Alignment is a standard procedure to fine-tune pre-trained large language models (LLMs) to follow natural language instructions and serve as helpful AI assistants. We have observed, however, that the conventional alignment process fails to enhance the factual accuracy of LLMs, and often leads to the generation of more false facts (i.e. hallucination). In this paper, we study how to make the LLM alignment process more factual, by first identifying factors that lead to hallucination in both alignment steps:\ supervised fine-tuning (SFT) and reinforcement learning (RL). In particular, we find that training the LLM on new knowledge or unfamiliar texts can encourage hallucination. This makes SFT less factual as it trains on human labeled data that may be novel to the LLM. Furthermore, reward functions used in standard RL can also encourage hallucination, because it guides the LLM to provide more helpful responses on a diverse set of instructions, often preferring longer and more detailed responses. Based on these observations, we propose factuality-aware alignment, comprised of factuality-aware SFT and factuality-aware RL through direct preference optimization. Experiments show that our proposed factuality-aware alignment guides LLMs to output more factual responses while maintaining instruction-following capability.

[Arxiv](https://arxiv.org/abs/2405.01525)