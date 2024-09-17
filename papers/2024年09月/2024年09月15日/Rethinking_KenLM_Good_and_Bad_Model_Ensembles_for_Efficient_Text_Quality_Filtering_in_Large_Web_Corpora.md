# 重新审视 KenLM：探讨大型网络语料库中文本质量过滤的有效模型集成，分析其优劣。

发布时间：2024年09月15日

`LLM应用` `数据处理`

> Rethinking KenLM: Good and Bad Model Ensembles for Efficient Text Quality Filtering in Large Web Corpora

# 摘要

> 随着训练大型语言模型 (LLM) 对高质量数据的需求日益增长，高效过滤网络语料库成为一大挑战。KenLM 作为一种轻量级 n-gram 语言模型，广泛应用于 CPU 上。然而，传统 KenLM 训练仅依赖高质量数据，忽略了低质量数据的语言模式。为此，我们提出了一种集成方法，结合了高质量数据训练的 Good KenLM 和低质量数据训练的 Bad KenLM。实验显示，该方法在减少噪声的同时保留了高质量内容，优于传统方法。这表明，我们的方法在资源受限环境中，是一种计算开销最小的实用方案。

> With the increasing demand for substantial amounts of high-quality data to train large language models (LLMs), efficiently filtering large web corpora has become a critical challenge. For this purpose, KenLM, a lightweight n-gram-based language model that operates on CPUs, is widely used. However, the traditional method of training KenLM utilizes only high-quality data and, consequently, does not explicitly learn the linguistic patterns of low-quality data. To address this issue, we propose an ensemble approach that leverages two contrasting KenLMs: (i) Good KenLM, trained on high-quality data; and (ii) Bad KenLM, trained on low-quality data. Experimental results demonstrate that our approach significantly reduces noisy content while preserving high-quality content compared to the traditional KenLM training method. This indicates that our method can be a practical solution with minimal computational overhead for resource-constrained environments.

[Arxiv](https://arxiv.org/abs/2409.09613)