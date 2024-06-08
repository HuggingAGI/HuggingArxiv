# 提升对LLMs的信任：探索比较与解读LLMs的算法之道

发布时间：2024年06月03日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）的评估技术，包括各种评估指标和创新方法，旨在提升LLMs的可信度和理解度。这些内容更多地涉及LLM的理论研究和评估框架的构建，而不是具体的应用、代理（Agent）行为或检索增强生成（RAG）技术。因此，将其归类为LLM理论是合适的。` `人工智能评估`

> Enhancing Trust in LLMs: Algorithms for Comparing and Interpreting LLMs

# 摘要

> 随着对大型语言模型（LLMs）依赖的加深，确保其可靠性、公平性和透明性变得至关重要。本文探讨了多种评估技术，旨在提升LLMs的可信度和理解度。我们分析了包括困惑度、NLP指标（如BLEU、ROUGE等）、零样本和少样本学习性能等在内的关键评估指标，并引入了创新方法，如LLMMaps分层评估、基准测试与排行榜竞争评估等，以深入理解LLMs的性能。此外，我们还强调了人类评估的重要性，以捕捉自动化指标可能忽视的细节。这些评估技术共同构成了一个框架，旨在提高LLMs的透明度，指导其开发，并增强用户信任。未来研究将进一步展示这些评估方法在实际应用中的效果。

> This paper surveys evaluation techniques to enhance the trustworthiness and understanding of Large Language Models (LLMs). As reliance on LLMs grows, ensuring their reliability, fairness, and transparency is crucial. We explore algorithmic methods and metrics to assess LLM performance, identify weaknesses, and guide development towards more trustworthy applications. Key evaluation metrics include Perplexity Measurement, NLP metrics (BLEU, ROUGE, METEOR, BERTScore, GLEU, Word Error Rate, Character Error Rate), Zero-Shot and Few-Shot Learning Performance, Transfer Learning Evaluation, Adversarial Testing, and Fairness and Bias Evaluation. We introduce innovative approaches like LLMMaps for stratified evaluation, Benchmarking and Leaderboards for competitive assessment, Stratified Analysis for in-depth understanding, Visualization of Blooms Taxonomy for cognitive level accuracy distribution, Hallucination Score for quantifying inaccuracies, Knowledge Stratification Strategy for hierarchical analysis, and Machine Learning Models for Hierarchy Generation. Human Evaluation is highlighted for capturing nuances that automated metrics may miss. These techniques form a framework for evaluating LLMs, aiming to enhance transparency, guide development, and establish user trust. Future papers will describe metric visualization and demonstrate each approach on practical examples.

[Arxiv](https://arxiv.org/abs/2406.01943)