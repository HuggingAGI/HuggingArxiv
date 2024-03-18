# [VisionLLaMA 是一个为各类视觉任务打造的统一 LLaMA（大规模预训练语言模型）接口，旨在整合并发挥 LLama 在视觉领域的强大功能。](https://arxiv.org/abs/2403.00522)

发布时间：2024年03月01日

`LLM应用`

> VisionLLaMA: A Unified LLaMA Interface for Vision Tasks

> 基于Transformer架构的大型语言模型擅长处理文本信息，其中LLaMA是诸多开源实现中的佼佼者。而如今，我们尝试探索相同的Transformer架构是否也能应用于二维图像处理。本论文介绍了名为VisionLLaMA的独特视觉Transformer模型，它以平面和金字塔结构呈现，并专为此目标定制。VisionLLaMA提供了一个统一而通用的解决方案，足以应对多数视觉任务挑战。我们深入研究了VisionLLaMA在多个下游图像感知及特别是图像生成任务上的表现，通过标准预训练方式对其效果进行了广泛的验证。实验结果显示，在许多场景下，VisionLLaMA相较于现有的最先进视觉Transformer取得了显著的进步。因此，我们认为VisionLLaMA有望成为视觉生成与理解领域的一个强有力的新基准模型，相关代码将会在https://github.com/Meituan-AutoML/VisionLLaMA上公开发布。

> Large language models are built on top of a transformer-based architecture to process textual inputs. For example, the LLaMA stands out among many open-source implementations. Can the same transformer be used to process 2D images? In this paper, we answer this question by unveiling a LLaMA-like vision transformer in plain and pyramid forms, termed VisionLLaMA, which is tailored for this purpose. VisionLLaMA is a unified and generic modelling framework for solving most vision tasks. We extensively evaluate its effectiveness using typical pre-training paradigms in a good portion of downstream tasks of image perception and especially image generation. In many cases, VisionLLaMA have exhibited substantial gains over the previous state-of-the-art vision transformers. We believe that VisionLLaMA can serve as a strong new baseline model for vision generation and understanding. Our code will be released at https://github.com/Meituan-AutoML/VisionLLaMA.

[Arxiv](https://arxiv.org/abs/2403.00522)