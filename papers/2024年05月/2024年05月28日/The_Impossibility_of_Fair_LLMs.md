# 大型语言模型（LLMs）的公平性实为一种难以企及的理想。

发布时间：2024年05月28日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）在公平性方面的理论问题和挑战，提出了针对特定使用案例实现公平性的实用指南，并强调了情境的关键性、开发者的责任以及利益相关者的参与。这些内容更多地涉及LLMs的理论层面，特别是关于公平性的理论探讨和应用框架的分析，因此适合归类为LLM理论。` `人工智能伦理` `机器学习`

> The Impossibility of Fair LLMs

# 摘要

> 在ChatGPT、Gemini等通用系统盛行的今天，公平AI的重要性日益凸显。然而，人机交互的复杂性及其社会影响引发了对公平标准应用的疑问。我们审视了机器学习领域用于评估公平性的技术框架，如群体公平和公平表示，发现这些框架在大型语言模型（LLMs）中的应用存在根本限制。每个框架要么逻辑上不适用于LLMs，要么提出了对LLMs而言难以实现的公平性概念，主要原因在于涉及的群体多样、敏感属性和使用案例复杂。为此，我们提出了在特定使用案例中实现公平的实用指南：强调情境的关键性、LLM开发者的责任，以及利益相关者在设计和评估迭代过程中的必要参与。未来，利用AI系统的通用能力来解决公平性挑战，可能成为一种必要的可扩展AI辅助对齐方式。

> The need for fair AI is increasingly clear in the era of general-purpose systems such as ChatGPT, Gemini, and other large language models (LLMs). However, the increasing complexity of human-AI interaction and its social impacts have raised questions of how fairness standards could be applied. Here, we review the technical frameworks that machine learning researchers have used to evaluate fairness, such as group fairness and fair representations, and find that their application to LLMs faces inherent limitations. We show that each framework either does not logically extend to LLMs or presents a notion of fairness that is intractable for LLMs, primarily due to the multitudes of populations affected, sensitive attributes, and use cases. To address these challenges, we develop guidelines for the more realistic goal of achieving fairness in particular use cases: the criticality of context, the responsibility of LLM developers, and the need for stakeholder participation in an iterative process of design and evaluation. Moreover, it may eventually be possible and even necessary to use the general-purpose capabilities of AI systems to address fairness challenges as a form of scalable AI-assisted alignment.

[Arxiv](https://arxiv.org/abs/2406.03198)