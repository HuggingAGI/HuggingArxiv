# STAND-Guard：一款小型的任务自适应内容审核模型

发布时间：2024年11月07日

`LLM应用` `内容审核` `在线平台`

> STAND-Guard: A Small Task-Adaptive Content Moderation Model

# 摘要

> 内容审核，也就是审查和监控生成内容安全性的这一过程，对于构建受欢迎的在线平台以及负责任的大型语言模型意义重大。内容审核涵盖了各类任务，每个任务都有契合特定场景的独特要求。所以，开发出一款无需大量模型调优就能轻松且精准地适配新的或定制的内容审核任务的模型极为关键。本文呈现了 STAND-GUARD，一种小型任务自适应内容审核模型。其基本动因在于：通过对各种内容审核任务进行指令调整，能够在未曾见过的（分布外）内容审核任务上释放小型语言模型（SLMs）的能量。我们还仔细探究了训练任务和模型规模对跨任务微调机制成效的影响。实验显示，在超过 40 个公共数据集以及源自真实商业场景的专有数据集中，STAND-Guard 与 GPT-3.5-Turbo 旗鼓相当。尤为显著的是，在未曾见过的英语二分类任务上，STAND-Guard 取得了与 GPT-4-Turbo 近乎一致的结果。

> Content moderation, the process of reviewing and monitoring the safety of generated content, is important for development of welcoming online platforms and responsible large language models. Content moderation contains various tasks, each with its unique requirements tailored to specific scenarios. Therefore, it is crucial to develop a model that can be easily adapted to novel or customized content moderation tasks accurately without extensive model tuning. This paper presents STAND-GUARD, a Small Task-Adaptive coNtent moDeration model. The basic motivation is: by performing instruct tuning on various content moderation tasks, we can unleash the power of small language models (SLMs) on unseen (out-of-distribution) content moderation tasks. We also carefully study the effects of training tasks and model size on the efficacy of cross-task fine-tuning mechanism. Experiments demonstrate STAND-Guard is comparable to GPT-3.5-Turbo across over 40 public datasets, as well as proprietary datasets derived from real-world business scenarios. Remarkably, STAND-Guard achieved nearly equivalent results to GPT-4-Turbo on unseen English binary classification tasks

[Arxiv](https://arxiv.org/abs/2411.05214)