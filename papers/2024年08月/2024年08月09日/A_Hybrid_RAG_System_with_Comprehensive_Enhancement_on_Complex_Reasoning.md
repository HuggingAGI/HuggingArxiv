# 混合RAG系统，全面提升复杂推理能力

发布时间：2024年08月09日

`RAG` `人工智能` `知识图谱`

> A Hybrid RAG System with Comprehensive Enhancement on Complex Reasoning

# 摘要

> RAG 框架通过整合外部知识库，助力大型语言模型提升准确性并减少幻觉。本文介绍的混合 RAG 系统，经过一系列全面优化，大幅提升了检索质量、推理能力和数值计算精度。我们优化了网页文本和表格，引入属性预测器减少幻觉，实施了知识提取和知识图谱提取，最终构建了包含所有参考的推理策略。在 CRAG 数据集上的评估显示，我们的系统在复杂推理方面表现卓越。无论是本地还是在线评估，都证实了我们的系统在准确性和错误率上均有显著提升，且在泛化能力上表现出色。系统源代码已公开发布于 \url{https://gitlab.aicrowd.com/shizueyy/crag-new}。

> Retrieval-augmented generation (RAG) is a framework enabling large language models (LLMs) to enhance their accuracy and reduce hallucinations by integrating external knowledge bases. In this paper, we introduce a hybrid RAG system enhanced through a comprehensive suite of optimizations that significantly improve retrieval quality, augment reasoning capabilities, and refine numerical computation ability. We refined the text chunks and tables in web pages, added attribute predictors to reduce hallucinations, conducted LLM Knowledge Extractor and Knowledge Graph Extractor, and finally built a reasoning strategy with all the references. We evaluated our system on the CRAG dataset through the Meta CRAG KDD Cup 2024 Competition. Both the local and online evaluations demonstrate that our system significantly enhances complex reasoning capabilities. In local evaluations, we have significantly improved accuracy and reduced error rates compared to the baseline model, achieving a notable increase in scores. In the meanwhile, we have attained outstanding results in online assessments, demonstrating the performance and generalization capabilities of the proposed system. The source code for our system is released in \url{https://gitlab.aicrowd.com/shizueyy/crag-new}.

[Arxiv](https://arxiv.org/abs/2408.05141)