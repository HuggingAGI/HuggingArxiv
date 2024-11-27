# LLMs 能够在模态方面持续演进，以用于 X 模态推理

发布时间：2024年10月26日

`LLM应用` `多模态` `持续学习`

> LLMs Can Evolve Continually on Modality for X-Modal Reasoning

# 摘要

> 多模态大型语言模型（MLLMs）因在多模态理解上的出色能力而备受瞩目。但现有方法过度依赖大量特定模态的预训练和联合模态调整，在拓展新模态时会产生极大的计算负担。本文中，我们提出了 PathWeave，这是一个具备模态路径切换与扩展能力的灵活可扩展框架，能让 MLLMs 在模态上持续进化以进行 $\mathbb{X}$ 模态推理。我们借助持续学习的理念，在预训练的 MLLMs 基础上开发了增量训练策略，使其能利用单模态数据拓展到新模态，无需进行联合模态预训练。具体而言，引入了新颖的“Adapter-in-Adapter（AnA）”框架，单模态和跨模态适配器无缝融合，利于高效的模态对齐与协作。此外，在两类适配器之间应用了基于 MoE 的门控模块，进一步增强多模态交互。为探究所提方法，我们构建了一个颇具挑战的基准——模态持续学习（MCL），它包含来自图像、视频、音频、深度和点云这五个不同模态的高质量问答数据。大量实验表明，所提出的 AnA 框架在持续学习中的学习可塑性和记忆稳定性方面效果显著。而且，PathWeave 的表现与最先进的 MLLMs 相当，同时将参数训练负担降低了 98.73％。我们的代码位于 https://github.com/JiazuoYu/PathWeave

> Multimodal Large Language Models (MLLMs) have gained significant attention due to their impressive capabilities in multimodal understanding. However, existing methods rely heavily on extensive modal-specific pretraining and joint-modal tuning, leading to significant computational burdens when expanding to new modalities. In this paper, we propose PathWeave, a flexible and scalable framework with modal-Path sWitching and ExpAnsion abilities that enables MLLMs to continually EVolve on modalities for $\mathbb{X}$-modal reasoning. We leverage the concept of Continual Learning and develop an incremental training strategy atop pre-trained MLLMs, enabling their expansion to new modalities using uni-modal data, without executing joint-modal pretraining. In detail, a novel Adapter-in-Adapter (AnA) framework is introduced, in which uni-modal and cross-modal adapters are seamlessly integrated to facilitate efficient modality alignment and collaboration. Additionally, an MoE-based gating module is applied between two types of adapters to further enhance the multimodal interaction. To investigate the proposed method, we establish a challenging benchmark called Continual Learning of Modality (MCL), which consists of high-quality QA data from five distinct modalities: image, video, audio, depth and point cloud. Extensive experiments demonstrate the effectiveness of the proposed AnA framework on learning plasticity and memory stability during continual learning. Furthermore, PathWeave performs comparably to state-of-the-art MLLMs while concurrently reducing parameter training burdens by 98.73%. Our code locates at https://github.com/JiazuoYu/PathWeave

[Arxiv](https://arxiv.org/abs/2410.20178)