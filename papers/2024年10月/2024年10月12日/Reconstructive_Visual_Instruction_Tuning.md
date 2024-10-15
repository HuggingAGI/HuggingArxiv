# 视觉指令的重构调整

发布时间：2024年10月12日

`LLM应用` `计算机视觉` `人工智能`

> Reconstructive Visual Instruction Tuning

# 摘要

> 本文介绍的重建视觉指令调优（ROSS），通过利用视觉为中心的监督信号，改进了大型多模态模型（LMMs）的表现。与仅关注文本输出的传统方法不同，ROSS 通过重建输入图像来监督视觉输出，从而保留了图像的丰富细节。然而，从自然图像中提取有意义的反馈因其高空间冗余而颇具挑战。为此，ROSS 采用去噪目标重建图像的潜在表示，避免了直接处理原始 RGB 值。这种设计不仅增强了模型的细粒度理解能力，还减少了幻觉现象。实验证明，ROSS 在不同视觉编码器和语言模型中均表现出色。与依赖多个视觉专家的外部辅助方法相比，ROSS 仅凭单一 SigLIP 视觉编码器便能与之匹敌，彰显了其以视觉为中心的监督策略的卓越效果。

> This paper introduces reconstructive visual instruction tuning (ROSS), a family of Large Multimodal Models (LMMs) that exploit vision-centric supervision signals. In contrast to conventional visual instruction tuning approaches that exclusively supervise text outputs, ROSS prompts LMMs to supervise visual outputs via reconstructing input images. By doing so, it capitalizes on the inherent richness and detail present within input images themselves, which are often lost in pure text supervision. However, producing meaningful feedback from natural images is challenging due to the heavy spatial redundancy of visual signals. To address this issue, ROSS employs a denoising objective to reconstruct latent representations of input images, avoiding directly regressing exact raw RGB values. This intrinsic activation design inherently encourages LMMs to maintain image detail, thereby enhancing their fine-grained comprehension capabilities and reducing hallucinations. Empirically, ROSS consistently brings significant improvements across different visual encoders and language models. In comparison with extrinsic assistance state-of-the-art alternatives that aggregate multiple visual experts, ROSS delivers competitive performance with a single SigLIP visual encoder, demonstrating the efficacy of our vision-centric supervision tailored for visual outputs.

[Arxiv](https://arxiv.org/abs/2410.09575)