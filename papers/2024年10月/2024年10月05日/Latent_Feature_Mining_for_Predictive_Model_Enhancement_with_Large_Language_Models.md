# 利用大型语言模型挖掘潜在特征，提升预测模型性能

发布时间：2024年10月05日

`LLM应用` `刑事司法`

> Latent Feature Mining for Predictive Model Enhancement with Large Language Models

# 摘要

> 预测建模常因数据有限和质量问题受阻，尤其是在特征与结果关联弱、额外特征收集受伦理或实际限制的领域。传统机器学习模型难以纳入未观测但关键的因素。我们提出FLAME框架，通过文本到文本的命题逻辑推理，利用大型语言模型增强观察特征与潜在特征，提升下游任务的预测能力。该框架设计灵活，能整合各领域独特上下文信息，确保跨领域有效应用。通过刑事司法和医疗保健领域的案例研究，我们验证了FLAME的有效性，推断的潜在特征与真实标签高度吻合，显著提升下游分类器性能。

> Predictive modeling often faces challenges due to limited data availability and quality, especially in domains where collected features are weakly correlated with outcomes and where additional feature collection is constrained by ethical or practical difficulties. Traditional machine learning (ML) models struggle to incorporate unobserved yet critical factors. In this work, we introduce an effective approach to formulate latent feature mining as text-to-text propositional logical reasoning. We propose FLAME (Faithful Latent Feature Mining for Predictive Model Enhancement), a framework that leverages large language models (LLMs) to augment observed features with latent features and enhance the predictive power of ML models in downstream tasks. Our framework is generalizable across various domains with necessary domain-specific adaptation, as it is designed to incorporate contextual information unique to each area, ensuring effective transfer to different areas facing similar data availability challenges. We validate our framework with two case studies: (1) the criminal justice system, a domain characterized by limited and ethically challenging data collection; (2) the healthcare domain, where patient privacy concerns and the complexity of medical data limit comprehensive feature collection. Our results show that inferred latent features align well with ground truth labels and significantly enhance the downstream classifier.

[Arxiv](https://arxiv.org/abs/2410.04347)