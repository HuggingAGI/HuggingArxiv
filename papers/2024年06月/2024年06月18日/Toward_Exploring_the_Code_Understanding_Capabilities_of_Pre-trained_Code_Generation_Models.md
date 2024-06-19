# 探究预训练代码生成模型对代码的理解力

发布时间：2024年06月18日

`Agent

理由：这篇论文主要探讨了如何将预训练的代码生成模型的知识迁移到代码理解任务中，具体通过引入一种对比学习方法（CL4D）来增强仅解码器模型的表示能力，从而在代码搜索和克隆检测等任务上取得显著效果。这种方法涉及到模型的应用和改进，但更侧重于模型作为一个智能体（Agent）在特定任务（代码理解）中的应用和优化，而不是理论研究或LLM的通用应用。因此，将其归类为Agent更为合适。` `软件开发` `代码分析`

> Toward Exploring the Code Understanding Capabilities of Pre-trained Code Generation Models

# 摘要

> 近期，通过自监督学习在海量未标记编程语言数据上训练的大型代码生成模型取得了显著成就。尽管这些模型积累了丰富的代码知识，但在代码理解任务，如代码搜索和克隆检测上表现欠佳，因为其训练重点在于生成。从头开始预训练一个庞大的仅编码器模型虽能提升理解性能，但成本高昂且耗时。本文中，我们率先将预训练代码生成模型的知识迁移至代码理解任务，大幅降低训练成本。我们探讨了如何让仅解码器模型获得强健的代码表示，并引入了CL4D这一对比学习方法，以增强仅解码器模型的表示能力。实验证明，我们的方法在代码搜索和克隆检测等任务上达到了业界领先水平，有效缩短了语义相同样本在表示空间中的距离。这表明，采用仅解码器结构的模型有望统一代码理解和生成任务。

> Recently, large code generation models trained in a self-supervised manner on extensive unlabeled programming language data have achieved remarkable success. While these models acquire vast amounts of code knowledge, they perform poorly on code understanding tasks, such as code search and clone detection, as they are specifically trained for generation. Pre-training a larger encoder-only architecture model from scratch on massive code data can improve understanding performance. However, this approach is costly and time-consuming, making it suboptimal. In this paper, we pioneer the transfer of knowledge from pre-trained code generation models to code understanding tasks, significantly reducing training costs. We examine effective strategies for enabling decoder-only models to acquire robust code representations. Furthermore, we introduce CL4D, a contrastive learning method designed to enhance the representation capabilities of decoder-only models. Comprehensive experiments demonstrate that our approach achieves state-of-the-art performance in understanding tasks such as code search and clone detection. Our analysis shows that our method effectively reduces the distance between semantically identical samples in the representation space. These findings suggest the potential for unifying code understanding and generation tasks using a decoder-only structured model.

![探究预训练代码生成模型对代码的理解力](../../../paper_images/2406.12326/model_size.png)

![探究预训练代码生成模型对代码的理解力](../../../paper_images/2406.12326/last.png)

![探究预训练代码生成模型对代码的理解力](../../../paper_images/2406.12326/average.png)

![探究预训练代码生成模型对代码的理解力](../../../paper_images/2406.12326/dual-encoder.png)

![探究预训练代码生成模型对代码的理解力](../../../paper_images/2406.12326/wo_CL4D_CSN.png)

![探究预训练代码生成模型对代码的理解力](../../../paper_images/2406.12326/wo_CL4D_CoSQA.png)

![探究预训练代码生成模型对代码的理解力](../../../paper_images/2406.12326/wo_CL4D_POJ.png)

![探究预训练代码生成模型对代码的理解力](../../../paper_images/2406.12326/w_CL4D_CSN.png)

![探究预训练代码生成模型对代码的理解力](../../../paper_images/2406.12326/w_CL4D_CoSQA.png)

![探究预训练代码生成模型对代码的理解力](../../../paper_images/2406.12326/w_CL4D_POJ.png)

[Arxiv](https://arxiv.org/abs/2406.12326)