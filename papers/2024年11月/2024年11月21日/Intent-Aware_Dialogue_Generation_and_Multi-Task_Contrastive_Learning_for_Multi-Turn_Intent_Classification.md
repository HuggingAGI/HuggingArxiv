# 关于意图感知的对话生成以及用于多轮意图分类的多任务对比学习

发布时间：2024年11月21日

`LLM应用` `聊天机器人`

> Intent-Aware Dialogue Generation and Multi-Task Contrastive Learning for Multi-Turn Intent Classification

# 摘要

> 生成大规模、特定领域、多语言的多轮对话数据集，一直是在聊天机器人系统中训练高效多轮意图分类模型的重大难题。在本文中，我们推出了“意图链”，这一创新机制将隐马尔可夫模型与大型语言模型（LLMs）相结合，通过自我博弈生成具有上下文感知和意图驱动的对话。从电商聊天记录中提取特定领域知识，我们得以估算对话轮次和意图转换，进而引导生成连贯的对话。借助 LLMs 提升发射概率，我们的方法能生成自然且上下文一致的问答。我们还提出了 MINT-CL，这是一个运用多任务对比学习进行多轮意图分类的框架，无需大量标注数据就能提高分类准确率。评估显示，我们的方法在对话质量和意图分类准确度上优于基线，在多语言场景中尤为突出，同时大幅降低了数据生成的工作量。此外，我们发布了 MINT-E，这是一个多语言、具有意图感知的多轮电商对话语料库，以助力该领域的未来研究。

> Generating large-scale, domain-specific, multilingual multi-turn dialogue datasets remains a significant hurdle for training effective Multi-Turn Intent Classification models in chatbot systems. In this paper, we introduce Chain-of-Intent, a novel mechanism that combines Hidden Markov Models with Large Language Models (LLMs) to generate contextually aware, intent-driven conversations through self-play. By extracting domain-specific knowledge from e-commerce chat logs, we estimate conversation turns and intent transitions, which guide the generation of coherent dialogues. Leveraging LLMs to enhance emission probabilities, our approach produces natural and contextually consistent questions and answers. We also propose MINT-CL, a framework for multi-turn intent classification using multi-task contrastive learning, improving classification accuracy without the need for extensive annotated data. Evaluations show that our methods outperform baselines in dialogue quality and intent classification accuracy, especially in multilingual settings, while significantly reducing data generation efforts. Furthermore, we release MINT-E, a multilingual, intent-aware multi-turn e-commerce dialogue corpus to support future research in this area.

[Arxiv](https://arxiv.org/abs/2411.14252)