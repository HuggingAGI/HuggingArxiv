# 为提升 LLM 上下文学习中的公平性，我们探讨战略性的演示选择策略。

发布时间：2024年08月19日

`LLM应用` `人工智能` `数据分析`

> Strategic Demonstration Selection for Improved Fairness in LLM In-Context Learning

# 摘要

> 近期研究显示，ICL 在引导 LLMs 处理结构化表格数据方面表现出色，但这些方法的公平性影响仍待深入探讨。本研究发现，在 ICL 提示中精心纳入少数群体样本，不仅能提升公平性，还能保持预测准确性。实验进一步揭示，少数与多数群体样本的比例是影响公平性与预测准确性平衡的关键。为此，我们提出了一种结合聚类与进化策略的缓解技术，旨在从训练数据中筛选出既多样又具代表性的样本集，以优化 ICL 应用中的性能与公平性。实验证实，该方法在多个公平性指标上取得了显著提升，证明了其在实际应用中的有效性。

> Recent studies highlight the effectiveness of using in-context learning (ICL) to steer large language models (LLMs) in processing tabular data, a challenging task given the structured nature of such data. Despite advancements in performance, the fairness implications of these methods are less understood. This study investigates how varying demonstrations within ICL prompts influence the fairness outcomes of LLMs. Our findings reveal that deliberately including minority group samples in prompts significantly boosts fairness without sacrificing predictive accuracy. Further experiments demonstrate that the proportion of minority to majority samples in demonstrations affects the trade-off between fairness and prediction accuracy. Based on these insights, we introduce a mitigation technique that employs clustering and evolutionary strategies to curate a diverse and representative sample set from the training data. This approach aims to enhance both predictive performance and fairness in ICL applications. Experimental results validate that our proposed method dramatically improves fairness across various metrics, showing its efficacy in real-world scenarios.

[Arxiv](https://arxiv.org/abs/2408.09757)