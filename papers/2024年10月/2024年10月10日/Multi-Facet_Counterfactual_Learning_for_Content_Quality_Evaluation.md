# 多维度反事实学习助力内容质量评估

发布时间：2024年10月10日

`LLM应用` `信息筛选` `质量评估`

> Multi-Facet Counterfactual Learning for Content Quality Evaluation

# 摘要

> 在信息爆炸的时代，评估文档质量至关重要。传统方法依赖单一分数，难以区分多维度质量差异。为此，我们提出多方面反事实学习（MOLE）框架，通过大型语言模型生成关键质量变化的反事实内容，并结合对比学习和监督学习，使评估器能精准区分不同质量维度。实验证明，MOLE显著提升了评估与人类判断的相关性，为信息筛选提供了有力工具。

> Evaluating the quality of documents is essential for filtering valuable content from the current massive amount of information. Conventional approaches typically rely on a single score as a supervision signal for training content quality evaluators, which is inadequate to differentiate documents with quality variations across multiple facets. In this paper, we propose Multi-facet cOunterfactual LEarning (MOLE), a framework for efficiently constructing evaluators that perceive multiple facets of content quality evaluation. Given a specific scenario, we prompt large language models to generate counterfactual content that exhibits variations in critical quality facets compared to the original document. Furthermore, we leverage a joint training strategy based on contrastive learning and supervised learning to enable the evaluator to distinguish between different quality facets, resulting in more accurate predictions of content quality scores. Experimental results on 2 datasets across different scenarios demonstrate that our proposed MOLE framework effectively improves the correlation of document content quality evaluations with human judgments, which serve as a valuable toolkit for effective information acquisition.

[Arxiv](https://arxiv.org/abs/2410.07693)