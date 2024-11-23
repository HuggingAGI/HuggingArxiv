# LLM 充当裁判时的自我偏好偏差

发布时间：2024年10月29日

`LLM应用` `对话系统`

> Self-Preference Bias in LLM-as-a-Judge

# 摘要

> 利用大型语言模型（LLMs）的自动评估（常被称作 LLM 评估器或 LLM 充当裁判）已被广泛用于衡量对话系统的性能。然而，LLMs 存在的自我偏好偏差带来了重大风险，比如推广 LLMs 自身特有的风格或政策。尽管此问题至关重要，但定量测量自我偏好偏差的成熟方法缺失，其根本成因也鲜为人知。在本文中，我们引入了一种新的定量指标来衡量自我偏好偏差。我们的实验结果显示，GPT-4 呈现出显著的自我偏好偏差。为探究原因，我们假设 LLMs 或许更青睐对它们而言更熟悉的输出，这从较低的困惑度就能体现。我们分析了 LLM 评估与输出的困惑度之间的关系。我们的发现表明，无论输出是否为自我生成，LLMs 对困惑度低的输出的评估都显著高于人类评估者。这意味着偏差的本质在于困惑度，自我偏好偏差之所以存在，是因为 LLMs 更偏爱它们熟悉的文本。

> Automated evaluation leveraging large language models (LLMs), commonly referred to as LLM evaluators or LLM-as-a-judge, has been widely used in measuring the performance of dialogue systems. However, the self-preference bias in LLMs has posed significant risks, including promoting specific styles or policies intrinsic to the LLMs. Despite the importance of this issue, there is a lack of established methods to measure the self-preference bias quantitatively, and its underlying causes are poorly understood. In this paper, we introduce a novel quantitative metric to measure the self-preference bias. Our experimental results demonstrate that GPT-4 exhibits a significant degree of self-preference bias. To explore the causes, we hypothesize that LLMs may favor outputs that are more familiar to them, as indicated by lower perplexity. We analyze the relationship between LLM evaluations and the perplexities of outputs. Our findings reveal that LLMs assign significantly higher evaluations to outputs with lower perplexity than human evaluators, regardless of whether the outputs were self-generated. This suggests that the essence of the bias lies in perplexity and that the self-preference bias exists because LLMs prefer texts more familiar to them.

[Arxiv](https://arxiv.org/abs/2410.21819)