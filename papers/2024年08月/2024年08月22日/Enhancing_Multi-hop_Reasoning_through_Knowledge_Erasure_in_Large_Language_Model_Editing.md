# 通过在大规模语言模型编辑中实施知识擦除，我们旨在提升多跳推理能力。

发布时间：2024年08月22日

`LLM理论` `人工智能` `认知神经科学`

> Enhancing Multi-hop Reasoning through Knowledge Erasure in Large Language Model Editing

# 摘要

> 大型语言模型（LLM）在处理内部知识不准确和信息过时问题上，知识编辑成为关键解决方案。尽管现有技术在单跳推理中表现出色，但在多跳推理中存在局限。我们基于认知神经科学和LLM的运作机制，提出假设：编辑后的残留单跳知识导致模型在多跳问题中回复原始答案，影响多跳推理性能。通过实验验证这一假设后，我们创新性地提出了结合知识擦除机制的KELE方法，通过优化残留知识擦除和新知识注入，显著提升LLM在多跳推理任务中的表现。实验结果显示，KELE在GPT-J和GPT-2 XL模型上取得了显著成效。

> Large language models (LLMs) face challenges with internal knowledge inaccuracies and outdated information. Knowledge editing has emerged as a pivotal approach to mitigate these issues. Although current knowledge editing techniques exhibit promising performance in single-hop reasoning tasks, they show limitations when applied to multi-hop reasoning. Drawing on cognitive neuroscience and the operational mechanisms of LLMs, we hypothesize that the residual single-hop knowledge after editing causes edited models to revert to their original answers when processing multi-hop questions, thereby undermining their performance in multihop reasoning tasks. To validate this hypothesis, we conduct a series of experiments that empirically confirm our assumptions. Building on the validated hypothesis, we propose a novel knowledge editing method that incorporates a Knowledge Erasure mechanism for Large language model Editing (KELE). Specifically, we design an erasure function for residual knowledge and an injection function for new knowledge. Through joint optimization, we derive the optimal recall vector, which is subsequently utilized within a rank-one editing framework to update the parameters of targeted model layers. Extensive experiments on GPT-J and GPT-2 XL demonstrate that KELE substantially enhances the multi-hop reasoning capability of edited LLMs.

[Arxiv](https://arxiv.org/abs/2408.12456)