# RATE：用重写的瑕疵来评估奖励模型

发布时间：2024年10月15日

`LLM理论` `人工智能`

> RATE: Score Reward Models with Imperfect Rewrites of Rewrites

# 摘要

> 本文探讨了语言建模中奖励模型的评估问题。奖励模型通过给提示和响应打分来衡量响应的质量。然而，这些模型往往无法完美反映实际偏好，例如，一个旨在奖励有用性的模型可能反而偏好更长的响应。为此，我们提出了RATE评估方法，通过重写响应来测量特定属性对奖励的因果影响。我们利用大型语言模型生成反事实响应，并通过双重重写来修正误差。实验证明，在合理假设下，RATE能准确评估属性对奖励模型的影响，无论是在合成数据还是真实数据上。

> This paper concerns the evaluation of reward models used in language modeling. A reward model is a function that takes a prompt and a response and assigns a score indicating how good that response is for the prompt. A key challenge is that reward models are usually imperfect proxies for actual preferences. For example, we may worry that a model trained to reward helpfulness learns to instead prefer longer responses. In this paper, we develop an evaluation method, RATE (Rewrite-based Attribute Treatment Estimators), that allows us to measure the causal effect of a given attribute of a response (e.g., length) on the reward assigned to that response. The core idea is to use large language models to rewrite responses to produce imperfect counterfactuals, and to adjust for rewriting error by rewriting twice. We show that the RATE estimator is consistent under reasonable assumptions. We demonstrate the effectiveness of RATE on synthetic and real-world data, showing that it can accurately estimate the effect of a given attribute on the reward model.

[Arxiv](https://arxiv.org/abs/2410.11348)