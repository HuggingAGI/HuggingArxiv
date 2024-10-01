# CLIP-MoE：通过多样化多重升级，构建专家混合模型

发布时间：2024年09月28日

`LLM应用` `人工智能` `计算机视觉`

> CLIP-MoE: Towards Building Mixture of Experts for CLIP with Diversified Multiplet Upcycling

# 摘要

> 近年来，对比语言-图像预训练 (CLIP) 已成为多模态智能的基石。然而，最新研究发现，CLIP 在编码过程中存在显著的信息损失，且倾向于捕捉粗粒度特征，这限制了其处理细节丰富的图像的能力。为此，我们提出了多样化多重升级 (DMU) 策略，通过微调一系列捕捉不同特征空间的 CLIP 模型，从密集预训练的 CLIP 检查点中提取，共享除前馈网络 (FFN) 外的参数，从而将这些模型转换为具有更大容量的 CLIP-MoE，显著提升性能且计算开销最小。据我们所知，DMU 是首次将稀疏激活的 MoE 引入 CLIP 基础模型的方法。实验证明，CLIP-MoE 在零样本检索、分类及下游多模态大语言模型 (MLLM) 基准测试中表现优异。此外，DMU 使任何密集 CLIP 模型都能转换为 CLIP-MoE，无缝替换下游框架中的 CLIP，无需额外适应。通过 DMU，我们希望为未来开发更高效的多模态学习系统提供新思路。

> In recent years, Contrastive Language-Image Pre-training (CLIP) has become a cornerstone in multimodal intelligence. However, recent studies have identified that the information loss in the CLIP encoding process is substantial, and CLIP tends to capture only coarse-grained features from the input. This deficiency significantly limits the ability of a single CLIP model to handle images rich in visual detail. In this work, we propose a simple yet effective model-agnostic strategy, Diversified Multiplet Upcycling (DMU), for CLIP. DMU efficiently fine-tunes a series of CLIP models that capture different feature spaces, from a dense pre-trained CLIP checkpoint, sharing parameters except for the Feed-Forward Network (FFN). These models can then be transformed into a CLIP-MoE with a larger model capacity, leading to significantly enhanced performance with minimal computational overhead. To the best of our knowledge, Diversified Multiplet Upcycling is the first approach to introduce sparsely activated MoE into CLIP foundation models. Extensive experiments demonstrate the significant performance of CLIP-MoE across various zero-shot retrieval, zero-shot image classification tasks, and downstream Multimodal Large Language Model (MLLM) benchmarks by serving as a vision encoder. Furthermore, Diversified Multiplet Upcycling enables the conversion of any dense CLIP model into CLIP-MoEs, which can seamlessly replace CLIP in a plug-and-play manner without requiring further adaptation in downstream frameworks. Through Diversified Multiplet Upcycling, we aim to provide valuable insights for future research on developing more efficient and effective multimodal learning systems.

[Arxiv](https://arxiv.org/abs/2409.19291)