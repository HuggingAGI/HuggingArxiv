# DEEM：扩散模型——大型语言模型感知图像的慧眼

发布时间：2024年05月24日

`LLM应用

这篇论文探讨了扩散模型在图像处理中的应用，特别是在增强大型语言模型（LLM）处理多模态数据时的鲁棒性和减少视觉幻觉的能力。通过提出的DEEM方法，论文展示了如何利用扩散模型的生成反馈来改进图像编码器的性能，从而提高模型对异常数据的处理能力。这种方法不需要额外的训练模块和大量参数，显示了在特定基准测试中的优越性能。因此，这篇论文属于LLM应用类别，因为它专注于实际应用中如何改进和增强LLM的功能。` `图像处理` `多模态学习`

> DEEM: Diffusion Models Serve as the Eyes of Large Language Models for Image Perception

# 摘要

> 大型语言模型的发展催生了大型多模态模型的兴起。虽然多模态模型在促进理解和创造的协同方面取得了显著成就，但面对分布外的数据时，它们往往力不从心。这主要是因为它们依赖于将图像转化为任务相关特征的图像编码器，可能会忽略掉无关的细节。本文探讨了扩散模型在图像处理中的潜力，并提出一个问题：扩散模型是否能成为大型语言模型的“视觉之眼”？我们提出的DEEM方法，通过利用扩散模型的生成反馈，有效对齐图像编码器的语义分布，克服了仅依赖图像编码器（如ViT）的局限，增强了模型对异常数据的抵抗力，减少了视觉幻觉，且无需额外训练模块和大量参数。在RobustVQA和POPE两个基准测试中，DEEM展现了优于现有模型的鲁棒性和幻觉缓解能力，同时减少了训练参数和预训练数据的需求。

> The development of large language models (LLMs) has significantly advanced the emergence of large multimodal models (LMMs). While LMMs have achieved tremendous success by promoting the synergy between multimodal comprehension and creation, they often face challenges when confronted with out-of-distribution data. This is primarily due to their reliance on image encoders trained to encode images into task-relevant features, which may lead them to disregard irrelevant details. Delving into the modeling capabilities of diffusion models for images naturally prompts the question: Can diffusion models serve as the eyes of large language models for image perception? In this paper, we propose DEEM, a simple and effective approach that utilizes the generative feedback of diffusion models to align the semantic distributions of the image encoder. This addresses the drawbacks of previous methods that solely relied on image encoders like ViT, thereby enhancing the model's resilience against out-of-distribution samples and reducing visual hallucinations. Importantly, this is achieved without requiring additional training modules and with fewer training parameters. We extensively evaluated DEEM on both our newly constructed RobustVQA benchmark and another well-known benchmark, POPE, for object hallucination. Compared to the state-of-the-art interleaved content generation models, DEEM exhibits enhanced robustness and a superior capacity to alleviate model hallucinations while utilizing fewer trainable parameters, less pre-training data (10%), and a smaller base model size.

![DEEM：扩散模型——大型语言模型感知图像的慧眼](../../../paper_images/2405.15232/x2.png)

![DEEM：扩散模型——大型语言模型感知图像的慧眼](../../../paper_images/2405.15232/x3.png)

![DEEM：扩散模型——大型语言模型感知图像的慧眼](../../../paper_images/2405.15232/x4.png)

![DEEM：扩散模型——大型语言模型感知图像的慧眼](../../../paper_images/2405.15232/x5.png)

![DEEM：扩散模型——大型语言模型感知图像的慧眼](../../../paper_images/2405.15232/x6.png)

![DEEM：扩散模型——大型语言模型感知图像的慧眼](../../../paper_images/2405.15232/x7.png)

![DEEM：扩散模型——大型语言模型感知图像的慧眼](../../../paper_images/2405.15232/x8.png)

![DEEM：扩散模型——大型语言模型感知图像的慧眼](../../../paper_images/2405.15232/x9.png)

![DEEM：扩散模型——大型语言模型感知图像的慧眼](../../../paper_images/2405.15232/x10.png)

![DEEM：扩散模型——大型语言模型感知图像的慧眼](../../../paper_images/2405.15232/x11.png)

![DEEM：扩散模型——大型语言模型感知图像的慧眼](../../../paper_images/2405.15232/x12.png)

[Arxiv](https://arxiv.org/abs/2405.15232)