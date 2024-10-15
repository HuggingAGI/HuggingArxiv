# 让AI更诚实：通过微调小型语言模型，使其能说“我不知道”，并减少RAG中的幻觉现象。

发布时间：2024年10月12日

`LLM应用` `人工智能`

> Honest AI: Fine-Tuning "Small" Language Models to Say "I Don't Know", and Reducing Hallucination in RAG

# 摘要

> 幻觉是 LLM 应用中的关键难题，尤其在企业应用中，信息准确性至关重要。为解决此问题，我们探索了两种方法：RAG 提供更新信息，以及微调 LLM 以适应新信息和输出风格。本文提出 Honest AI，通过微调“小”模型使其说“我不知道”来减少幻觉，并结合多种 RAG 方法。该方案在任务 2 中排名第一。替代方法包括结合搜索引擎和知识图谱的 RAG，微调基础 LLM，以及两者的结合。虽然所有方法都提升了 LLM 性能，但仅 RAG 效果有限，微调更为关键。最终，混合方法在 CRAG 基准中表现最佳。此外，我们提倡使用少于 100 亿参数的小模型，以提高资源效率。

> Hallucination is a key roadblock for applications of Large Language Models (LLMs), particularly for enterprise applications that are sensitive to information accuracy. To address this issue, two general approaches have been explored: Retrieval-Augmented Generation (RAG) to supply LLMs with updated information as context, and fine-tuning the LLMs with new information and desired output styles. In this paper, we propose Honest AI: a novel strategy to fine-tune "small" language models to say "I don't know" to reduce hallucination, along with several alternative RAG approaches. The solution ranked 1st in Task 2 for the false premise question. The alternative approaches include using RAG with search engine and knowledge graph results, fine-tuning base LLMs with new information and combinations of both approaches. Although all approaches improve the performance of the LLMs, RAG alone does not significantly improve the performance and fine-tuning is needed for better results. Finally, the hybrid approach achieved the highest score in the CRAG benchmark. In addition, our approach emphasizes the use of relatively small models with fewer than 10 billion parameters, promoting resource efficiency.

[Arxiv](https://arxiv.org/abs/2410.09699)