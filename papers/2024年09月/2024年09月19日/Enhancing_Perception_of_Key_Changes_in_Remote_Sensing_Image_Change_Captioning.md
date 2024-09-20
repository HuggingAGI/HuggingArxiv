# 提升遥感图像变化描述中关键变化的感知能力

发布时间：2024年09月19日

`LLM应用` `地理信息系统`

> Enhancing Perception of Key Changes in Remote Sensing Image Change Captioning

# 摘要

> 近期，遥感图像变化描述虽有进展，但现有方法未能有效过滤无关区域，导致模型易受干扰。为此，我们提出KCFI多模态框架，通过视觉指令与像素级检测，提升大型语言模型在变化特征上的表现。KCFI包含ViTs编码器、关键特征感知器、像素级检测解码器及指令调优解码器，并采用动态权重策略优化任务。实验表明，仅用关键变化特征指导模型效果最佳，在LEVIR-CC数据集上超越现有方法。代码即将在GitHub发布。

> Recently, while significant progress has been made in remote sensing image change captioning, existing methods fail to filter out areas unrelated to actual changes, making models susceptible to irrelevant features. In this article, we propose a novel multimodal framework for remote sensing image change captioning, guided by Key Change Features and Instruction-tuned (KCFI). This framework aims to fully leverage the intrinsic knowledge of large language models through visual instructions and enhance the effectiveness and accuracy of change features using pixel-level change detection tasks. Specifically, KCFI includes a ViTs encoder for extracting bi-temporal remote sensing image features, a key feature perceiver for identifying critical change areas, a pixel-level change detection decoder to constrain key change features, and an instruction-tuned decoder based on a large language model. Moreover, to ensure that change description and change detection tasks are jointly optimized, we employ a dynamic weight-averaging strategy to balance the losses between the two tasks. We also explore various feature combinations for visual fine-tuning instructions and demonstrate that using only key change features to guide the large language model is the optimal choice. To validate the effectiveness of our approach, we compare it against several state-of-the-art change captioning methods on the LEVIR-CC dataset, achieving the best performance. Our code will be available at https://github.com/yangcong356/KCFI.git.

[Arxiv](https://arxiv.org/abs/2409.12612)