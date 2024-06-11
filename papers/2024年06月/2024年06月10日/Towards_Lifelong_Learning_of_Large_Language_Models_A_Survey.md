# 大型语言模型终身学习之路：综述

发布时间：2024年06月10日

`LLM应用

这篇论文摘要主要讨论了大型语言模型（LLMs）在实际应用中的适应性问题，特别是通过终身学习（持续学习）策略来增强模型对数据、任务和用户偏好变化的适应能力。这种研究关注的是如何使LLMs在运行期间持续学习，以适应动态的现实世界信息。因此，它属于LLM应用的范畴，因为它探讨的是如何将LLM技术应用于解决实际问题，而不是专注于LLM的理论研究或Agent的设计与实现。` `终身学习` `人工智能`

> Towards Lifelong Learning of Large Language Models: A Survey

# 摘要

> 随着大型语言模型（LLMs）在多领域的应用日益广泛，这些模型适应数据、任务和用户偏好变化的能力变得至关重要。传统的静态数据集训练方法已不足以应对现实世界的动态信息。终身学习（或称持续学习）通过让LLMs在运行期间持续适应性学习，既吸收新知又不忘旧识，有效解决了这一难题。本调查深入分析了终身学习的策略，将其分为内部知识和外部知识两大类。内部知识策略如持续预训练和微调，增强了LLMs在多变环境中的适应力；而外部知识策略，包括基于检索和工具的方法，利用外部资源扩展模型能力，无需改动核心参数。我们的调查贡献在于：（1）提出了一种新分类法，将终身学习文献细分为12种场景；（2）识别并分类了各场景中的通用技术；（3）强调了如模型扩展和数据选择等新兴技术，这些在LLM时代之前较少受到关注。通过深入探讨这些策略和分类，本调查旨在提升LLMs在实际应用中的适应性、可靠性和性能。

> As the applications of large language models (LLMs) expand across diverse fields, the ability of these models to adapt to ongoing changes in data, tasks, and user preferences becomes crucial. Traditional training methods, relying on static datasets, are increasingly inadequate for coping with the dynamic nature of real-world information. Lifelong learning, also known as continual or incremental learning, addresses this challenge by enabling LLMs to learn continuously and adaptively over their operational lifetime, integrating new knowledge while retaining previously learned information and preventing catastrophic forgetting. This survey delves into the sophisticated landscape of lifelong learning, categorizing strategies into two primary groups: Internal Knowledge and External Knowledge. Internal Knowledge includes continual pretraining and continual finetuning, each enhancing the adaptability of LLMs in various scenarios. External Knowledge encompasses retrieval-based and tool-based lifelong learning, leveraging external data sources and computational tools to extend the model's capabilities without modifying core parameters. The key contributions of our survey are: (1) Introducing a novel taxonomy categorizing the extensive literature of lifelong learning into 12 scenarios; (2) Identifying common techniques across all lifelong learning scenarios and classifying existing literature into various technique groups within each scenario; (3) Highlighting emerging techniques such as model expansion and data selection, which were less explored in the pre-LLM era. Through a detailed examination of these groups and their respective categories, this survey aims to enhance the adaptability, reliability, and overall performance of LLMs in real-world applications.

[Arxiv](https://arxiv.org/abs/2406.06391)