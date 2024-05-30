# 大型语言模型偏差的量化认证

发布时间：2024年05月29日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）中存在的社会偏见和刻板印象问题，并开发了一个名为QuaCer-B的偏见定量认证框架。该框架旨在通过高置信度界限来量化LLMs在任何包含敏感属性的提示集上产生偏见回复的概率。这项工作涉及对LLMs的理论分析和偏见评估，因此属于LLM理论分类。` `人工智能` `社会科学`

> Quantitative Certification of Bias in Large Language Models

# 摘要

> 大型语言模型（LLMs）可能产生带有社会偏见和刻板印象的回复。传统的基准测试无法全面评估这些偏见，因为它无法处理大量提示集，并且缺乏保证。为此，我们开发了QuaCer-B（偏见定量认证框架），确保在面对大量提示时，LLMs能提供无偏见的回复。该框架通过高置信度界限来量化LLMs在任何包含敏感属性的提示集上产生偏见回复的概率。我们通过分析来自特定分布的各种前缀提示，展示了LLMs的偏见认证过程。我们考虑了随机令牌序列、混合手动越狱以及LLM嵌入空间中的越狱情况，以验证其偏见。通过QuaCer-B，我们对流行的LLMs进行了认证，并揭示了它们偏见的新视角。

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