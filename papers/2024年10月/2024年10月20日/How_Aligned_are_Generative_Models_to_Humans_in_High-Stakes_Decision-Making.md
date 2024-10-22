# 在高风险决策中，生成模型与人类的契合度究竟如何？

发布时间：2024年10月20日

`LLM应用` `人工智能`

> How Aligned are Generative Models to Humans in High-Stakes Decision-Making?

# 摘要

> 在高风险决策中，大型生成模型（LMs）日益受到重视。本文探讨了这些模型在再犯预测任务中与人类和预测AI的对比。我们整合了COMPAS风险评分、人类判断和照片三个数据集，研究了多模态LMs的性能。除了准确性和偏见，我们还关注人类与LMs在再犯预测上的对齐。研究发现，通过上下文学习，LMs能超越人类和COMPAS。然而，反歧视提示却产生了意外效果，导致部分模型自我抑制，正面预测大幅减少。

> Large generative models (LMs) are increasingly being considered for high-stakes decision-making. This work considers how such models compare to humans and predictive AI models on a specific case of recidivism prediction. We combine three datasets -- COMPAS predictive AI risk scores, human recidivism judgements, and photos -- into a dataset on which we study the properties of several state-of-the-art, multimodal LMs. Beyond accuracy and bias, we focus on studying human-LM alignment on the task of recidivism prediction. We investigate if these models can be steered towards human decisions, the impact of adding photos, and whether anti-discimination prompting is effective. We find that LMs can be steered to outperform humans and COMPAS using in context-learning. We find anti-discrimination prompting to have unintended effects, causing some models to inhibit themselves and significantly reduce their number of positive predictions.

[Arxiv](https://arxiv.org/abs/2410.15471)