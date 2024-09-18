# 提升视觉增强语言模型的效率

发布时间：2024年09月17日

`LLM应用` `人工智能` `计算机视觉`

> Improving the Efficiency of Visually Augmented Language Models

# 摘要

> 尽管自回归语言模型表现出色，但由于报告偏差，这些模型缺乏视觉知识，对视觉世界了解甚少。为弥补这一缺陷，现有方法常依赖显式图像，耗时且复杂。本文提出，无需显式图像，通过 CLIP 多模态系统获取的视觉基础文本表示即可增强语言模型。我们改造了 VALM 模型，使其直接使用这种文本表示，并命名为 BLIND-VALM。实验表明，BLIND-VALM 在 VLU、NLU 和语言建模任务中与 VALM 表现相当，且更高效简洁。进一步扩展模型规模后，我们在所有评估任务中均超越了 VALM。

> Despite the impressive performance of autoregressive Language Models (LM) it has been shown that due to reporting bias, LMs lack visual knowledge, i.e. they do not know much about the visual world and its properties. To augment LMs with visual knowledge, existing solutions often rely on explicit images, requiring time-consuming retrieval or image generation systems. This paper shows that explicit images are not necessary to visually augment an LM. Instead, we use visually-grounded text representations obtained from the well-known CLIP multimodal system. For a fair comparison, we modify VALM, a visually-augmented LM which uses image retrieval and representation, to work directly with visually-grounded text representations. We name this new model BLIND-VALM. We show that BLIND-VALM performs on par with VALM for Visual Language Understanding (VLU), Natural Language Understanding (NLU) and Language Modeling tasks, despite being significantly more efficient and simpler. We also show that scaling up our model within the compute budget of VALM, either increasing the model or pre-training corpus size, we outperform VALM for all the evaluation tasks.

[Arxiv](https://arxiv.org/abs/2409.11148)