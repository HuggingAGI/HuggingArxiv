# WikiContradict：大型语言模型在维基百科知识冲突评估的基准

发布时间：2024年06月19日

`RAG

理由：这篇论文主要关注的是检索增强生成（RAG）模型在处理大型语言模型（LLMs）中的知识冲突问题，特别是在面对来自同一来源且可信度相等的不同检索段落间的矛盾信息时的表现。论文通过创建WikiContradict基准来评估LLMs在这种情况下的性能，并探讨了如何通过自动化模型来降低评估成本。因此，这篇论文的主题与RAG模型的应用和评估紧密相关，属于RAG分类。` `问答系统` `知识图谱`

> WikiContradict: A Benchmark for Evaluating LLMs on Real-World Knowledge Conflicts from Wikipedia

# 摘要

> 检索增强生成（RAG）作为一种解决方案，有效缓解了大型语言模型（LLMs）的幻觉和信息过时等问题。但LLMs如何处理来自同一来源且可信度相等的不同检索段落间的知识冲突，仍是一个未解之谜。本研究针对维基百科中的矛盾段落，对LLM生成的答案进行了深入评估，维基百科被视为LLMs的高质量预训练资源。我们创建了WikiContradict基准，包含253个精心标注的实例，专门用于测试LLM在面对真实世界知识冲突时的表现。在多种QA场景下，我们对闭源和开源LLMs进行了广泛测试，包括单一和矛盾段落的RAG。通过在WikiContradict上对5个LLM进行超过3,500次的人工评估，我们揭示了这些模型在处理矛盾信息时的挑战，尤其是在需要推理的隐含冲突上。为了降低评估成本，我们开发了一个自动化模型，利用强大的开源语言模型评估LLM性能，F分数达到0.8。我们还对七个LLM在WikiContradict上的1,500多个答案进行了自动化评估。为了推动后续研究，我们公开了WikiContradict：https://ibm.biz/wikicontradict。

> Retrieval-augmented generation (RAG) has emerged as a promising solution to mitigate the limitations of large language models (LLMs), such as hallucinations and outdated information. However, it remains unclear how LLMs handle knowledge conflicts arising from different augmented retrieved passages, especially when these passages originate from the same source and have equal trustworthiness. In this work, we conduct a comprehensive evaluation of LLM-generated answers to questions that have varying answers based on contradictory passages from Wikipedia, a dataset widely regarded as a high-quality pre-training resource for most LLMs. Specifically, we introduce WikiContradict, a benchmark consisting of 253 high-quality, human-annotated instances designed to assess LLM performance when augmented with retrieved passages containing real-world knowledge conflicts. We benchmark a diverse range of both closed and open-source LLMs under different QA scenarios, including RAG with a single passage, and RAG with 2 contradictory passages. Through rigorous human evaluations on a subset of WikiContradict instances involving 5 LLMs and over 3,500 judgements, we shed light on the behaviour and limitations of these models. For instance, when provided with two passages containing contradictory facts, all models struggle to generate answers that accurately reflect the conflicting nature of the context, especially for implicit conflicts requiring reasoning. Since human evaluation is costly, we also introduce an automated model that estimates LLM performance using a strong open-source language model, achieving an F-score of 0.8. Using this automated metric, we evaluate more than 1,500 answers from seven LLMs across all WikiContradict instances. To facilitate future work, we release WikiContradict on: https://ibm.biz/wikicontradict.

![WikiContradict：大型语言模型在维基百科知识冲突评估的基准](../../../paper_images/2406.13805/x1.png)

![WikiContradict：大型语言模型在维基百科知识冲突评估的基准](../../../paper_images/2406.13805/x2.png)

![WikiContradict：大型语言模型在维基百科知识冲突评估的基准](../../../paper_images/2406.13805/x3.png)

![WikiContradict：大型语言模型在维基百科知识冲突评估的基准](../../../paper_images/2406.13805/example_1_1.png)

![WikiContradict：大型语言模型在维基百科知识冲突评估的基准](../../../paper_images/2406.13805/example_1_2.png)

![WikiContradict：大型语言模型在维基百科知识冲突评估的基准](../../../paper_images/2406.13805/example_1_3.png)

![WikiContradict：大型语言模型在维基百科知识冲突评估的基准](../../../paper_images/2406.13805/example_1_4.png)

![WikiContradict：大型语言模型在维基百科知识冲突评估的基准](../../../paper_images/2406.13805/example_1_5.png)

![WikiContradict：大型语言模型在维基百科知识冲突评估的基准](../../../paper_images/2406.13805/example_1_6.png)

![WikiContradict：大型语言模型在维基百科知识冲突评估的基准](../../../paper_images/2406.13805/example_2_1.png)

![WikiContradict：大型语言模型在维基百科知识冲突评估的基准](../../../paper_images/2406.13805/example_2_2.png)

![WikiContradict：大型语言模型在维基百科知识冲突评估的基准](../../../paper_images/2406.13805/example_2_3.png)

![WikiContradict：大型语言模型在维基百科知识冲突评估的基准](../../../paper_images/2406.13805/example_2_4.png)

![WikiContradict：大型语言模型在维基百科知识冲突评估的基准](../../../paper_images/2406.13805/example_2_5.png)

![WikiContradict：大型语言模型在维基百科知识冲突评估的基准](../../../paper_images/2406.13805/example_2_6.png)

![WikiContradict：大型语言模型在维基百科知识冲突评估的基准](../../../paper_images/2406.13805/example_3_1.png)

![WikiContradict：大型语言模型在维基百科知识冲突评估的基准](../../../paper_images/2406.13805/example_3_2.png)

![WikiContradict：大型语言模型在维基百科知识冲突评估的基准](../../../paper_images/2406.13805/example_3_3.png)

![WikiContradict：大型语言模型在维基百科知识冲突评估的基准](../../../paper_images/2406.13805/example_3_4.png)

![WikiContradict：大型语言模型在维基百科知识冲突评估的基准](../../../paper_images/2406.13805/example_3_5.png)

![WikiContradict：大型语言模型在维基百科知识冲突评估的基准](../../../paper_images/2406.13805/example_3_6.png)

[Arxiv](https://arxiv.org/abs/2406.13805)