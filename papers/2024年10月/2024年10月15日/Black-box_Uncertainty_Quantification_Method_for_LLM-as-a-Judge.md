# LLM 作为评判者的黑箱不确定性量化方法

发布时间：2024年10月15日

`LLM理论` `人工智能`

> Black-box Uncertainty Quantification Method for LLM-as-a-Judge

# 摘要

> LLM-as-a-Judge 是评估大型语言模型 (LLM) 性能的常用方法。我们专注于量化其评估的不确定性。尽管其他领域已深入研究了不确定性量化，但 LLM 的复杂决策和计算需求带来了独特挑战。本文提出了一种新方法，通过分析评估与评分的关系来量化不确定性，从而提升 LLM-as-a-Judge 的可信度。通过交叉评估和构建混淆矩阵，我们推导出高或低不确定性的标签。实验表明，LLM 评估的准确性与不确定性分数高度相关。这表明，该方法能显著增强 LLM-as-a-Judge 评估的可靠性和一致性。

> LLM-as-a-Judge is a widely used method for evaluating the performance of Large Language Models (LLMs) across various tasks. We address the challenge of quantifying the uncertainty of LLM-as-a-Judge evaluations. While uncertainty quantification has been well-studied in other domains, applying it effectively to LLMs poses unique challenges due to their complex decision-making capabilities and computational demands. In this paper, we introduce a novel method for quantifying uncertainty designed to enhance the trustworthiness of LLM-as-a-Judge evaluations. The method quantifies uncertainty by analyzing the relationships between generated assessments and possible ratings. By cross-evaluating these relationships and constructing a confusion matrix based on token probabilities, the method derives labels of high or low uncertainty. We evaluate our method across multiple benchmarks, demonstrating a strong correlation between the accuracy of LLM evaluations and the derived uncertainty scores. Our findings suggest that this method can significantly improve the reliability and consistency of LLM-as-a-Judge evaluations.

[Arxiv](https://arxiv.org/abs/2410.11594)