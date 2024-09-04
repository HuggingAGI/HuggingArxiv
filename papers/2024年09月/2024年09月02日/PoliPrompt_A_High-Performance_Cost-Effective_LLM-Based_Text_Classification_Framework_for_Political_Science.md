# PoliPrompt：一款高效且经济的 LLM 文本分类框架，专为政治科学领域设计。

发布时间：2024年09月02日

`LLM应用` `政治学` `新闻媒体`

> PoliPrompt: A High-Performance Cost-Effective LLM-Based Text Classification Framework for Political Science

# 摘要

> 大型语言模型 (LLM) 的进步为政治学中的文本分类带来了革新，超越了依赖大量特征工程和人工标注的传统方法。尽管如此，其分类准确性仍存疑。本文提出了一种三阶段 in-context learning 策略，旨在提升分类准确性并降低成本。该策略包括自动优化提示生成、智能示例选择及一个共识机制，后者通过先进 LLM 优化两个较弱 LLM 的决策。通过 BBC 新闻、Kavanaugh 最高法院确认及 2018 年竞选广告数据集的验证，我们的方法显著提升了分类 F1 分数（零-shot 分类提升 0.36），且成本大幅降低（较人工标注节省 78%）。这不仅克服了传统机器学习的局限，还为政治学文本分析提供了高效且可靠的解决方案。

> Recent advancements in large language models (LLMs) have opened new avenues for enhancing text classification efficiency in political science, surpassing traditional machine learning methods that often require extensive feature engineering, human labeling, and task-specific training. However, their effectiveness in achieving high classification accuracy remains questionable. This paper introduces a three-stage in-context learning approach that leverages LLMs to improve classification accuracy while minimizing experimental costs. Our method incorporates automatic enhanced prompt generation, adaptive exemplar selection, and a consensus mechanism that resolves discrepancies between two weaker LLMs, refined by an advanced LLM. We validate our approach using datasets from the BBC news reports, Kavanaugh Supreme Court confirmation, and 2018 election campaign ads. The results show significant improvements in classification F1 score (+0.36 for zero-shot classification) with manageable economic costs (-78% compared with human labeling), demonstrating that our method effectively addresses the limitations of traditional machine learning while offering a scalable and reliable solution for text analysis in political science.

[Arxiv](https://arxiv.org/abs/2409.01466)