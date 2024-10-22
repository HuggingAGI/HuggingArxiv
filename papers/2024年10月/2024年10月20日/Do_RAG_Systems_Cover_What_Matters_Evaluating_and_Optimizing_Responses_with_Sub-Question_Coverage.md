# RAG 系统是否抓住了重点？通过子问题覆盖来评估和优化回答

发布时间：2024年10月20日

`RAG` `搜索引擎` `人工智能`

> Do RAG Systems Cover What Matters? Evaluating and Optimizing Responses with Sub-Question Coverage

# 摘要

> 评估RAG系统依然充满挑战，尤其是面对那些答案模糊、需涵盖多重子题的开放性问题。本文提出了一种基于子问题覆盖率的新评估框架，旨在衡量RAG系统如何全面应对问题的各个层面。我们将问题细分为核心、背景和后续三类子问题，以凸显其重要性。通过这种分类，我们设计了一套细致的评估方案，深入剖析了You.com、Perplexity AI和Bing Chat等三大生成引擎的检索与生成特性。研究发现，尽管这些引擎在核心子问题上表现较佳，但仍有约50%的核心子问题被遗漏，显示出显著的提升空间。此外，子问题覆盖率指标在响应排序中表现出色，准确率高达82%，与人工偏好标注相媲美。最后，利用核心子问题不仅优化了检索效率，还显著提升了答案生成质量，使得RAG系统在无子问题基线上的胜率提升了74%。

> Evaluating retrieval-augmented generation (RAG) systems remains challenging, particularly for open-ended questions that lack definitive answers and require coverage of multiple sub-topics. In this paper, we introduce a novel evaluation framework based on sub-question coverage, which measures how well a RAG system addresses different facets of a question. We propose decomposing questions into sub-questions and classifying them into three types -- core, background, and follow-up -- to reflect their roles and importance. Using this categorization, we introduce a fine-grained evaluation protocol that provides insights into the retrieval and generation characteristics of RAG systems, including three commercial generative answer engines: You.com, Perplexity AI, and Bing Chat. Interestingly, we find that while all answer engines cover core sub-questions more often than background or follow-up ones, they still miss around 50% of core sub-questions, revealing clear opportunities for improvement. Further, sub-question coverage metrics prove effective for ranking responses, achieving 82% accuracy compared to human preference annotations. Lastly, we also demonstrate that leveraging core sub-questions enhances both retrieval and answer generation in a RAG system, resulting in a 74% win rate over the baseline that lacks sub-questions.

[Arxiv](https://arxiv.org/abs/2410.15531)