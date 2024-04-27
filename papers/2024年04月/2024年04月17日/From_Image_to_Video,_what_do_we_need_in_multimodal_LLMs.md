# 探索从静态图像到动态视频的转变，我们需明确多模态大型语言模型所需具备的关键要素。

发布时间：2024年04月17日

`LLM应用` `计算机视觉` `人工智能`

> From Image to Video, what do we need in multimodal LLMs?

# 摘要

> 多模态大型语言模型（MLLMs）在处理多模态信息方面展现出了非凡的洞察力，从图像语言模型（Image LLMs）到更为复杂的视频语言模型（Video LLMs）均有涉猎。大量研究已经证明了它们在跨模态理解上的卓越能力。最近，提出了结合视频基础模型与大型语言模型，以构建一个全面的视频理解系统，旨在突破特定预设视觉任务的限制。然而，当前视频LLMs的发展往往忽略了图像LLMs的基石作用，倾向于采用更复杂的结构和多样化的多模态数据进行预训练，这大幅提高了相关方法的成本。为应对这些挑战，本研究提出了一种高效的方法，它巧妙地利用了图像LLMs的已有优势，以资源节约的方式实现从图像LLMs向视频LLMs的转变。我们介绍了RED-VILLM，这是一个高效的视频LLMs开发流程，它基于图像LLMs，采用了时间适应性的即插即用结构，扩展了对时间信息的理解能力，从而开发出不仅性能超越基准，而且使用最少的指导数据和训练资源的视频LLMs。我们的方法展现了在多模态模型领域实现成本效益更高、更具扩展性进步的可能性，为图像LLMs的基石工作提供了有效的延伸。

> Multimodal Large Language Models (MLLMs) have demonstrated profound capabilities in understanding multimodal information, covering from Image LLMs to the more complex Video LLMs. Numerous studies have illustrated their exceptional cross-modal comprehension. Recently, integrating video foundation models with large language models to build a comprehensive video understanding system has been proposed to overcome the limitations of specific pre-defined vision tasks. However, the current advancements in Video LLMs tend to overlook the foundational contributions of Image LLMs, often opting for more complicated structures and a wide variety of multimodal data for pre-training. This approach significantly increases the costs associated with these methods.In response to these challenges, this work introduces an efficient method that strategically leverages the priors of Image LLMs, facilitating a resource-efficient transition from Image to Video LLMs. We propose RED-VILLM, a Resource-Efficient Development pipeline for Video LLMs from Image LLMs, which utilizes a temporal adaptation plug-and-play structure within the image fusion module of Image LLMs. This adaptation extends their understanding capabilities to include temporal information, enabling the development of Video LLMs that not only surpass baseline performances but also do so with minimal instructional data and training resources. Our approach highlights the potential for a more cost-effective and scalable advancement in multimodal models, effectively building upon the foundational work of Image LLMs.

![探索从静态图像到动态视频的转变，我们需明确多模态大型语言模型所需具备的关键要素。](../../../paper_images/2404.11865/pipeline_v4.png)

![探索从静态图像到动态视频的转变，我们需明确多模态大型语言模型所需具备的关键要素。](../../../paper_images/2404.11865/pooling_v2.png)

[Arxiv](https://arxiv.org/abs/2404.11865)