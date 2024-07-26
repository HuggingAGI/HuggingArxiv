# BLAZE 技术通过动态分块与硬示例学习，实现了跨语言与跨项目的错误精准定位。

发布时间：2024年07月24日

`LLM应用` `软件开发` `人工智能`

> BLAZE: Cross-Language and Cross-Project Bug Localization via Dynamic Chunking and Hard Example Learning

# 摘要

> 软件错误让开发者头疼不已，耗费他们大量时间。错误定位，即精准找出需修改的代码文件，是减轻这一负担的关键。现有工具虽依赖深度学习，但在跨项目和多语言环境中效果有限。大型语言模型（LLM）虽提供了详细定位，但仍受限于上下文窗口和映射准确性。为此，我们提出BLAZE方法，通过动态分块和硬示例学习，首先优化代码分割，再通过GPT模型微调，提升跨项目和跨语言的定位能力。我们还构建了BEETLEBOX数据集，涵盖26,321个错误，涉及五种编程语言。在三个基准数据集上的评估显示，BLAZE大幅超越现有技术，准确性、平均精度均值和平均倒数排名分别提升120%、144%和100%。消融研究进一步证实了BLAZE各组件的有效性。

> Software bugs require developers to exert significant effort to identify and resolve them, often consuming about one-third of their time. Bug localization, the process of pinpointing the exact source code files that need modification, is crucial in reducing this effort. Existing bug localization tools, typically reliant on deep learning techniques, face limitations in cross-project applicability and effectiveness in multi-language environments. Recent advancements with Large Language Models (LLMs) offer detailed representations for bug localization. However, they encounter challenges with limited context windows and mapping accuracy. To address these issues, we propose BLAZE, an approach that employs dynamic chunking and hard example learning. First, BLAZE dynamically segments source code to minimize continuity loss. Then, BLAZE fine-tunes a GPT-based model using challenging bug cases, in order to enhance cross-project and cross-language bug localization. To support the capability of BLAZE, we create the BEETLEBOX dataset, which comprises 26,321 bugs from 29 large and thriving open-source projects across five different programming languages (Java, C++, Python, Go, and JavaScript). Our evaluations of BLAZE on three benchmark datasets BEETLEBOX, SWE-Bench, and Ye et al. demonstrate substantial improvements compared to six state-of-the-art baselines. Specifically, BLAZE achieves up to an increase of 120% in Top 1 accuracy, 144% in Mean Average Precision (MAP), and 100% in Mean Reciprocal Rank (MRR). An extensive ablation study confirms the contributions of our pipeline components to the overall performance enhancement.

![BLAZE 技术通过动态分块与硬示例学习，实现了跨语言与跨项目的错误精准定位。](../../../paper_images/2407.17631/x1.png)

![BLAZE 技术通过动态分块与硬示例学习，实现了跨语言与跨项目的错误精准定位。](../../../paper_images/2407.17631/x2.png)

![BLAZE 技术通过动态分块与硬示例学习，实现了跨语言与跨项目的错误精准定位。](../../../paper_images/2407.17631/hard_mining3.png)

![BLAZE 技术通过动态分块与硬示例学习，实现了跨语言与跨项目的错误精准定位。](../../../paper_images/2407.17631/Training_Methodology.png)

![BLAZE 技术通过动态分块与硬示例学习，实现了跨语言与跨项目的错误精准定位。](../../../paper_images/2407.17631/Offline_Indexing_Methodology.png)

![BLAZE 技术通过动态分块与硬示例学习，实现了跨语言与跨项目的错误精准定位。](../../../paper_images/2407.17631/Retrieval_Methodology.png)

![BLAZE 技术通过动态分块与硬示例学习，实现了跨语言与跨项目的错误精准定位。](../../../paper_images/2407.17631/PRCurve.png)

![BLAZE 技术通过动态分块与硬示例学习，实现了跨语言与跨项目的错误精准定位。](../../../paper_images/2407.17631/Epoch_0.png)

![BLAZE 技术通过动态分块与硬示例学习，实现了跨语言与跨项目的错误精准定位。](../../../paper_images/2407.17631/Epoch_5.png)

![BLAZE 技术通过动态分块与硬示例学习，实现了跨语言与跨项目的错误精准定位。](../../../paper_images/2407.17631/Epoch_15.png)

[Arxiv](https://arxiv.org/abs/2407.17631)