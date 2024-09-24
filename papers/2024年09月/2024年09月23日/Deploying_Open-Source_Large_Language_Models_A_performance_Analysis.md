# 开源大型语言模型的部署：性能探究

发布时间：2024年09月23日

`LLM应用` `人工智能` `云计算`

> Deploying Open-Source Large Language Models: A performance Analysis

# 摘要

> 自ChatGPT于2023年11月问世以来，大型语言模型（LLMs）在开源社区中取得了巨大成功，众多开放权重模型涌现。然而，部署这些模型的要求往往不为人知，且难以预先评估。为此，我们在波尔多大学Inria中心进行了大量测试。本文中，我们利用vLLM这一Python库，根据不同GPU资源，对比了Mistral和LLaMa等模型的性能。研究结果为希望部署LLMs的团体提供了宝贵参考，帮助他们根据现有硬件评估模型性能。这不仅促进了LLMs在各领域的应用，也为其广泛采用铺平了道路。

> Since the release of ChatGPT in November 2023, large language models (LLMs) have seen considerable success, including in the open-source community, with many open-weight models available. However, the requirements to deploy such a service are often unknown and difficult to evaluate in advance. To facilitate this process, we conducted numerous tests at the Centre Inria de l'Université de Bordeaux. In this article, we propose a comparison of the performance of several models of different sizes (mainly Mistral and LLaMa) depending on the available GPUs, using vLLM, a Python library designed to optimize the inference of these models. Our results provide valuable information for private and public groups wishing to deploy LLMs, allowing them to evaluate the performance of different models based on their available hardware. This study thus contributes to facilitating the adoption and use of these large language models in various application domains.

[Arxiv](https://arxiv.org/abs/2409.14887)