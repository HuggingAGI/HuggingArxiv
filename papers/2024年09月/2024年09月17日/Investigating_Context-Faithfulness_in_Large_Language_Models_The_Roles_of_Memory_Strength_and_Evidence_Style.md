# 探索大型语言模型中的上下文忠实度：记忆强度与证据风格的影响

发布时间：2024年09月17日

`RAG` `人工智能`

> Investigating Context-Faithfulness in Large Language Models: The Roles of Memory Strength and Evidence Style

# 摘要

> RAG 通过整合外部信息，显著提升了 LLM 的响应质量。然而，LLM 的上下文忠实度及其影响因素仍未被充分研究。本研究聚焦于记忆强度和证据呈现方式对 LLM 接受外部证据的影响。我们创新性地通过分析 LLM 对同一问题不同释义的响应差异，量化其记忆强度。同时，我们生成多种风格的证据，评估其效果。实验基于 Natural Questions 和 popQA 两个数据集，结果表明，高记忆强度的问题下，LLM 更依赖内部记忆，尤其是 GPT-4 等大型模型。而释义证据的呈现，相比简单重复或添加细节，更能提升 LLM 的接受度。

> Retrieval-augmented generation (RAG) improves Large Language Models (LLMs) by incorporating external information into the response generation process. However, how context-faithful LLMs are and what factors influence LLMs' context-faithfulness remain largely unexplored. In this study, we investigate the impact of memory strength and evidence presentation on LLMs' receptiveness to external evidence. We introduce a method to quantify the memory strength of LLMs by measuring the divergence in LLMs' responses to different paraphrases of the same question, which is not considered by previous works. We also generate evidence in various styles to evaluate the effects of evidence in different styles. Two datasets are used for evaluation: Natural Questions (NQ) with popular questions and popQA featuring long-tail questions. Our results show that for questions with high memory strength, LLMs are more likely to rely on internal memory, particularly for larger LLMs such as GPT-4. On the other hand, presenting paraphrased evidence significantly increases LLMs' receptiveness compared to simple repetition or adding details.

[Arxiv](https://arxiv.org/abs/2409.10955)