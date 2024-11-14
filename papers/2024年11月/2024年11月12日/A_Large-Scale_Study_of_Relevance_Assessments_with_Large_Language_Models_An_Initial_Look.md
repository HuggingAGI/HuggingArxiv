# 一项关于大型语言模型的相关性评估的大规模研究：初步观察

发布时间：2024年11月12日

`RAG` `信息检索`

> A Large-Scale Study of Relevance Assessments with Large Language Models: An Initial Look

# 摘要

> 大型语言模型在提供相关性评估方面的应用为推进信息检索、自然语言处理及其他领域带来了令人兴奋的机会，但迄今为止仍存在许多未知。本文报告了一项大规模评估（TREC 2024 RAG 轨道）的结果，其中四种不同的相关性评估方法在原地部署：NIST 几十年来实施的“标准”全手动流程，以及利用开源 UMBRELA 工具在不同程度上利用大型语言模型的三种不同替代方案。这种设置使我们能够将不同方法引起的系统排名相关联，以表征成本和质量之间的权衡。我们发现，就 nDCG@20、nDCG@100 和 Recall@100 而言，UMBRELA 自动生成的相关性评估所引起的系统排名与来自 19 个团队的 77 次不同运行的全手动评估所引起的系统排名高度相关。我们的结果表明，自动生成的 UMBRELA 判断可以取代全手动判断，以准确捕捉运行级别的有效性。令人惊讶的是，我们发现大型语言模型的协助似乎并未增加与全手动评估的相关性，这表明与人工参与流程相关的成本并未带来明显的切实好处。总的来说，在应用相关性标准方面，人类评估者似乎比 UMBRELA 更严格。我们的工作验证了大型语言模型在学术 TREC 式评估中的使用，并为未来的研究提供了基础。

> The application of large language models to provide relevance assessments presents exciting opportunities to advance information retrieval, natural language processing, and beyond, but to date many unknowns remain. This paper reports on the results of a large-scale evaluation (the TREC 2024 RAG Track) where four different relevance assessment approaches were deployed in situ: the "standard" fully manual process that NIST has implemented for decades and three different alternatives that take advantage of LLMs to different extents using the open-source UMBRELA tool. This setup allows us to correlate system rankings induced by the different approaches to characterize tradeoffs between cost and quality. We find that in terms of nDCG@20, nDCG@100, and Recall@100, system rankings induced by automatically generated relevance assessments from UMBRELA correlate highly with those induced by fully manual assessments across a diverse set of 77 runs from 19 teams. Our results suggest that automatically generated UMBRELA judgments can replace fully manual judgments to accurately capture run-level effectiveness. Surprisingly, we find that LLM assistance does not appear to increase correlation with fully manual assessments, suggesting that costs associated with human-in-the-loop processes do not bring obvious tangible benefits. Overall, human assessors appear to be stricter than UMBRELA in applying relevance criteria. Our work validates the use of LLMs in academic TREC-style evaluations and provides the foundation for future studies.

[Arxiv](https://arxiv.org/abs/2411.08275)