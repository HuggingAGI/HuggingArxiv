# 借助思维树，我们能够跨越语言障碍，增强多步骤推理能力。

发布时间：2024年06月21日

`LLM应用

这篇论文探讨了如何通过跨语言思维树（Cross-ToT）方法提升大型语言模型（LLMs）在不同语言中的多步推理能力。这种方法通过自一致性跨语言提示机制，在不同语言间构建推理路径，以解决多步推理在非英语语言中的局限性。由于其关注的是LLMs在实际应用中的跨语言推理能力提升，因此属于LLM应用分类。` `跨语言推理`

> Empowering Multi-step Reasoning across Languages via Tree-of-Thoughts

# 摘要

> 思维链（CoT）等推理方法通过引导大型语言模型（LLMs）逐步解决复杂任务，显著提升了其推理能力。然而，由于预训练数据的不均衡分布，多步推理仍主要局限于英语，其他语言则面临挑战。本文提出了一种名为跨语言思维树（Cross-ToT）的新方法，旨在实现跨语言间的CoT推理对齐。通过采用自一致性跨语言提示机制，Cross-ToT在不同语言中构建了多步推理路径，逐步引导至最终解决方案。实验结果表明，该方法不仅减少了交互需求，还实现了业界领先的性能，显著超越了现有提示技术。

> Reasoning methods, best exemplified by the well-known Chain-of-Thought (CoT), empower the reasoning abilities of Large Language Models (LLMs) by eliciting them to solve complex tasks in a step-by-step manner. Although they are achieving significant success, the ability to deliver multi-step reasoning remains limited to English because of the imbalance in the distribution of pre-training data, which makes other languages a barrier. In this paper, we propose Cross-lingual Tree-of-Thoughts (Cross-ToT), a method for aligning Cross-lingual CoT reasoning across languages. The proposed method, through a self-consistent cross-lingual prompting mechanism inspired by the Tree-of-Thoughts approach, provides multi-step reasoning paths in different languages that, during the steps, lead to the final solution. Experimental evaluations show that our method significantly outperforms existing prompting methods by reducing the number of interactions and achieving state-of-the-art performance.

[Arxiv](https://arxiv.org/abs/2311.08097)