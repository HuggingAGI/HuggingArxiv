# 双耳全开：探索语言驱动的空间音频生成

发布时间：2024年10月14日

`其他` `音频生成` `虚拟现实`

> Both Ears Wide Open: Towards Language-Driven Spatial Audio Generation

# 摘要

> 近期，扩散模型在单声道音频生成领域大放异彩。然而，面对立体声音频生成，复杂的声景——多对象、多方向——使得空间上下文的控制变得棘手，高昂的数据成本与不稳定的生成模型更是雪上加霜。本研究首开先河，直面这些挑战。我们精心打造了BEWO-1M数据集，这是一个大规模、模拟驱动、GPT助力的宝库，声景丰富，描述详尽，甚至涵盖移动与多源场景。不仅如此，我们还通过检索技术，为文本之外的图像模态匹配了立体声音频，助力多模态生成更上一层楼。现有音频生成模型往往空间感模糊，随机性大。为此，我们创新推出SpatialSonic模型，借助空间感知编码器与方位角状态矩阵，为潜在扩散模型提供精准空间指引。这一创新不仅让我们的模型能从文本与图像中生成沉浸式、可控的空间音频，更在推理过程中实现了音频生成的互动性。最终，在公正的评估环境下，我们通过模拟与真实数据的主客观测试，验证了本方法相较于主流技术的优越性，其生成的空间音频，物理规则严丝合缝。

> Recently, diffusion models have achieved great success in mono-channel audio generation. However, when it comes to stereo audio generation, the soundscapes often have a complex scene of multiple objects and directions. Controlling stereo audio with spatial contexts remains challenging due to high data costs and unstable generative models. To the best of our knowledge, this work represents the first attempt to address these issues. We first construct a large-scale, simulation-based, and GPT-assisted dataset, BEWO-1M, with abundant soundscapes and descriptions even including moving and multiple sources. Beyond text modality, we have also acquired a set of images and rationally paired stereo audios through retrieval to advance multimodal generation. Existing audio generation models tend to generate rather random and indistinct spatial audio. To provide accurate guidance for latent diffusion models, we introduce the SpatialSonic model utilizing spatial-aware encoders and azimuth state matrices to reveal reasonable spatial guidance. By leveraging spatial guidance, our unified model not only achieves the objective of generating immersive and controllable spatial audio from text and image but also enables interactive audio generation during inference. Finally, under fair settings, we conduct subjective and objective evaluations on simulated and real-world data to compare our approach with prevailing methods. The results demonstrate the effectiveness of our method, highlighting its capability to generate spatial audio that adheres to physical rules.

[Arxiv](https://arxiv.org/abs/2410.10676)