# 破除偏见，搭建沟通之桥：利用接触假设评估并减轻 LLMs 中的社会偏见

发布时间：2024年07月02日

`LLM应用` `社会心理学` `人工智能`

> Breaking Bias, Building Bridges: Evaluation and Mitigation of Social Biases in LLMs via Contact Hypothesis

# 摘要

> 大型语言模型（LLM）不仅反映训练数据中的偏见，还加剧了社会刻板印象和不平等。我们借鉴社会心理学的接触假设，探索其在减少LLM偏见方面的应用。通过模拟不同形式的社会接触，我们评估了这些接触对模型偏见的影响，类似于群体间互动在现实世界中减少偏见的效果。我们精心设计了包含108,000个提示的数据集，涵盖13个社会偏见维度，用于评估LLaMA 2、Tulu和NousHermes三个模型。我们创新性地提出了社会接触去偏见（SCD）技术，通过无偏见的响应对模型进行调优。研究显示，尽管LLM在接触探测下表现出偏见，但通过我们的SCD策略，一个周期的调优即可显著减少高达40%的偏见。相关代码和数据已公开在https://github.com/chahatraj/breakingbias。

> Large Language Models (LLMs) perpetuate social biases, reflecting prejudices in their training data and reinforcing societal stereotypes and inequalities. Our work explores the potential of the Contact Hypothesis, a concept from social psychology for debiasing LLMs. We simulate various forms of social contact through LLM prompting to measure their influence on the model's biases, mirroring how intergroup interactions can reduce prejudices in social contexts. We create a dataset of 108,000 prompts following a principled approach replicating social contact to measure biases in three LLMs (LLaMA 2, Tulu, and NousHermes) across 13 social bias dimensions. We propose a unique debiasing technique, Social Contact Debiasing (SCD), that instruction-tunes these models with unbiased responses to prompts. Our research demonstrates that LLM responses exhibit social biases when subject to contact probing, but more importantly, these biases can be significantly reduced by up to 40% in 1 epoch of instruction tuning LLaMA 2 following our SCD strategy. Our code and data are available at https://github.com/chahatraj/breakingbias.

[Arxiv](https://arxiv.org/abs/2407.02030)