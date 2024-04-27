# 深入探究大型语言模型的持续学习：全面综述

发布时间：2024年04月25日

`分类：LLM应用

这篇论文摘要主要讨论了大型语言模型（LLMs）在持续学习（Continual Learning, CL）领域的应用和挑战。它概述了LLMs在CL中的研究进展，包括持续预训练、领域自适应预训练和持续微调等学习阶段，以及评估协议和数据资源。由于论文聚焦于LLMs在特定应用场景中的性能和挑战，因此将其归类为LLM应用。` `机器学习` `持续学习`

> Continual Learning of Large Language Models: A Comprehensive Survey

# 摘要

> 大型语言模型（LLMs）在静态、预先收集的通用数据集上的训练成就，开启了众多研究新方向和应用场景。其中一个关键研究方向是如何将这些预训练的LLMs有效地融入到不断变化的数据分布、任务结构和用户偏好中。当这些模型为特定需求定制时，常常会在原有知识领域出现性能大幅下降，这一现象被称为“灾难性遗忘”。尽管在持续学习（CL）领域已有深入研究，但在LLMs的应用中仍展现出新的挑战。本文综述了LLMs在CL领域的研究进展，分为四个部分：首先介绍持续学习的LLMs概览，涉及垂直连续性和水平连续性两个维度（第3节）；接着总结LLMs在现代CL中的三个学习阶段：持续预训练（CPT）、领域自适应预训练（DAP）和持续微调（CFT）（第4节）；然后概述了LLMs持续学习的评估协议和可用数据资源（第5节）；最后探讨了LLMs持续学习中的一些引人入胜的问题（第6节）。相关论文的完整列表可访问 https://github.com/Wang-ML-Lab/llm-continual-learning-survey。

> The recent success of large language models (LLMs) trained on static, pre-collected, general datasets has sparked numerous research directions and applications. One such direction addresses the non-trivial challenge of integrating pre-trained LLMs into dynamic data distributions, task structures, and user preferences. Pre-trained LLMs, when tailored for specific needs, often experience significant performance degradation in previous knowledge domains -- a phenomenon known as "catastrophic forgetting". While extensively studied in the continual learning (CL) community, it presents new manifestations in the realm of LLMs. In this survey, we provide a comprehensive overview of the current research progress on LLMs within the context of CL. This survey is structured into four main sections: we first describe an overview of continually learning LLMs, consisting of two directions of continuity: vertical continuity (or vertical continual learning), i.e., continual adaptation from general to specific capabilities, and horizontal continuity (or horizontal continual learning), i.e., continual adaptation across time and domains (Section 3). We then summarize three stages of learning LLMs in the context of modern CL: Continual Pre-Training (CPT), Domain-Adaptive Pre-training (DAP), and Continual Fine-Tuning (CFT) (Section 4). Then we provide an overview of evaluation protocols for continual learning with LLMs, along with the current available data sources (Section 5). Finally, we discuss intriguing questions pertaining to continual learning for LLMs (Section 6). The full list of papers examined in this survey is available at https://github.com/Wang-ML-Lab/llm-continual-learning-survey.

[Arxiv](https://arxiv.org/abs/2404.16789)