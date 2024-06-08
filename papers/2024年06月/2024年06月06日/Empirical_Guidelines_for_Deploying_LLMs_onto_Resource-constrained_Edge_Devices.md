# 资源受限边缘设备上部署 LLMs 的实用指南

发布时间：2024年06月06日

`LLM应用

这篇论文探讨了在资源受限环境下如何设计和部署个性化的大型语言模型（LLMs）。它关注了多个设计因素，如学习方法、个性化数据量、模型类型与大小、压缩技术、学习时间以及任务难度，并研究了这些因素如何影响学习效率和准确性。论文通过实验和基准测试，提供了一系列指导原则，以帮助在资源受限设备上部署LLMs。这与LLM应用分类相符，因为它专注于实际应用中的问题和解决方案，而不是理论研究。` `智能助手` `个性化技术`

> Empirical Guidelines for Deploying LLMs onto Resource-constrained Edge Devices

# 摘要

> 缩放法则虽为设计大型语言模型（LLMs）提供了指导，但这些法则是在无限计算资源的假设下研究的。随着LLMs逐渐成为个性化智能助手，其在资源受限设备上的定制化与部署变得日益重要。一个亟待解答的问题是，资源受限环境如何影响个性化LLM的设计。本研究通过实证探讨了这一问题，特别关注了多个关键设计因素间的权衡及其对学习效率与准确性的综合影响。这些因素涵盖了LLM定制化的学习方法、个性化数据量、模型类型与大小、压缩技术、学习时间以及任务难度。通过详尽的实验与基准测试，我们揭示了一系列富有洞察力的指导原则，以助LLMs在资源受限设备上的部署。例如，参数学习与RAG的最佳选择取决于任务难度，长时间的微调未必有益，而压缩后的LLM可能更适于处理有限的个性化数据。

> The scaling laws have become the de facto guidelines for designing large language models (LLMs), but they were studied under the assumption of unlimited computing resources for both training and inference. As LLMs are increasingly used as personalized intelligent assistants, their customization (i.e., learning through fine-tuning) and deployment onto resource-constrained edge devices will become more and more prevalent. An urging but open question is how a resource-constrained computing environment would affect the design choices for a personalized LLM. We study this problem empirically in this work. In particular, we consider the tradeoffs among a number of key design factors and their intertwined impacts on learning efficiency and accuracy. The factors include the learning methods for LLM customization, the amount of personalized data used for learning customization, the types and sizes of LLMs, the compression methods of LLMs, the amount of time afforded to learn, and the difficulty levels of the target use cases. Through extensive experimentation and benchmarking, we draw a number of surprisingly insightful guidelines for deploying LLMs onto resource-constrained devices. For example, an optimal choice between parameter learning and RAG may vary depending on the difficulty of the downstream task, the longer fine-tuning time does not necessarily help the model, and a compressed LLM may be a better choice than an uncompressed LLM to learn from limited personalized data.

[Arxiv](https://arxiv.org/abs/2406.03777)