# 因果引导的主动学习策略，旨在减少大型语言模型的偏见。

发布时间：2024年08月23日

`LLM理论` `人工智能` `数据科学`

> Causal-Guided Active Learning for Debiasing Large Language Models

# 摘要

> 尽管当前的生成式大型语言模型 (LLMs) 表现出色，但它们可能仍会捕捉并利用数据集中的偏差，影响其泛化能力和安全性。传统的去偏方法因数据集偏差的多样性和过度优化问题而难以适用。为此，我们提出因果引导的主动学习 (CAL) 框架，通过 LLMs 自身识别并处理偏差样本，结合高效的基于情境学习的去偏方法，有效提升 LLMs 的去偏效果。实验证实，CAL 能精准识别并处理多种偏差模式，显著改善 LLMs 的性能。

> Although achieving promising performance, recent analyses show that current generative large language models (LLMs) may still capture dataset biases and utilize them for generation, leading to poor generalizability and harmfulness of LLMs. However, due to the diversity of dataset biases and the over-optimization problem, previous prior-knowledge-based debiasing methods and fine-tuning-based debiasing methods may not be suitable for current LLMs. To address this issue, we explore combining active learning with the causal mechanisms and propose a casual-guided active learning (CAL) framework, which utilizes LLMs itself to automatically and autonomously identify informative biased samples and induce the bias patterns. Then a cost-effective and efficient in-context learning based method is employed to prevent LLMs from utilizing dataset biases during generation. Experimental results show that CAL can effectively recognize typical biased instances and induce various bias patterns for debiasing LLMs.

[Arxiv](https://arxiv.org/abs/2408.12942)