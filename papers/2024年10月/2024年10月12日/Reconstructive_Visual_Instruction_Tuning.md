# 视觉指令的重建调优

发布时间：2024年10月12日

`LLM应用` `计算机视觉` `人工智能`

> Reconstructive Visual Instruction Tuning

# 摘要

> 本文提出重建视觉指令调优（ROSS），一种利用视觉监督信号的大型多模态模型（LMMs）。与仅监督文本的传统方法不同，ROSS 通过重建图像来监督视觉输出，保留了图像的丰富细节。然而，从自然图像中提取有意义反馈的挑战在于视觉信号的高度冗余。为此，ROSS 采用去噪目标重建图像潜在表示，避免直接处理原始 RGB 值，从而保持图像细节，提升细粒度理解能力，减少幻觉。实验证明，ROSS 在不同视觉编码器和语言模型中均带来显著改进。与依赖多视觉专家的外部辅助方法相比，ROSS 以单一 SigLIP 视觉编码器实现竞争性能，凸显了其视觉为中心监督方法的有效性。

> This paper introduces reconstructive visual instruction tuning (ROSS), a family of Large Multimodal Models (LMMs) that exploit vision-centric supervision signals. In contrast to conventional visual instruction tuning approaches that exclusively supervise text outputs, ROSS prompts LMMs to supervise visual outputs via reconstructing input images. By doing so, it capitalizes on the inherent richness and detail present within input images themselves, which are often lost in pure text supervision. However, producing meaningful feedback from natural images is challenging due to the heavy spatial redundancy of visual signals. To address this issue, ROSS employs a denoising objective to reconstruct latent representations of input images, avoiding directly regressing exact raw RGB values. This intrinsic activation design inherently encourages LMMs to maintain image detail, thereby enhancing their fine-grained comprehension capabilities and reducing hallucinations. Empirically, ROSS consistently brings significant improvements across different visual encoders and language models. In comparison with extrinsic assistance state-of-the-art alternatives that aggregate multiple visual experts, ROSS delivers competitive performance with a single SigLIP visual encoder, demonstrating the efficacy of our vision-centric supervision tailored for visual outputs.

[Arxiv](https://arxiv.org/abs/2410.09575)