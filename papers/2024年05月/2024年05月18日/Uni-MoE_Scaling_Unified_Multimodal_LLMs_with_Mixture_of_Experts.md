# Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型

发布时间：2024年05月18日

`LLM应用

理由：这篇论文主要探讨了多模态大型语言模型（MLLMs）的构建和优化，特别是通过引入混合专家（MoE）架构来处理多种模态数据。论文的重点在于模型的应用和性能提升，包括模态特定编码器和连接器的使用，以及稀疏MoE架构的引入，这些都是为了提高模型的效率和泛化能力。此外，论文还介绍了渐进式训练策略和在多模态数据集上的评估结果，这些都是模型应用层面的内容。因此，这篇论文更适合归类于LLM应用。` `人工智能` `多模态学习`

> Uni-MoE: Scaling Unified Multimodal LLMs with Mixture of Experts

# 摘要

> 近期，多模态大型语言模型（MLLMs）的发展突显了模型和数据的可扩展性对性能提升的重要性，但这也带来了高昂的计算成本。尽管混合专家（MoE）架构已被用于优化大型语言和图像-文本模型的扩展，但这些尝试通常涉及的专家数量有限，模态也较为单一。为此，我们首次尝试构建一个名为Uni-MoE的统一MLLM，采用MoE架构，能处理多种模态。该模型特有模态特定编码器和连接器，以实现统一的跨模态表示。我们还引入了稀疏MoE架构，通过模态级数据并行和专家级模型并行，实现高效训练和推理。为提升多专家协作与泛化能力，我们提出了一种渐进式训练策略：首先进行跨模态对齐，然后训练模态特定专家以激活其偏好，最后利用低秩适应（LoRA）在混合多模态指令数据上调优Uni-MoE。我们在多个多模态数据集上评估了Uni-MoE，结果显示其在处理混合多模态数据时显著减少了性能偏差，并增强了多专家协作与泛化能力。我们的研究凸显了MoE框架在推动MLLMs发展中的巨大潜力，相关代码已公开在https://github.com/HITsz-TMG/UMOE-Scaling-Unified-Multimodal-LLMs。

> Recent advancements in Multimodal Large Language Models (MLLMs) underscore the significance of scalable models and data to boost performance, yet this often incurs substantial computational costs. Although the Mixture of Experts (MoE) architecture has been employed to efficiently scale large language and image-text models, these efforts typically involve fewer experts and limited modalities. To address this, our work presents the pioneering attempt to develop a unified MLLM with the MoE architecture, named Uni-MoE that can handle a wide array of modalities. Specifically, it features modality-specific encoders with connectors for a unified multimodal representation. We also implement a sparse MoE architecture within the LLMs to enable efficient training and inference through modality-level data parallelism and expert-level model parallelism. To enhance the multi-expert collaboration and generalization, we present a progressive training strategy: 1) Cross-modality alignment using various connectors with different cross-modality data, 2) Training modality-specific experts with cross-modality instruction data to activate experts' preferences, and 3) Tuning the Uni-MoE framework utilizing Low-Rank Adaptation (LoRA) on mixed multimodal instruction data. We evaluate the instruction-tuned Uni-MoE on a comprehensive set of multimodal datasets. The extensive experimental results demonstrate Uni-MoE's principal advantage of significantly reducing performance bias in handling mixed multimodal datasets, alongside improved multi-expert collaboration and generalization. Our findings highlight the substantial potential of MoE frameworks in advancing MLLMs and the code is available at https://github.com/HITsz-TMG/UMOE-Scaling-Unified-Multimodal-LLMs.

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/moe_intro.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/model.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/loss_curve.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/cap_image_text_v1.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/cap_text_audio_v1.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/cap_text_video_v1.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/cap_image_audio_v1.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/cap_text_video_audio_v1.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/cap_image_text_v2.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/cap_text_audio_v2.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/cap_text_video_v2.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/cap_image_audio_v2.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/cap_text_video_audio_v2.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/cap_image_text_v3.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/cap_text_audio_v3.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/cap_text_video_v3.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/cap_image_audio_v3.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/cap_text_video_audio_v3.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/case_figure.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/cappre_image_text_v1.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/cappre_text_audio_v1.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/cappre_text_video_v1.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/cappre_image_audio_v1.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/cappre_text_video_audio_v1.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/speech_image_text_v1.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/speech_text_audio_v1.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/speech_text_video_v1.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/speech_image_audio_v1.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/speech_text_video_audio_v1.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/cappre_image_text_v2.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/cappre_text_audio_v2.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/cappre_text_video_v2.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/cappre_image_audio_v2.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/cappre_text_video_audio_v2.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/speech_image_text_v2.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/speech_text_audio_v2.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/speech_text_video_v2.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/speech_image_audio_v2.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/speech_text_video_audio_v2.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/cappre_image_text_v3.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/cappre_text_audio_v3.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/cappre_text_video_v3.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/cappre_image_audio_v3.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/cappre_text_video_audio_v3.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/speech_image_text_v3.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/speech_text_audio_v3.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/speech_text_video_v3.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/speech_image_audio_v3.png)

![Uni-MoE：借助专家混合技术，扩展统一多模态大型语言模型](../../../paper_images/2405.11273/speech_text_video_audio_v3.png)

[Arxiv](https://arxiv.org/abs/2405.11273)