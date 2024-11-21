# Context-Aware Testing：大型语言模型模型测试的全新范式

发布时间：2024年10月31日

`LLM应用` `机器学习` `模型测试`

> Context-Aware Testing: A New Paradigm for Model Testing with Large Language Models

# 摘要

> 测试机器学习模型的主流实际范式，要么仅依靠保留数据来计算综合评估指标，要么通过评估不同子组的表现。然而，这类仅基于数据的测试方法存在局限性，即认为可用的经验数据是测试机器学习模型的唯一输入，而忽略了能够引导模型测试的宝贵上下文信息。在本文中，我们对这种仅数据测试的常规做法提出挑战，并引入了上下文感知测试（CAT），它将上下文作为归纳偏差，以引导探寻有意义的模型故障。我们构建了首个 CAT 系统——SMART 测试，它借助大型语言模型来假设相关且可能出现的故障，并通过自证伪机制在数据上进行评估。经过在多种环境中的实证评估，我们发现 SMART 能自动识别出比其他方法更具相关性和影响力的故障，展现了 CAT 作为一种测试范式的潜力。

> The predominant de facto paradigm of testing ML models relies on either using only held-out data to compute aggregate evaluation metrics or by assessing the performance on different subgroups. However, such data-only testing methods operate under the restrictive assumption that the available empirical data is the sole input for testing ML models, disregarding valuable contextual information that could guide model testing. In this paper, we challenge the go-to approach of data-only testing and introduce context-aware testing (CAT) which uses context as an inductive bias to guide the search for meaningful model failures. We instantiate the first CAT system, SMART Testing, which employs large language models to hypothesize relevant and likely failures, which are evaluated on data using a self-falsification mechanism. Through empirical evaluations in diverse settings, we show that SMART automatically identifies more relevant and impactful failures than alternatives, demonstrating the potential of CAT as a testing paradigm.

[Arxiv](https://arxiv.org/abs/2410.24005)