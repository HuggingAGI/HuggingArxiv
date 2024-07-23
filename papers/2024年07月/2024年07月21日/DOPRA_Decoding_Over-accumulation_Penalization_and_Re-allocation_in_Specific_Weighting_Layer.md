# DOPRA：特定权重层中的过度累积惩罚与重新分配解码

发布时间：2024年07月21日

`LLM应用` `人工智能` `计算机视觉`

> DOPRA: Decoding Over-accumulation Penalization and Re-allocation in Specific Weighting Layer

# 摘要

> 我们推出的 DOPRA 方法，通过解码特定层加权惩罚和重新分配，有效减轻了多模态大型语言模型中的幻觉问题，无需额外资源，既经济又高效。DOPRA 深入分析了模型过度依赖自注意力矩阵中部分摘要令牌的问题，特别是在某些层级，通过在解码时对特定层（如第 12 层）实施加权叠加惩罚和重新分配，以及回顾性令牌分配，确保生成内容更贴合实际图像，显著提升了 MLLM 的输出质量。

> In this work, we introduce DOPRA, a novel approach designed to mitigate hallucinations in multi-modal large language models (MLLMs). Unlike existing solutions that typically involve costly supplementary training data or the integration of external knowledge sources, DOPRA innovatively addresses hallucinations by decoding specific weighted layer penalties and redistribution, offering an economical and effective solution without additional resources. DOPRA is grounded in unique insights into the intrinsic mechanisms controlling hallucinations within MLLMs, especially the models' tendency to over-rely on a subset of summary tokens in the self-attention matrix, neglecting critical image-related information. This phenomenon is particularly pronounced in certain strata. To counteract this over-reliance, DOPRA employs a strategy of weighted overlay penalties and redistribution in specific layers, such as the 12th layer, during the decoding process. Furthermore, DOPRA includes a retrospective allocation process that re-examines the sequence of generated tokens, allowing the algorithm to reallocate token selection to better align with the actual image content, thereby reducing the incidence of hallucinatory descriptions in auto-generated captions. Overall, DOPRA represents a significant step forward in improving the output quality of MLLMs by systematically reducing hallucinations through targeted adjustments during the decoding process.

![DOPRA：特定权重层中的过度累积惩罚与重新分配解码](../../../paper_images/2407.15130/x1.png)

![DOPRA：特定权重层中的过度累积惩罚与重新分配解码](../../../paper_images/2407.15130/attn_3.png)

![DOPRA：特定权重层中的过度累积惩罚与重新分配解码](../../../paper_images/2407.15130/x2.png)

![DOPRA：特定权重层中的过度累积惩罚与重新分配解码](../../../paper_images/2407.15130/x3.png)

![DOPRA：特定权重层中的过度累积惩罚与重新分配解码](../../../paper_images/2407.15130/x4.png)

![DOPRA：特定权重层中的过度累积惩罚与重新分配解码](../../../paper_images/2407.15130/x5.png)

[Arxiv](https://arxiv.org/abs/2407.15130)