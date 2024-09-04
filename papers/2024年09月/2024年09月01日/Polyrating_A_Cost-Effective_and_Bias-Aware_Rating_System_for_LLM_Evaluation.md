# Polyrating：高效且公正的 LLM 评估评级系统

发布时间：2024年09月01日

`LLM理论` `人工智能` `教育评估`

> Polyrating: A Cost-Effective and Bias-Aware Rating System for LLM Evaluation

# 摘要

> 基于评分的用户评估对于衡量大型语言模型（LLM）的卓越性能至关重要，但现有评分系统存在明显缺陷。为克服这些问题，我们推出了Polyrating——一个基于最大后验估计的灵活且富有表达力的评分系统，它能在降低成本的同时，对模型性能进行更深入的剖析。Polyrating能识别并量化人类偏见，确保模型比较的公正性，并借助现有基准分数大幅削减评估成本（新模型达41%，新任务达77%）。此外，它还支持跨任务的直接评分比较，全面揭示LLM在各类应用中的表现优劣。

> Rating-based human evaluation has become an essential tool to accurately evaluate the impressive performance of Large language models (LLMs). However, current rating systems suffer from several critical limitations. Specifically, they fail to account for human biases that significantly influence evaluation results, require large and expensive preference datasets to obtain accurate ratings, and do not facilitate meaningful comparisons of model ratings across different tasks. To address these issues, we introduce Polyrating, an expressive and flexible rating system based on maximum a posteriori estimation that enables a more nuanced and thorough analysis of model performance at lower costs. Polyrating can detect and quantify biases affecting human preferences, ensuring fairer model comparisons. Furthermore, Polyrating can reduce the cost of human evaluations by up to $41\%$ for new models and up to $77\%$ for new tasks by leveraging existing benchmark scores. Lastly, Polyrating enables direct comparisons of ratings across different tasks, providing a comprehensive understanding of an LLMs' strengths, weaknesses, and relative performance across different applications.

[Arxiv](https://arxiv.org/abs/2409.00696)