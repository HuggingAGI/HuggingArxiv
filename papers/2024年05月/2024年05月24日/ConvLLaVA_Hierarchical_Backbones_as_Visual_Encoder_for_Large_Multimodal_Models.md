# ConvLLaVA：大型多模态模型的视觉编码器——层次化骨干网络

发布时间：2024年05月24日

`LLM应用

理由：这篇论文主要讨论了高分辨率大型多模态模型（LMMs）在处理视觉信息时的效率问题，并提出了一种新的模型ConvLLaVA来解决视觉令牌的冗余和计算负担问题。该研究关注的是LLM在实际应用中的性能优化，特别是在多模态处理方面的应用，因此属于LLM应用类别。` `计算机视觉` `图像处理`

> ConvLLaVA: Hierarchical Backbones as Visual Encoder for Large Multimodal Models

# 摘要

> 高分辨率大型多模态模型（LMMs）常受视觉令牌过多和视觉复杂度二次方之困。尽管现有模型已解决二次方复杂度，但视觉令牌的冗余问题依旧突出，导致计算负担加重。为此，我们研发了ConvLLaVA，采用ConvNeXt作为视觉编码器，替代传统的Vision Transformer（ViT），有效压缩高分辨率图像至富含信息的视觉特征，避免了视觉令牌的过度生成。为提升ConvLLaVA性能，我们实施了两项关键优化：一是更新低分辨率预训练的ConvNeXt，以适应高分辨率需求；二是增加连续训练阶段，进一步压缩视觉令牌，减少冗余。这些改进使ConvLLaVA能处理1536x1536分辨率的输入，仅产生576个视觉令牌，适应各种宽高比图像。实验证明，我们的方法在主流基准上与顶尖模型并驾齐驱。ConvLLaVA模型系列已公开于https://github.com/alibaba/conv-llava。

> High-resolution Large Multimodal Models (LMMs) encounter the challenges of excessive visual tokens and quadratic visual complexity. Current high-resolution LMMs address the quadratic complexity while still generating excessive visual tokens. However, the redundancy in visual tokens is the key problem as it leads to more substantial compute. To mitigate this issue, we propose ConvLLaVA, which employs ConvNeXt, a hierarchical backbone, as the visual encoder of LMM to replace Vision Transformer (ViT). ConvLLaVA compresses high-resolution images into information-rich visual features, effectively preventing the generation of excessive visual tokens. To enhance the capabilities of ConvLLaVA, we propose two critical optimizations. Since the low-resolution pretrained ConvNeXt underperforms when directly applied on high resolution, we update it to bridge the gap. Moreover, since ConvNeXt's original compression ratio is inadequate for much higher resolution inputs, we train a successive stage to further compress the visual tokens, thereby reducing redundancy. These optimizations enable ConvLLaVA to support inputs of 1536x1536 resolution generating only 576 visual tokens, capable of handling images of arbitrary aspect ratios. Experimental results demonstrate that our method achieves competitive performance with state-of-the-art models on mainstream benchmarks. The ConvLLaVA model series are publicly available at https://github.com/alibaba/conv-llava.

![ConvLLaVA：大型多模态模型的视觉编码器——层次化骨干网络](../../../paper_images/2405.15738/x1.png)

![ConvLLaVA：大型多模态模型的视觉编码器——层次化骨干网络](../../../paper_images/2405.15738/x2.png)

[Arxiv](https://arxiv.org/abs/2405.15738)