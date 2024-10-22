# 探究大型语言模型中的深度遗忘现象

发布时间：2024年10月19日

`LLM应用` `数据保护` `人工智能`

> Evaluating Deep Unlearning in Large Language Models

# 摘要

> 机器遗忘是 GDPR 等数据保护法规的核心要求。以往的研究主要集中在表面遗忘任务上，即移除单个或少数相关信息。然而，在现代大型语言模型 (LLM) 中，遗忘一个事实变得异常复杂，因为这些事实可以相互推导。我们探讨了当前的 LLM 遗忘方法是否能超越表面遗忘。为此，我们提出了一个深度遗忘框架，并设计了“召回率”指标来衡量其效果。我们构建了一个包含家庭关系和传记的合成数据集 EDU-RELAT，并测试了四种遗忘方法在不同大小的 LLM 中的表现。结果显示，在深度遗忘单个事实时，这些方法要么召回率低，要么误删了大量无关信息。我们的数据集和代码已公开，网址为：https://github.com/wrh14/deep_unlearning。

> Machine unlearning is a key requirement of many data protection regulations such as GDPR. Prior work on unlearning has mostly considered superficial unlearning tasks where a single or a few related pieces of information are required to be removed. However, the task of unlearning a fact is much more challenging in recent large language models (LLMs), because the facts in LLMs can be deduced from each other. In this work, we investigate whether current unlearning methods for LLMs succeed beyond superficial unlearning of facts. Specifically, we formally propose a framework and a definition for deep unlearning facts that are interrelated. We design the metric, recall, to quantify the extent of deep unlearning. To systematically evaluate deep unlearning, we construct a synthetic dataset EDU-RELAT, which consists of a synthetic knowledge base of family relationships and biographies, together with a realistic logical rule set that connects them. We use this dataset to test four unlearning methods in four LLMs at different sizes. Our findings reveal that in the task of deep unlearning only a single fact, they either fail to properly unlearn with high recall, or end up unlearning many other irrelevant facts. Our dataset and code are publicly available at: https://github.com/wrh14/deep_unlearning.

[Arxiv](https://arxiv.org/abs/2410.15153)