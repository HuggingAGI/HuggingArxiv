# 借助潜在空间引导，减少视觉语言模型中的幻觉现象。

发布时间：2024年10月21日

`LLM应用` `计算机视觉` `人工智能`

> Reducing Hallucinations in Vision-Language Models via Latent Space Steering

# 摘要

> 幻觉问题对大型视觉语言模型 (LVLMs) 的应用部署构成了挑战。与大型语言模型 (LLMs) 不同，LVLMs 中的幻觉通常源于视觉与文本之间的不一致。本文深入探讨了幻觉的内在机制，特别关注了 LVLMs 的独特结构。我们发现，幻觉往往源于文本解码器对视觉输入的高度敏感，这在图像编码器和文本解码器分别预训练时尤为明显。基于此，我们提出了视觉和文本干预 (VTI) 技术，通过在推理过程中调整潜在空间表示，增强视觉特征的稳定性，从而减少幻觉。VTI 作为一种任务无关的测试时干预手段，无需额外成本即可轻松应用于各种问题。实验结果显示，VTI 能有效减少幻觉，并在多个指标上超越基线方法，凸显了视觉特征稳定性在 LVLMs 中的重要性。

> Hallucination poses a challenge to the deployment of large vision-language models (LVLMs) in applications. Unlike in large language models (LLMs), hallucination in LVLMs often arises from misalignments between visual inputs and textual outputs. This paper investigates the underlying mechanisms of hallucination, focusing on the unique structure of LVLMs that distinguishes them from large language models (LLMs). We identify that hallucinations often arise from the sensitivity of text decoders to vision inputs, a natural phenomenon when image encoders and text decoders are pre-trained separately. Inspired by this, we introduce Visual and Textual Intervention (VTI), a novel technique designed to reduce hallucinations by steering latent space representations during inference to enhance the stability of vision features. As a task-agnostic test-time intervention, VTI can be easily applied to any problem without additional cost. Extensive experiments demonstrate that it can effectively reduce hallucinations and outperform baseline methods across multiple metrics, highlighting the critical role of vision feature stability in LVLMs.

[Arxiv](https://arxiv.org/abs/2410.15778)