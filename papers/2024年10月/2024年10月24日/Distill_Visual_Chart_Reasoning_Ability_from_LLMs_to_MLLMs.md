# 从大型语言模型（LLMs）向多语言大型语言模型（MLLMs）提炼视觉图表推理能力

发布时间：2024年10月24日

`LLM应用` `图表问答` `数据合成`

> Distill Visual Chart Reasoning Ability from LLMs to MLLMs

# 摘要

> 解决复杂的图表问答任务需要多模态大型语言模型（MLLMs）具备先进的视觉推理能力。最近的研究强调，这些能力主要由两部分组成：从视觉输入中识别关键信息并对其进行推理。因此，增强 MLLMs 的一个有前途的方法是构建侧重于这两个方面的相关训练数据。然而，收集和标注复杂的图表和问题既昂贵又耗时，并且确保标注答案的质量仍然是一个挑战。在本文中，我们提出了代码作为中介翻译（CIT），这是一种经济高效、易于扩展的数据合成方法，用于将大型语言模型（LLMs）的视觉推理能力提炼到 MLLMs 中。代码充当将视觉图表表示转换为文本表示的中介，使 LLM 能够理解跨模态信息。具体来说，我们采用基于文本的合成技术来构建图表绘制代码，并生成 ReachQA，这是一个包含 3k 个推理密集型图表和 20k 个问答对的数据集，以增强识别和推理能力。实验表明，当使用我们的数据进行微调时，模型不仅在与图表相关的基准测试中表现良好，而且在像 MathVista 这样的一般数学基准测试中也展示出改进的多模态推理能力。代码和数据集可在 https://github.com/hewei2001/ReachQA 公开获取。

> Solving complex chart Q&A tasks requires advanced visual reasoning abilities in multimodal large language models (MLLMs). Recent studies highlight that these abilities consist of two main parts: recognizing key information from visual inputs and conducting reasoning over it. Thus, a promising approach to enhance MLLMs is to construct relevant training data focusing on the two aspects. However, collecting and annotating complex charts and questions is costly and time-consuming, and ensuring the quality of annotated answers remains a challenge. In this paper, we propose Code-as-Intermediary Translation (CIT), a cost-effective, efficient and easily scalable data synthesis method for distilling visual reasoning abilities from LLMs to MLLMs. The code serves as an intermediary that translates visual chart representations into textual representations, enabling LLMs to understand cross-modal information. Specifically, we employ text-based synthesizing techniques to construct chart-plotting code and produce ReachQA, a dataset containing 3k reasoning-intensive charts and 20k Q&A pairs to enhance both recognition and reasoning abilities. Experiments show that when fine-tuned with our data, models not only perform well on chart-related benchmarks, but also demonstrate improved multimodal reasoning abilities on general mathematical benchmarks like MathVista. The code and dataset are publicly available at https://github.com/hewei2001/ReachQA.

[Arxiv](https://arxiv.org/abs/2410.18798)