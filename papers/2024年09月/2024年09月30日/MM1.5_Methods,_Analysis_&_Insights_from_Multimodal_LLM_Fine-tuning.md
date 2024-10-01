# MM1.5：多模态 LLM 微调的策略、分析与洞察

发布时间：2024年09月30日

`LLM应用` `人工智能` `多媒体`

> MM1.5: Methods, Analysis & Insights from Multimodal LLM Fine-tuning

# 摘要

> 我们推出了 MM1.5，这是一系列多模态大型语言模型，旨在提升文本图像理解、视觉定位和多图像推理的能力。基于 MM1 架构，MM1.5 采用数据驱动的方法，全面探索了训练过程中数据多样性的影响。我们的模型规模从 1B 到 30B 参数不等，包括密集和专家混合变体，证明了即使在较小规模下，精心设计的数据策略也能带来卓越性能。此外，我们还推出了 MM1.5-Video 和 MM1.5-UI 两个专业版本，分别针对视频和移动界面理解。通过详尽的实验和分析，我们揭示了训练过程中的关键决策，为未来的 MLLM 研究提供了重要参考。

> We present MM1.5, a new family of multimodal large language models (MLLMs) designed to enhance capabilities in text-rich image understanding, visual referring and grounding, and multi-image reasoning. Building upon the MM1 architecture, MM1.5 adopts a data-centric approach to model training, systematically exploring the impact of diverse data mixtures across the entire model training lifecycle. This includes high-quality OCR data and synthetic captions for continual pre-training, as well as an optimized visual instruction-tuning data mixture for supervised fine-tuning. Our models range from 1B to 30B parameters, encompassing both dense and mixture-of-experts (MoE) variants, and demonstrate that careful data curation and training strategies can yield strong performance even at small scales (1B and 3B). Additionally, we introduce two specialized variants: MM1.5-Video, designed for video understanding, and MM1.5-UI, tailored for mobile UI understanding. Through extensive empirical studies and ablations, we provide detailed insights into the training processes and decisions that inform our final designs, offering valuable guidance for future research in MLLM development.

[Arxiv](https://arxiv.org/abs/2409.20566)