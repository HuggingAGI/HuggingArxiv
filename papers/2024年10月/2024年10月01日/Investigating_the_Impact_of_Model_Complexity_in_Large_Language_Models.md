# 探究大型语言模型中模型复杂性的影响

发布时间：2024年10月01日

`LLM理论` `机器学习`

> Investigating the Impact of Model Complexity in Large Language Models

# 摘要

> 预训练微调范式下的 LLM 在 NLP 任务中表现卓越，但其复杂性对微调性能的影响仍待深入研究。本文聚焦自回归 LLM，引入 HMM 建模，探讨模型复杂性与下游任务泛化能力的关系。我们采用头部调优策略，仅训练单个头部，发现模型复杂性增加时，风险呈现“双下降”现象，初始下降意味着模型大小为零时偏差与方差达到平衡。研究面临建模与风险分析的挑战，但 HMM 数据实验验证了理论发现。

> Large Language Models (LLMs) based on the pre-trained fine-tuning paradigm have become pivotal in solving natural language processing tasks, consistently achieving state-of-the-art performance. Nevertheless, the theoretical understanding of how model complexity influences fine-tuning performance remains challenging and has not been well explored yet. In this paper, we focus on autoregressive LLMs and propose to employ Hidden Markov Models (HMMs) to model them. Based on the HMM modeling, we investigate the relationship between model complexity and the generalization capability in downstream tasks. Specifically, we consider a popular tuning paradigm for downstream tasks, head tuning, where all pre-trained parameters are frozen and only individual heads are trained atop pre-trained LLMs. Our theoretical analysis reveals that the risk initially increases and then decreases with rising model complexity, showcasing a "double descent" phenomenon. In this case, the initial "descent" is degenerate, signifying that the "sweet spot" where bias and variance are balanced occurs when the model size is zero. Obtaining the presented in this study conclusion confronts several challenges, primarily revolving around effectively modeling autoregressive LLMs and downstream tasks, as well as conducting a comprehensive risk analysis for multivariate regression. Our research is substantiated by experiments conducted on data generated from HMMs, which provided empirical support and alignment with our theoretical insights.

[Arxiv](https://arxiv.org/abs/2410.00699)