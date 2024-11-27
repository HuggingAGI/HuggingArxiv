# MotionLLaMA：运动合成与理解的统一框架

发布时间：2024年11月26日

`LLM应用` `语言模型`

> MotionLLaMA: A Unified Framework for Motion Synthesis and Comprehension

# 摘要

> 本文介绍了 MotionLLaMA，这是用于动作合成与理解的统一框架，还有名为 HoMi Tokenizer 的全新全身动作标记器。MotionLLaMA 基于三大核心原则开发而成。其一，借由 HoMi Tokenizer 构建起强大的统一表示空间。在 MotionLLaMA 中，使用单个码本的 HoMi Tokenizer 能实现与采用六个码本的残差向量量化标记器相当的重建精度，胜过所有现有的单个码本标记器。其二，MotionLLaMA 整合了大型语言模型以处理各类与动作相关的任务。这种整合打通了各种模式，有利于全面且复杂的动作合成与理解。其三，MotionLLaMA 引入了 MotionHub 数据集，这是当下最为广泛的多模态、多任务动作数据集，能够对大型语言模型进行微调。大量实验结果表明，MotionLLaMA 不但涵盖了最广泛的动作相关任务，而且在动作完成、交互双人文本转动作以及所有理解任务中达到了最先进水平，在其余任务中的表现也与最先进水平相当。代码和 MotionHub 数据集均可公开获取。

> This paper introduces MotionLLaMA, a unified framework for motion synthesis and comprehension, along with a novel full-body motion tokenizer called the HoMi Tokenizer. MotionLLaMA is developed based on three core principles. First, it establishes a powerful unified representation space through the HoMi Tokenizer. Using a single codebook, the HoMi Tokenizer in MotionLLaMA achieves reconstruction accuracy comparable to residual vector quantization tokenizers utilizing six codebooks, outperforming all existing single-codebook tokenizers. Second, MotionLLaMA integrates a large language model to tackle various motion-related tasks. This integration bridges various modalities, facilitating both comprehensive and intricate motion synthesis and comprehension. Third, MotionLLaMA introduces the MotionHub dataset, currently the most extensive multimodal, multitask motion dataset, which enables fine-tuning of large language models. Extensive experimental results demonstrate that MotionLLaMA not only covers the widest range of motion-related tasks but also achieves state-of-the-art (SOTA) performance in motion completion, interaction dual-person text-to-motion, and all comprehension tasks while reaching performance comparable to SOTA in the remaining tasks. The code and MotionHub dataset are publicly available.

[Arxiv](https://arxiv.org/abs/2411.17335)