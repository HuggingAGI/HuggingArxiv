# RS-GPT4V：遥感图像理解领域的统一多模态指令遵循数据集

发布时间：2024年06月18日

`RAG

理由：这篇论文主要介绍了如何通过构建一个新的数据集RS-GPT4V来增强多模态大型语言模型（MLLM）在遥感图像智能理解领域的应用。该数据集的设计旨在提升模型的泛化能力、深度场景理解和高级视觉推理能力，这些都是RAG（Retrieval-Augmented Generation）模型的关键特性，即通过检索增强生成过程，使模型能够更好地理解和生成与特定领域相关的信息。因此，这篇论文更适合归类于RAG，因为它专注于通过数据集的改进来提升模型的领域适应性和理解能力。` `人工智能`

> RS-GPT4V: A Unified Multimodal Instruction-Following Dataset for Remote Sensing Image Understanding

# 摘要

> 遥感图像智能理解模型正经历一场由多模态大型语言模型（MLLM）引领的范式革命，从专一领域模型学习转向先构建通用预训练基础模型，再进行领域适应性学习。在这一新范式下，过去十年中推动遥感图像智能理解发展的旧数据集已不再适配新挑战。我们主张，需设计一个新数据集，它应具备：1) 泛化能力，使模型能跨任务学习并灵活适应；2) 深度场景理解，让模型捕捉对象细节并用自然语言描绘场景；3) 高级视觉推理能力。为此，我们推出了RS-GPT4V，一个融合GPT-4V与现有数据的高质量、多元化指令遵循数据集。我们通过GPT-4V生成的（问题，答案）统一了标题生成与定位等任务，以增强泛化性；通过局部与全局策略结合的分层指令描述，深化场景理解；通过多轮QA对，赋予模型推理能力。实证显示，经RS-GPT4V微调的MLLMs能精准捕捉细节。该数据集已公开，详情请访问：https://github.com/GeoX-Lab/RS-GPT4V。

> The remote sensing image intelligence understanding model is undergoing a new profound paradigm shift which has been promoted by multi-modal large language model (MLLM), i.e. from the paradigm learning a domain model (LaDM) shifts to paradigm learning a pre-trained general foundation model followed by an adaptive domain model (LaGD). Under the new LaGD paradigm, the old datasets, which have led to advances in RSI intelligence understanding in the last decade, are no longer suitable for fire-new tasks. We argued that a new dataset must be designed to lighten tasks with the following features: 1) Generalization: training model to learn shared knowledge among tasks and to adapt to different tasks; 2) Understanding complex scenes: training model to understand the fine-grained attribute of the objects of interest, and to be able to describe the scene with natural language; 3) Reasoning: training model to be able to realize high-level visual reasoning. In this paper, we designed a high-quality, diversified, and unified multimodal instruction-following dataset for RSI understanding produced by GPT-4V and existing datasets, which we called RS-GPT4V. To achieve generalization, we used a (Question, Answer) which was deduced from GPT-4V via instruction-following to unify the tasks such as captioning and localization; To achieve complex scene, we proposed a hierarchical instruction description with local strategy in which the fine-grained attributes of the objects and their spatial relationships are described and global strategy in which all the local information are integrated to yield detailed instruction descript; To achieve reasoning, we designed multiple-turn QA pair to provide the reasoning ability for a model. The empirical results show that the fine-tuned MLLMs by RS-GPT4V can describe fine-grained information. The dataset is available at: https://github.com/GeoX-Lab/RS-GPT4V.

![RS-GPT4V：遥感图像理解领域的统一多模态指令遵循数据集](../../../paper_images/2406.12479/pyramid.png)

![RS-GPT4V：遥感图像理解领域的统一多模态指令遵循数据集](../../../paper_images/2406.12479/principle.png)

![RS-GPT4V：遥感图像理解领域的统一多模态指令遵循数据集](../../../paper_images/2406.12479/main.png)

![RS-GPT4V：遥感图像理解领域的统一多模态指令遵循数据集](../../../paper_images/2406.12479/caption.png)

![RS-GPT4V：遥感图像理解领域的统一多模态指令遵循数据集](../../../paper_images/2406.12479/vqa.png)

![RS-GPT4V：遥感图像理解领域的统一多模态指令遵循数据集](../../../paper_images/2406.12479/llava.png)

[Arxiv](https://arxiv.org/abs/2406.12479)