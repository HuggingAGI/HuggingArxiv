# 多语言大型语言模型的密集连接器

发布时间：2024年05月22日

`RAG

理由：这篇论文主要探讨了多模态大型语言模型（MLLMs）中视觉编码器的潜能，并提出了一种名为“密集连接器”的视觉-语言连接器，以提升MLLMs的性能。这种连接器的设计和应用涉及到对多模态数据的处理和增强，特别是在视觉和语言模态之间的交互。这与RAG（Retrieval-Augmented Generation）的概念相符，其中“Retrieval-Augmented”指的是通过检索增强生成过程，而“Generation”则通常指语言模型的生成能力。在这篇论文中，通过密集连接器增强视觉特征的使用，可以看作是对生成过程的一种增强，尤其是在处理多模态数据时。因此，这篇论文更适合归类于RAG。` `人工智能` `多媒体处理`

> Dense Connector for MLLMs

# 摘要

> 我们是否已充分发掘多模态大型语言模型（MLLMs）中视觉编码器的潜能？MLLMs在多模态理解上的卓越表现近期备受瞩目。然而，在这场MLLM的竞赛中，焦点多集中在语言层面，如更大、更高质量的指令数据集和更大规模的LLMs。相比之下，MLLMs所依赖的视觉信号却鲜少被关注，通常仅被视为由冻结视觉编码器提取的高层特征。本文中，我们提出了一种名为“密集连接器”的视觉-语言连接器，它简单、高效且易于集成，通过利用多层视觉特征大幅提升了现有MLLMs的性能，且计算负担微乎其微。令人惊喜的是，我们的模型虽仅通过图像训练，却在视频理解上展现了卓越的零样本能力。在多种视觉编码器、图像分辨率、训练数据集规模、不同大小的LLMs及多样的MLLMs架构上进行的实验，均证实了我们方法的广泛适用性和可扩展性，使其在19个图像和视频基准测试中达到了业界领先水平。我们期望这项研究能为未来MLLM的发展提供重要参考，并成为其基础构建模块。

> Do we fully leverage the potential of visual encoder in Multimodal Large Language Models (MLLMs)? The recent outstanding performance of MLLMs in multimodal understanding has garnered broad attention from both academia and industry. In the current MLLM rat race, the focus seems to be predominantly on the linguistic side. We witness the rise of larger and higher-quality instruction datasets, as well as the involvement of larger-sized LLMs. Yet, scant attention has been directed towards the visual signals utilized by MLLMs, often assumed to be the final high-level features extracted by a frozen visual encoder. In this paper, we introduce the Dense Connector - a simple, effective, and plug-and-play vision-language connector that significantly enhances existing MLLMs by leveraging multi-layer visual features, with minimal additional computational overhead. Furthermore, our model, trained solely on images, showcases remarkable zero-shot capabilities in video understanding as well. Experimental results across various vision encoders, image resolutions, training dataset scales, varying sizes of LLMs (2.7B->70B), and diverse architectures of MLLMs (e.g., LLaVA and Mini-Gemini) validate the versatility and scalability of our approach, achieving state-of-the-art performance on across 19 image and video benchmarks. We hope that this work will provide valuable experience and serve as a basic module for future MLLM development.

[Arxiv](https://arxiv.org/abs/2405.13800)