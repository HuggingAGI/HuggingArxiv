# Face-MLLM：一个大型面部感知模型

发布时间：2024年10月28日

`LLM应用` `人脸感知` `多模态模型`

> Face-MLLM: A Large Face Perception Model

# 摘要

> 尽管多模态大型语言模型（MLLMs）在广泛的视觉语言任务中取得了有希望的结果，但它们感知和理解人脸的能力却很少被探索。在这项工作中，我们全面评估了现有的 MLLMs 在人脸感知任务上的表现。定量结果表明，现有的 MLLMs 难以处理这些任务。主要原因是缺乏包含人脸细粒度描述的图像 - 文本数据集。为了解决这个问题，我们设计了一个构建数据集的实用管道，在此基础上，我们进一步构建了一个新的多模态大型人脸感知模型，即 Face-MLLM。具体来说，我们用更详细的人脸描述和面部属性标签重新标注了 LAION-Face 数据集。此外，我们使用问答风格重新制定了传统的人脸数据集，这适合 MLLMs。连同这些丰富的数据集，我们开发了一种新颖的三阶段 MLLM 训练方法。在前两个阶段，我们的模型分别学习视觉 - 文本对齐和基本的视觉问答能力。在第三阶段，我们的模型学习处理多个专门的人脸感知任务。实验结果表明，我们的模型在五个著名的人脸感知任务上超过了以前的 MLLMs。此外，在我们新引入的零样本面部属性分析任务中，我们的 Face-MLLM 也表现出优越的性能。

> Although multimodal large language models (MLLMs) have achieved promising results on a wide range of vision-language tasks, their ability to perceive and understand human faces is rarely explored. In this work, we comprehensively evaluate existing MLLMs on face perception tasks. The quantitative results reveal that existing MLLMs struggle to handle these tasks. The primary reason is the lack of image-text datasets that contain fine-grained descriptions of human faces. To tackle this problem, we design a practical pipeline for constructing datasets, upon which we further build a novel multimodal large face perception model, namely Face-MLLM. Specifically, we re-annotate LAION-Face dataset with more detailed face captions and facial attribute labels. Besides, we re-formulate traditional face datasets using the question-answer style, which is fit for MLLMs. Together with these enriched datasets, we develop a novel three-stage MLLM training method. In the first two stages, our model learns visual-text alignment and basic visual question answering capability, respectively. In the third stage, our model learns to handle multiple specialized face perception tasks. Experimental results show that our model surpasses previous MLLMs on five famous face perception tasks. Besides, on our newly introduced zero-shot facial attribute analysis task, our Face-MLLM also presents superior performance.

[Arxiv](https://arxiv.org/abs/2410.20717)