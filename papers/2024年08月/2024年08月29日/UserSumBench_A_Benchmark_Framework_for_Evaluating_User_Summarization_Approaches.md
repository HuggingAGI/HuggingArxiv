# UserSumBench：评估用户摘要技术的基准框架

发布时间：2024年08月29日

`LLM应用` `个性化推荐` `数据分析`

> UserSumBench: A Benchmark Framework for Evaluating User Summarization Approaches

# 摘要

> 大型语言模型（LLM）在从海量用户活动数据中提炼关键信息方面表现出色，生成的用户摘要不仅揭示了个人偏好和兴趣，还为个性化推荐系统等应用提供了宝贵数据。然而，新摘要技术的研发面临多重挑战，包括缺乏标准标签、摘要的主观性以及耗时耗力的人工评估。为此，我们推出了\UserSumBench框架，旨在推动基于LLM的摘要技术迭代进步。该框架包含两大亮点：一是无参考的摘要质量评估工具，经证实，该工具在MovieLens、Yelp和Amazon Review等多个数据集上与人类判断高度吻合；二是创新的鲁棒摘要生成方法，结合时间层次摘要与自我批评验证，确保摘要质量的同时杜绝信息失真。这一方法为摘要技术的创新发展奠定了坚实基础。

> Large language models (LLMs) have shown remarkable capabilities in generating user summaries from a long list of raw user activity data. These summaries capture essential user information such as preferences and interests, and therefore are invaluable for LLM-based personalization applications, such as explainable recommender systems. However, the development of new summarization techniques is hindered by the lack of ground-truth labels, the inherent subjectivity of user summaries, and human evaluation which is often costly and time-consuming. To address these challenges, we introduce \UserSumBench, a benchmark framework designed to facilitate iterative development of LLM-based summarization approaches. This framework offers two key components: (1) A reference-free summary quality metric. We show that this metric is effective and aligned with human preferences across three diverse datasets (MovieLens, Yelp and Amazon Review). (2) A novel robust summarization method that leverages time-hierarchical summarizer and self-critique verifier to produce high-quality summaries while eliminating hallucination. This method serves as a strong baseline for further innovation in summarization techniques.

[Arxiv](https://arxiv.org/abs/2408.16966)