# Croc：借助跨模态理解，预训练大型多模态模型

发布时间：2024年10月18日

`LLM应用` `人工智能` `计算机视觉`

> Croc: Pretraining Large Multimodal Models with Cross-Modal Comprehension

# 摘要

> 大型语言模型 (LLM) 的进步推动了大型多模态模型 (LMM) 的发展。然而，现有研究多聚焦于语言和图像指令的调整，却忽视了模型学习处理文本和视觉模态联合的关键预训练阶段。为此，我们提出了一种新的 LMM 预训练范式，通过引入跨模态理解阶段，增强 LLM 的视觉理解能力。我们设计了动态可学习的提示词池，并运用匈牙利算法优化视觉词的替换。同时，将视觉词视为 LLM 的“外语”，提出混合注意力机制，全面提升视觉词的理解。此外，通过详细的字幕生成任务，进一步促进 LLM 对视觉语义信息的理解。在 150 万公开数据上预训练后，我们推出了新模型 Croc，其在视觉语言基准测试中表现卓越。为支持研究和可重复性，我们在 https://github.com/deepglint/Croc 上发布了相关资源。

> Recent advances in Large Language Models (LLMs) have catalyzed the development of Large Multimodal Models (LMMs). However, existing research primarily focuses on tuning language and image instructions, ignoring the critical pretraining phase where models learn to process textual and visual modalities jointly. In this paper, we propose a new pretraining paradigm for LMMs to enhance the visual comprehension capabilities of LLMs by introducing a novel cross-modal comprehension stage. Specifically, we design a dynamically learnable prompt token pool and employ the Hungarian algorithm to replace part of the original visual tokens with the most relevant prompt tokens. Then, we conceptualize visual tokens as analogous to a "foreign language" for the LLMs and propose a mixed attention mechanism with bidirectional visual attention and unidirectional textual attention to comprehensively enhance the understanding of visual tokens. Meanwhile, we integrate a detailed caption generation task, leveraging rich descriptions to further facilitate LLMs in understanding visual semantic information. After pretraining on 1.5 million publicly accessible data, we present a new foundation model called Croc. Experimental results demonstrate that Croc achieves new state-of-the-art performance on massive vision-language benchmarks. To support reproducibility and facilitate further research, we release the training code and pre-trained model weights at https://github.com/deepglint/Croc.

[Arxiv](https://arxiv.org/abs/2410.14332)