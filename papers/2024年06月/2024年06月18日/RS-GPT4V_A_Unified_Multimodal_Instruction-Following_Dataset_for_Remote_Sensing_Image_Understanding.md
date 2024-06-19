# RS-GPT4V：遥感图像理解领域的统一多模态指令遵循数据集

发布时间：2024年06月18日

`LLM应用

理由：这篇论文主要讨论了如何利用多模态大型语言模型（MLLM）来改进遥感图像智能理解模型，并设计了一个新的数据集RS-GPT4V来支持这一目标。论文的重点在于应用LLM技术来解决实际问题，即遥感图像的理解，而不是探讨LLM的理论基础或Agent的设计与实现。因此，它属于LLM应用类别。` `人工智能`

> RS-GPT4V: A Unified Multimodal Instruction-Following Dataset for Remote Sensing Image Understanding

# 摘要

> 遥感图像智能理解模型正迎来由多模态大型语言模型（MLLM）驱动的全新范式变革，从专一领域模型学习转向通用基础模型预训练加适应性领域模型学习。在这一新范式下，过去十年引领进步的旧数据集已不再适配新挑战。我们主张，需打造一个具备泛化性、复杂场景理解和高级推理能力的新数据集。为此，我们精心设计了RS-GPT4V，一个融合GPT-4V与现有数据的高质量、多元化指令遵循型多模态数据集。通过GPT-4V生成的问答对，我们统一了标题生成与定位等任务，实现了泛化；采用层次化指令描述，结合局部与全局策略，深入解析对象细节与空间关系，描绘复杂场景；设计多轮问答，赋予模型高级推理能力。实证显示，经RS-GPT4V微调的MLLMs能精准捕捉图像细节。该数据集已开放，详情请访问：https://github.com/GeoX-Lab/RS-GPT4V。

> The remote sensing image intelligence understanding model is undergoing a new profound paradigm shift which has been promoted by multi-modal large language model (MLLM), i.e. from the paradigm learning a domain model (LaDM) shifts to paradigm learning a pre-trained general foundation model followed by an adaptive domain model (LaGD). Under the new LaGD paradigm, the old datasets, which have led to advances in RSI intelligence understanding in the last decade, are no longer suitable for fire-new tasks. We argued that a new dataset must be designed to lighten tasks with the following features: 1) Generalization: training model to learn shared knowledge among tasks and to adapt to different tasks; 2) Understanding complex scenes: training model to understand the fine-grained attribute of the objects of interest, and to be able to describe the scene with natural language; 3) Reasoning: training model to be able to realize high-level visual reasoning. In this paper, we designed a high-quality, diversified, and unified multimodal instruction-following dataset for RSI understanding produced by GPT-4V and existing datasets, which we called RS-GPT4V. To achieve generalization, we used a (Question, Answer) which was deduced from GPT-4V via instruction-following to unify the tasks such as captioning and localization; To achieve complex scene, we proposed a hierarchical instruction description with local strategy in which the fine-grained attributes of the objects and their spatial relationships are described and global strategy in which all the local information are integrated to yield detailed instruction descript; To achieve reasoning, we designed multiple-turn QA pair to provide the reasoning ability for a model. The empirical results show that the fine-tuned MLLMs by RS-GPT4V can describe fine-grained information. The dataset is available at: https://github.com/GeoX-Lab/RS-GPT4V.

![RS-GPT4V：遥感图像理解领域的统一多模态指令遵循数据集](../../../paper_images/2406.12479/pyramid.png)

![RS-GPT4V：遥感图像理解领域的统一多模态指令遵循数据集](../../../paper_images/2406.12479/principle.png)

![RS-GPT4V：遥感图像理解领域的统一多模态指令遵循数据集](../../../paper_images/2406.12479/main.png)

![RS-GPT4V：遥感图像理解领域的统一多模态指令遵循数据集](../../../paper_images/2406.12479/caption.png)

![RS-GPT4V：遥感图像理解领域的统一多模态指令遵循数据集](../../../paper_images/2406.12479/vqa.png)

![RS-GPT4V：遥感图像理解领域的统一多模态指令遵循数据集](../../../paper_images/2406.12479/llava.png)

[Arxiv](https://arxiv.org/abs/2406.12479)