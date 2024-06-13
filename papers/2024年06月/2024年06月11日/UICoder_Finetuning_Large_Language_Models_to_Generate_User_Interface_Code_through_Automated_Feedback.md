# UICoder：借助自动化反馈，微调大型语言模型，精准生成用户界面代码

发布时间：2024年06月11日

`LLM应用

这篇论文探讨了如何通过自动化反馈机制来优化大型语言模型（LLMs）生成高质量UI代码的能力。它提出了一种方法，通过使用自动化工具对LLM生成的数据进行筛选、评分和去重，从而形成一个高质量的数据集，并在此基础上对LLM进行微调以提升其性能。这种方法特别关注于提升LLM在生成UI代码方面的应用能力，因此属于LLM应用分类。` `软件开发` `人工智能`

> UICoder: Finetuning Large Language Models to Generate User Interface Code through Automated Feedback

# 摘要

> 大型语言模型（LLMs）在生成既可编译又具有视觉吸引力的UI代码时面临挑战。目前，提升生成质量的方法多依赖于昂贵的人工反馈或专有模型的精炼。本文提出了一种新策略，利用自动化反馈（如编译器和多模态模型）来优化LLMs生成高质量UI代码的能力。我们的方法首先利用现有LLM生成大量合成数据，随后通过自动化工具严格筛选、评分和去重，形成一个精炼的高质量数据集。通过在此数据集上对原始LLM进行微调，我们迭代地改进了模型。实验中，我们将此方法应用于多个开源LLMs，并通过自动化指标和人类偏好评估，发现这些模型不仅超越了所有其他可下载的基线模型，其性能甚至接近了更大型的专有模型。

> Large language models (LLMs) struggle to consistently generate UI code that compiles and produces visually relevant designs. Existing approaches to improve generation rely on expensive human feedback or distilling a proprietary model. In this paper, we explore the use of automated feedback (compilers and multi-modal models) to guide LLMs to generate high-quality UI code. Our method starts with an existing LLM and iteratively produces improved models by self-generating a large synthetic dataset using an original model, applying automated tools to aggressively filter, score, and de-duplicate the data into a refined higher quality dataset. The original LLM is improved by finetuning on this refined dataset. We applied our approach to several open-source LLMs and compared the resulting performance to baseline models with both automated metrics and human preferences. Our evaluation shows the resulting models outperform all other downloadable baselines and approach the performance of larger proprietary models.

![UICoder：借助自动化反馈，微调大型语言模型，精准生成用户界面代码](../../../paper_images/2406.07739/x1.png)

![UICoder：借助自动化反馈，微调大型语言模型，精准生成用户界面代码](../../../paper_images/2406.07739/x2.png)

![UICoder：借助自动化反馈，微调大型语言模型，精准生成用户界面代码](../../../paper_images/2406.07739/winrate.png)

![UICoder：借助自动化反馈，微调大型语言模型，精准生成用户界面代码](../../../paper_images/2406.07739/collage2.jpg)

![UICoder：借助自动化反馈，微调大型语言模型，精准生成用户界面代码](../../../paper_images/2406.07739/x3.png)

![UICoder：借助自动化反馈，微调大型语言模型，精准生成用户界面代码](../../../paper_images/2406.07739/x4.png)

[Arxiv](https://arxiv.org/abs/2406.07739)