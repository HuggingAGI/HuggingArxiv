# 大型语言模型的持续学习：全面综述

发布时间：2024年04月25日

`LLM理论` `机器学习` `持续学习`

> Continual Learning of Large Language Models: A Comprehensive Survey

# 摘要

> 大型语言模型（LLMs）在静态、预收集的通用数据集上的成功训练，开启了众多研究的新方向和应用场景。特别地，一个研究方向是将预训练的LLMs融入到不断变化的数据分布、任务结构和用户偏好中，这一挑战颇具难度。预训练的LLMs在定制化以满足特定需求时，常会出现在原有知识领域性能大幅下降的问题，这被称为“灾难性遗忘”。尽管在持续学习（CL）领域已有深入研究，但在LLMs中这一现象呈现出新的特点。本综述提供了LLMs在CL背景下的当前研究进展的全面回顾。综述分为四个主要部分：首先介绍持续学习的LLMs概览，涵盖垂直连续性（即从通用到特定能力的持续适应）和水平连续性（即跨时间和领域的持续适应）（第3节）。接着总结LLMs在现代CL中的三个学习阶段：持续预训练（CPT）、领域自适应预训练（DAP）和持续微调（CFT）（第4节）。然后概述了LLMs持续学习的评估协议及当前可用的数据资源（第5节）。最后，探讨了LLMs持续学习中的一些引人入胜的问题（第6节）。本综述中检查的论文完整列表可在 https://github.com/Wang-ML-Lab/llm-continual-learning-survey 查看。

> The recent success of large language models (LLMs) trained on static, pre-collected, general datasets has sparked numerous research directions and applications. One such direction addresses the non-trivial challenge of integrating pre-trained LLMs into dynamic data distributions, task structures, and user preferences. Pre-trained LLMs, when tailored for specific needs, often experience significant performance degradation in previous knowledge domains -- a phenomenon known as "catastrophic forgetting". While extensively studied in the continual learning (CL) community, it presents new manifestations in the realm of LLMs. In this survey, we provide a comprehensive overview of the current research progress on LLMs within the context of CL. This survey is structured into four main sections: we first describe an overview of continually learning LLMs, consisting of two directions of continuity: vertical continuity (or vertical continual learning), i.e., continual adaptation from general to specific capabilities, and horizontal continuity (or horizontal continual learning), i.e., continual adaptation across time and domains (Section 3). We then summarize three stages of learning LLMs in the context of modern CL: Continual Pre-Training (CPT), Domain-Adaptive Pre-training (DAP), and Continual Fine-Tuning (CFT) (Section 4). Then we provide an overview of evaluation protocols for continual learning with LLMs, along with the current available data sources (Section 5). Finally, we discuss intriguing questions pertaining to continual learning for LLMs (Section 6). The full list of papers examined in this survey is available at https://github.com/Wang-ML-Lab/llm-continual-learning-survey.

[Arxiv](https://arxiv.org/abs/2404.16789)