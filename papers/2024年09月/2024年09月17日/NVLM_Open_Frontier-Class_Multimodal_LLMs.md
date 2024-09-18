# NVLM：探索多模态大型语言模型的前沿

发布时间：2024年09月17日

`LLM应用` `人工智能` `计算机视觉`

> NVLM: Open Frontier-Class Multimodal LLMs

# 摘要

> 我们推出了 NVLM 1.0，这是一系列顶尖的多模态大型语言模型，在视觉-语言任务上表现卓越，与 GPT-4o 等专有模型和 Llama 3-V 405B 等开放模型不相上下。特别值得一提的是，NVLM 1.0 在多模态训练后，其纯文本性能甚至超越了其 LLM 基础模型。在模型设计上，我们深入比较了仅解码器模型和基于交叉注意力的模型，并据此提出了一种新架构，既提升了训练效率，又增强了多模态推理能力。此外，我们创新的 1-D 瓦片标记设计，大幅提升了高分辨率图像处理任务的性能。在数据方面，我们强调了数据质量和任务多样性的重要性，并为此精心策划了多模态预训练和微调数据集。我们还为 NVLM-1.0 打造了生产级的多模态能力，使其在视觉-语言任务中大放异彩，同时保持了出色的纯文本性能。为了进一步推动研究，我们不仅公开了模型权重，还将开源代码，详情请访问：https://nvlm-project.github.io/。

> We introduce NVLM 1.0, a family of frontier-class multimodal large language models (LLMs) that achieve state-of-the-art results on vision-language tasks, rivaling the leading proprietary models (e.g., GPT-4o) and open-access models (e.g., Llama 3-V 405B and InternVL 2). Remarkably, NVLM 1.0 shows improved text-only performance over its LLM backbone after multimodal training. In terms of model design, we perform a comprehensive comparison between decoder-only multimodal LLMs (e.g., LLaVA) and cross-attention-based models (e.g., Flamingo). Based on the strengths and weaknesses of both approaches, we propose a novel architecture that enhances both training efficiency and multimodal reasoning capabilities. Furthermore, we introduce a 1-D tile-tagging design for tile-based dynamic high-resolution images, which significantly boosts performance on multimodal reasoning and OCR-related tasks. Regarding training data, we meticulously curate and provide detailed information on our multimodal pretraining and supervised fine-tuning datasets. Our findings indicate that dataset quality and task diversity are more important than scale, even during the pretraining phase, across all architectures. Notably, we develop production-grade multimodality for the NVLM-1.0 models, enabling them to excel in vision-language tasks while maintaining and even improving text-only performance compared to their LLM backbones. To achieve this, we craft and integrate a high-quality text-only dataset into multimodal training, alongside a substantial amount of multimodal math and reasoning data, leading to enhanced math and coding capabilities across modalities. To advance research in the field, we are releasing the model weights and will open-source the code for the community: https://nvlm-project.github.io/.

[Arxiv](https://arxiv.org/abs/2409.11402)