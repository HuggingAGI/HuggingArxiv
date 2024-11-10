# VQA$^2$:用于视频质量评估的视觉问答

发布时间：2024年11月06日

`LLM应用` `计算机视觉`

> VQA$^2$:Visual Question Answering for Video Quality Assessment

# 摘要

> 大型多模态模型（LMMs）的出现和扩散为视频相关的计算机视觉领域引入了一种新范式，包括基于视觉问答（VQA）的训练和推理方法。这些方法使模型能够稳健地处理多个下游任务。视频质量评估（VQA）是低级视觉质量评估中的一个经典领域，最初专注于定量的视频质量评分。然而，在大型多模态模型的推动下，它现在正朝着更全面的视觉质量理解任务发展。视觉问答最近在图像领域显著改善了低级视觉评估。然而，在视频领域相关工作几乎不存在，留下了很大的改进空间。为了解决这个差距，我们引入了 VQA2 指令数据集，这是第一个完全专注于视频质量评估的视觉问答指令数据集，并基于它，我们提出了 VQA2 系列模型。VQA2 指令数据集由三个阶段组成，涵盖各种视频类型，包含 157,735 个指令问答对，包括手动注释和合成数据。我们在视频质量评分和视频质量理解任务上进行了广泛的实验。结果表明，VQA2 系列模型在质量评分任务中达到了最先进（SOTA）的性能，并且它们在视觉质量问答中的表现超过了著名的 GPT-4o。此外，我们的最终模型 VQA2-Assistant 在评分和问答任务中都表现出色，验证了其通用性。

> The advent and proliferation of large multi-modal models (LMMs) have introduced a new paradigm to video-related computer vision fields, including training and inference methods based on visual question answering (VQA). These methods enable models to handle multiple downstream tasks robustly. Video Quality Assessment (VQA), a classic field in low-level visual quality evaluation, originally focused on quantitative video quality scoring. However, driven by advances in LMMs, it is now evolving towards more comprehensive visual quality understanding tasks. Visual question answering has significantly improved low-level visual evaluation within the image domain recently. However, related work is almost nonexistent in the video domain, leaving substantial room for improvement. To address this gap, we introduce the VQA2 Instruction Dataset the first visual question answering instruction dataset entirely focuses on video quality assessment, and based on it, we propose the VQA2 series models The VQA2 Instruction Dataset consists of three stages and covers various video types, containing 157,735 instruction question-answer pairs, including both manually annotated and synthetic data. We conduct extensive experiments on both video quality scoring and video quality understanding tasks. Results demonstrate that the VQA2 series models achieve state-of-the-art (SOTA) performance in quality scoring tasks, and their performance in visual quality question answering surpasses the renowned GPT-4o. Additionally, our final model, the VQA2-Assistant, performs well across both scoring and question-answering tasks, validating its versatility.

[Arxiv](https://arxiv.org/abs/2411.03795)