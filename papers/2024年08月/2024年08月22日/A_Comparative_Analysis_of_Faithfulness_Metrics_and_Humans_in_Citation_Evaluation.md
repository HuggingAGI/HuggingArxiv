# 比较分析引用评估中的信度度量与人类表现

发布时间：2024年08月22日

`LLM应用` `人工智能` `信息检索`

> A Comparative Analysis of Faithfulness Metrics and Humans in Citation Evaluation

# 摘要

> 大型语言模型（LLM）常产生“幻觉”内容，即未经证实或无法验证的信息。为此，检索增强型 LLM 通过引用可验证来源来确保内容的真实性。尽管如此，手动评估引用对陈述的支持程度仍是一大难题。以往研究虽尝试用忠诚度指标自动评估，但仅限于简单的二元分类，忽略了实际应用中的细粒度支持。我们提出了一种比较评估框架，旨在细粒度场景中检验忠诚度指标的有效性，通过区分三种支持级别（完全、部分和无支持）来评估指标。采用相关性分析、分类和检索评估，我们全面衡量了指标与人类判断的一致性。结果显示，没有单一指标能在所有评估中表现最佳，凸显了准确评估细粒度支持的复杂性。特别是，最佳指标在区分部分支持与完全或无支持时遇到困难。基于此，我们提出了开发更有效指标的实用建议。

> Large language models (LLMs) often generate content with unsupported or unverifiable content, known as "hallucinations." To address this, retrieval-augmented LLMs are employed to include citations in their content, grounding the content in verifiable sources. Despite such developments, manually assessing how well a citation supports the associated statement remains a major challenge. Previous studies tackle this challenge by leveraging faithfulness metrics to estimate citation support automatically. However, they limit this citation support estimation to a binary classification scenario, neglecting fine-grained citation support in practical scenarios. To investigate the effectiveness of faithfulness metrics in fine-grained scenarios, we propose a comparative evaluation framework that assesses the metric effectiveness in distinguishing citations between three-category support levels: full, partial, and no support. Our framework employs correlation analysis, classification evaluation, and retrieval evaluation to measure the alignment between metric scores and human judgments comprehensively. Our results indicate no single metric consistently excels across all evaluations, highlighting the complexity of accurately evaluating fine-grained support levels. Particularly, we find that the best-performing metrics struggle to distinguish partial support from full or no support. Based on these findings, we provide practical recommendations for developing more effective metrics.

[Arxiv](https://arxiv.org/abs/2408.12398)