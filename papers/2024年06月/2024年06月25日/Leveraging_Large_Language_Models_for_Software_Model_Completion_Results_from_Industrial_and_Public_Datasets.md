# 借助大型语言模型，探索软件模型补全：工业与公共数据集的实证研究

发布时间：2024年06月25日

`RAG

理由：该论文摘要中提到了“结合大型语言模型、模型历史与检索增强生成的新方法”，这表明论文主要关注的是如何利用大型语言模型（LLM）结合检索增强生成（RAG）技术来优化软件模型的完善过程。虽然论文涉及了LLM的应用，但其核心在于探讨RAG技术在模型完善中的应用，因此更适合归类为RAG。` `软件工程` `模型演进`

> Leveraging Large Language Models for Software Model Completion: Results from Industrial and Public Datasets

# 摘要

> 在软件工程实践中，软件系统的结构与行为建模至关重要。如同其他软件工程产物，软件模型亦需随时间演进。然而，如何辅助模型师在模型演进中提供完善建议，仍是待解之谜。本文深入探讨了大型语言模型在此领域的应用潜力，并提出了一种结合大型语言模型、模型历史与检索增强生成的新方法，旨在优化模型完善过程。实验涵盖了工业应用、公共开源社区及模拟模型库三大数据集，结果显示大型语言模型在模型完善方面展现出巨大潜力，尤其在处理缺乏、噪声或无先例概念时，其推理能力尤为突出，真实工业数据上的语义正确完成率达62.30%，类型正确完成率高达86.19%。

> Modeling structure and behavior of software systems plays a crucial role in the industrial practice of software engineering. As with other software engineering artifacts, software models are subject to evolution. Supporting modelers in evolving software models with recommendations for model completions is still an open problem, though. In this paper, we explore the potential of large language models for this task. In particular, we propose an approach, retrieval-augmented generation, leveraging large language models, model histories, and retrieval-augmented generation for model completion. Through experiments on three datasets, including an industrial application, one public open-source community dataset, and one controlled collection of simulated model repositories, we evaluate the potential of large language models for model completion with retrieval-augmented generation. We found that large language models are indeed a promising technology for supporting software model evolution (62.30% semantically correct completions on real-world industrial data and up to 86.19% type-correct completions). The general inference capabilities of large language models are particularly useful when dealing with concepts for which there are few, noisy, or no examples at all.

[Arxiv](https://arxiv.org/abs/2406.17651)