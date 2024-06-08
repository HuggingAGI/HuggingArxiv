# 大型语言模型（LLMs）的公平性实为一种奢望。

发布时间：2024年05月28日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）在实施公平性方面的挑战和局限性，并提出了针对特定场景下实现公平性的实用指南。这些讨论和建议更多地涉及LLMs的理论和设计原则，而不是具体的应用或Agent行为。因此，它更符合LLM理论分类，而不是Agent、RAG或LLM应用。` `人工智能伦理` `人机交互`

> The Impossibility of Fair LLMs

# 摘要

> 在ChatGPT、Gemini等通用系统盛行的今天，公平AI的重要性日益凸显。然而，人机交互的复杂性及其社会影响，使得如何实施公平标准成为难题。我们审视了机器学习界评估公平性的技术框架，如群体公平和公平表示，发现它们在大型语言模型中的应用存在根本局限。这些框架要么逻辑上不适用于LLMs，要么提出的公平概念对LLMs而言难以实现，主要是因为涉及的群体多样、敏感属性复杂、使用场景多变。为此，我们提出了实现特定场景下公平性的实用指南：强调情境的关键性、LLM开发者的责任，以及利益相关者在设计和评估迭代过程中的必要参与。长远来看，利用AI系统的通用能力来解决公平性问题，可能成为一种必要的、可扩展的AI辅助对齐方式。

> The need for fair AI is increasingly clear in the era of general-purpose systems such as ChatGPT, Gemini, and other large language models (LLMs). However, the increasing complexity of human-AI interaction and its social impacts have raised questions of how fairness standards could be applied. Here, we review the technical frameworks that machine learning researchers have used to evaluate fairness, such as group fairness and fair representations, and find that their application to LLMs faces inherent limitations. We show that each framework either does not logically extend to LLMs or presents a notion of fairness that is intractable for LLMs, primarily due to the multitudes of populations affected, sensitive attributes, and use cases. To address these challenges, we develop guidelines for the more realistic goal of achieving fairness in particular use cases: the criticality of context, the responsibility of LLM developers, and the need for stakeholder participation in an iterative process of design and evaluation. Moreover, it may eventually be possible and even necessary to use the general-purpose capabilities of AI systems to address fairness challenges as a form of scalable AI-assisted alignment.

[Arxiv](https://arxiv.org/abs/2406.03198)