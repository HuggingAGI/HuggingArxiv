# 本文介绍了一种具有泛化持续学习能力的可扩展语言模型。

发布时间：2024年04月11日

`LLM理论` `持续学习` `语言模型`

> Scalable Language Model with Generalized Continual Learning

# 摘要

> 持续学习正受到越来越多的关注，因为它能够有效地提升语言模型的知识和技能。然而，在现实应用中，传统方法常常面临诸多挑战，比如过度依赖经验回放、优化限制以及任务ID推断等问题。本研究提出了一种新型的可扩展语言模型（SLM），旨在在一个更具挑战性和普遍性的环境中克服这些限制，为持续学习的实际应用迈出了重要一步。我们特别设计了联合自适应重参数化（JARe）技术，并结合动态任务相关知识检索（DTKR），使得语言模型能够根据不同的下游任务进行自适应调整。这种方法通过在向量空间内分布任务，力求实现一个流畅且无缝的持续学习体验。我们的方法在多种基础架构和基准测试中均展现出卓越的性能，无论是在全数据集还是小样本情境下，都能实现高效的持续学习，同时最大程度地减少遗忘。此外，与以往主要关注单一任务类型如分类的研究不同，我们的研究扩展到了多个领域和任务类型，利用大型语言模型LLaMA-2，探索了其在广泛应用中的潜力和效果。

> Continual learning has gained increasing importance as it facilitates the acquisition and refinement of scalable knowledge and skills in language models. However, existing methods typically encounter strict limitations and challenges in real-world scenarios, such as reliance on experience replay, optimization constraints, and inference task-ID. In this study, we introduce the Scalable Language Model (SLM) to overcome these limitations within a more challenging and generalized setting, representing a significant advancement toward practical applications for continual learning. Specifically, we propose the Joint Adaptive Re-Parameterization (JARe), integrated with Dynamic Task-related Knowledge Retrieval (DTKR), to enable adaptive adjustment of language models based on specific downstream tasks. This approach leverages the task distribution within the vector space, aiming to achieve a smooth and effortless continual learning process. Our method demonstrates state-of-the-art performance on diverse backbones and benchmarks, achieving effective continual learning in both full-set and few-shot scenarios with minimal forgetting. Moreover, while prior research primarily focused on a single task type such as classification, our study goes beyond, with the large language model, i.e., LLaMA-2, to explore the effects across diverse domains and task types, such that a single language model can be decently scaled to broader applications.

![本文介绍了一种具有泛化持续学习能力的可扩展语言模型。](../../../paper_images/2404.07470/x1.png)

![本文介绍了一种具有泛化持续学习能力的可扩展语言模型。](../../../paper_images/2404.07470/x2.png)

![本文介绍了一种具有泛化持续学习能力的可扩展语言模型。](../../../paper_images/2404.07470/x3.png)

![本文介绍了一种具有泛化持续学习能力的可扩展语言模型。](../../../paper_images/2404.07470/x5.png)

![本文介绍了一种具有泛化持续学习能力的可扩展语言模型。](../../../paper_images/2404.07470/x6.png)

![本文介绍了一种具有泛化持续学习能力的可扩展语言模型。](../../../paper_images/2404.07470/x7.png)

![本文介绍了一种具有泛化持续学习能力的可扩展语言模型。](../../../paper_images/2404.07470/x8.png)

![本文介绍了一种具有泛化持续学习能力的可扩展语言模型。](../../../paper_images/2404.07470/x9.png)

![本文介绍了一种具有泛化持续学习能力的可扩展语言模型。](../../../paper_images/2404.07470/x10.png)

![本文介绍了一种具有泛化持续学习能力的可扩展语言模型。](../../../paper_images/2404.07470/x11.png)

![本文介绍了一种具有泛化持续学习能力的可扩展语言模型。](../../../paper_images/2404.07470/x12.png)

![本文介绍了一种具有泛化持续学习能力的可扩展语言模型。](../../../paper_images/2404.07470/x13.png)

![本文介绍了一种具有泛化持续学习能力的可扩展语言模型。](../../../paper_images/2404.07470/x14.png)

![本文介绍了一种具有泛化持续学习能力的可扩展语言模型。](../../../paper_images/2404.07470/x15.png)

![本文介绍了一种具有泛化持续学习能力的可扩展语言模型。](../../../paper_images/2404.07470/x16.png)

![本文介绍了一种具有泛化持续学习能力的可扩展语言模型。](../../../paper_images/2404.07470/x17.png)

![本文介绍了一种具有泛化持续学习能力的可扩展语言模型。](../../../paper_images/2404.07470/x18.png)

![本文介绍了一种具有泛化持续学习能力的可扩展语言模型。](../../../paper_images/2404.07470/x19.png)

[Arxiv](https://arxiv.org/abs/2404.07470)