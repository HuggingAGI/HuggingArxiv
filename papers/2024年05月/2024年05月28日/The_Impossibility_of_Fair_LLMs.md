# 大型语言模型（LLMs）的公平性实属难求。

发布时间：2024年05月28日

`LLM应用

这篇论文主要关注的是大型语言模型（LLMs）在实际应用中的公平性问题，特别是在人机交互和社会影响方面的公平性挑战。论文分析了现有的公平性评估框架在LLMs上的局限性，并提出了针对特定使用案例的实用指南，强调了情境的重要性、开发者的责任以及利益相关者的参与。这些内容与LLMs的实际应用紧密相关，因此将其归类为LLM应用。` `人工智能伦理` `人机交互`

> The Impossibility of Fair LLMs

# 摘要

> 在ChatGPT、Gemini等通用系统盛行的时代，公平AI的重要性日益凸显。然而，人机交互的复杂性及其社会影响提出了一个关键问题：如何确保公平性标准得以实施？我们审视了机器学习界用于评估公平性的技术框架，如群体公平和公平表示，发现这些框架在应用于LLMs时存在根本局限。每个框架要么逻辑上不适用于LLMs，要么提出了对LLMs而言难以实现的公平性概念，这主要是因为涉及的群体多样、敏感属性复杂以及使用案例繁多。为此，我们提出了实现特定使用案例中公平性的实用指南：强调情境的关键性、LLM开发者的责任，以及利益相关者在设计和评估过程中的迭代参与。最终，利用AI系统的通用能力来解决公平性挑战，可能成为一种必要的可扩展AI辅助对齐方式。

> The need for fair AI is increasingly clear in the era of general-purpose systems such as ChatGPT, Gemini, and other large language models (LLMs). However, the increasing complexity of human-AI interaction and its social impacts have raised questions of how fairness standards could be applied. Here, we review the technical frameworks that machine learning researchers have used to evaluate fairness, such as group fairness and fair representations, and find that their application to LLMs faces inherent limitations. We show that each framework either does not logically extend to LLMs or presents a notion of fairness that is intractable for LLMs, primarily due to the multitudes of populations affected, sensitive attributes, and use cases. To address these challenges, we develop guidelines for the more realistic goal of achieving fairness in particular use cases: the criticality of context, the responsibility of LLM developers, and the need for stakeholder participation in an iterative process of design and evaluation. Moreover, it may eventually be possible and even necessary to use the general-purpose capabilities of AI systems to address fairness challenges as a form of scalable AI-assisted alignment.

[Arxiv](https://arxiv.org/abs/2406.03198)