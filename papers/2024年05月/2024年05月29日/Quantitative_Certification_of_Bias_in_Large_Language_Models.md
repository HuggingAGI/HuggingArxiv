# 大型语言模型偏差的量化认证

发布时间：2024年05月29日

`LLM理论

理由：这篇论文主要关注大型语言模型（LLMs）中的社会偏见和刻板印象问题，并提出了一个创新的认证框架QuaCer-B来定量评估和认证这些偏见。这个框架涉及对LLMs的理论分析和改进，以确保模型在面对大量提示时能生成无偏见的回复。因此，这项工作更偏向于LLM的理论研究，特别是关于偏见检测和认证的方法论探讨。` `人工智能` `社会科学`

> Quantitative Certification of Bias in Large Language Models

# 摘要

> 大型语言模型（LLMs）的回复可能带有社会偏见和刻板印象，但传统基准测试难以全面评估这种偏见，因其无法处理大量提示且缺乏保证。为此，我们推出了创新的认证框架QuaCer-B（偏见定量认证），确保在面对大量提示时，LLMs能生成无偏见的回复。QuaCer-B为任何包含敏感属性的提示集提供了高置信度的偏见概率界限。我们通过分析来自特定分布的各种前缀提示，展示了LLMs的偏见认证过程。认证过程中考虑了随机令牌序列、混合手动破解以及LLM嵌入空间中的破解。通过QuaCer-B，我们对主流LLMs进行了偏见认证，并揭示了它们偏见的新视角。

> Large Language Models (LLMs) can produce responses that exhibit social biases and support stereotypes. However, conventional benchmarking is insufficient to thoroughly evaluate LLM bias, as it can not scale to large sets of prompts and provides no guarantees. Therefore, we propose a novel certification framework QuaCer-B (Quantitative Certification of Bias) that provides formal guarantees on obtaining unbiased responses from target LLMs under large sets of prompts. A certificate consists of high-confidence bounds on the probability of obtaining biased responses from the LLM for any set of prompts containing sensitive attributes, sampled from a distribution. We illustrate the bias certification in LLMs for prompts with various prefixes drawn from given distributions. We consider distributions of random token sequences, mixtures of manual jailbreaks, and jailbreaks in the LLM's embedding space to certify its bias. We certify popular LLMs with QuaCer-B and present novel insights into their biases.

![大型语言模型偏差的量化认证](../../../paper_images/2405.18780/x1.png)

![大型语言模型偏差的量化认证](../../../paper_images/2405.18780/x2.png)

![大型语言模型偏差的量化认证](../../../paper_images/2405.18780/x3.png)

![大型语言模型偏差的量化认证](../../../paper_images/2405.18780/x4.png)

![大型语言模型偏差的量化认证](../../../paper_images/2405.18780/x5.png)

![大型语言模型偏差的量化认证](../../../paper_images/2405.18780/x6.png)

![大型语言模型偏差的量化认证](../../../paper_images/2405.18780/x7.png)

![大型语言模型偏差的量化认证](../../../paper_images/2405.18780/x8.png)

![大型语言模型偏差的量化认证](../../../paper_images/2405.18780/x9.png)

![大型语言模型偏差的量化认证](../../../paper_images/2405.18780/x10.png)

![大型语言模型偏差的量化认证](../../../paper_images/2405.18780/x11.png)

![大型语言模型偏差的量化认证](../../../paper_images/2405.18780/x12.png)

![大型语言模型偏差的量化认证](../../../paper_images/2405.18780/x13.png)

[Arxiv](https://arxiv.org/abs/2405.18780)