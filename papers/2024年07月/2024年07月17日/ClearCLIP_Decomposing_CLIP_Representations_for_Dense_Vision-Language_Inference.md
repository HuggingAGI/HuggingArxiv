# ClearCLIP：解析 CLIP 表征，助力密集视觉-语言推理

发布时间：2024年07月17日

`LLM应用` `计算机视觉` `语义分割`

> ClearCLIP: Decomposing CLIP Representations for Dense Vision-Language Inference

# 摘要

> 尽管CLIP等大规模预训练视觉-语言模型在开放词汇任务中表现出色，但在语义分割领域仍面临挑战，常产生含噪声的分割图。本文深入分析CLIP架构，发现残差连接是主要噪声源。通过对比分析，揭示CLIP的图像-文本对比训练偏重全局特征而忽视局部细节，影响分割质量。为此，我们创新提出ClearCLIP方法，通过调整CLIP表示结构，优化分割效果。具体措施包括移除残差连接、引入自注意力机制及简化前馈网络。实验证明，ClearCLIP能生成更清晰准确的分割图，并在多基准测试中领先，凸显了研究的重要性。

> Despite the success of large-scale pretrained Vision-Language Models (VLMs) especially CLIP in various open-vocabulary tasks, their application to semantic segmentation remains challenging, producing noisy segmentation maps with mis-segmented regions. In this paper, we carefully re-investigate the architecture of CLIP, and identify residual connections as the primary source of noise that degrades segmentation quality. With a comparative analysis of statistical properties in the residual connection and the attention output across different pretrained models, we discover that CLIP's image-text contrastive training paradigm emphasizes global features at the expense of local discriminability, leading to noisy segmentation results. In response, we propose ClearCLIP, a novel approach that decomposes CLIP's representations to enhance open-vocabulary semantic segmentation. We introduce three simple modifications to the final layer: removing the residual connection, implementing the self-self attention, and discarding the feed-forward network. ClearCLIP consistently generates clearer and more accurate segmentation maps and outperforms existing approaches across multiple benchmarks, affirming the significance of our discoveries.

![ClearCLIP：解析 CLIP 表征，助力密集视觉-语言推理](../../../paper_images/2407.12442/Ablation_clip_b16_each.png)

![ClearCLIP：解析 CLIP 表征，助力密集视觉-语言推理](../../../paper_images/2407.12442/Ablation_openclip_b16_each.png)

![ClearCLIP：解析 CLIP 表征，助力密集视觉-语言推理](../../../paper_images/2407.12442/Ablation_clip_L14_each.png)

![ClearCLIP：解析 CLIP 表征，助力密集视觉-语言推理](../../../paper_images/2407.12442/Ablation_openclip_l14_each.png)

![ClearCLIP：解析 CLIP 表征，助力密集视觉-语言推理](../../../paper_images/2407.12442/feature_maps1.jpg)

![ClearCLIP：解析 CLIP 表征，助力密集视觉-语言推理](../../../paper_images/2407.12442/feature_maps2.jpg)

![ClearCLIP：解析 CLIP 表征，助力密集视觉-语言推理](../../../paper_images/2407.12442/vis_cocostuff.jpg)

![ClearCLIP：解析 CLIP 表征，助力密集视觉-语言推理](../../../paper_images/2407.12442/vis_ade.jpg)

![ClearCLIP：解析 CLIP 表征，助力密集视觉-语言推理](../../../paper_images/2407.12442/vis_context59.jpg)

[Arxiv](https://arxiv.org/abs/2407.12442)