# Harlequin：用于指称表达理解的由颜色驱动的合成数据生成

发布时间：2024年11月22日

`LLM应用` `视觉语言` `数据标注`

> Harlequin: Color-driven Generation of Synthetic Data for Referring Expression Comprehension

# 摘要

> 指称表达理解（REC）旨在凭借自然语言表述在场景里识别特定对象，是视觉语言理解的重要课题。此任务的前沿方法基于深度学习，往往需要昂贵且人工标注的注释。有些工作借助有限监督学习或依赖大型视觉和语言模型来应对问题。然而，合成标注数据的技术发展却被忽略了。在本文中，我们提出一个为REC任务生成人工数据的全新框架，兼顾了文本和视觉模态。首先，我们的流程处理现有数据以创造注释的变化。接着，它以修改后的注释为指引生成图像。该流程的成果是一个新的数据集，名为Harlequin，由超百万个查询构成。这种方式免除了手动的数据收集和标注，实现了可扩展性，也促进了任意的复杂性。我们在Harlequin上预训练了三个REC模型，然后在人工标注的数据集上进行微调并评估。我们的实验表明，在人工数据上的预训练对性能有益。

> Referring Expression Comprehension (REC) aims to identify a particular object in a scene by a natural language expression, and is an important topic in visual language understanding. State-of-the-art methods for this task are based on deep learning, which generally requires expensive and manually labeled annotations. Some works tackle the problem with limited-supervision learning or relying on Large Vision and Language Models. However, the development of techniques to synthesize labeled data is overlooked. In this paper, we propose a novel framework that generates artificial data for the REC task, taking into account both textual and visual modalities. At first, our pipeline processes existing data to create variations in the annotations. Then, it generates an image using altered annotations as guidance. The result of this pipeline is a new dataset, called Harlequin, made by more than 1M queries. This approach eliminates manual data collection and annotation, enabling scalability and facilitating arbitrary complexity. We pre-train three REC models on Harlequin, then fine-tuned and evaluated on human-annotated datasets. Our experiments show that the pre-training on artificial data is beneficial for performance.

[Arxiv](https://arxiv.org/abs/2411.14807)