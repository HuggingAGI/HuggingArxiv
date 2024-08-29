# Whisper-PMFA：利用 Whisper 模型进行演讲者验证的部分多尺度特征聚合技术

发布时间：2024年08月28日

`LLM应用` `语音识别` `说话人验证`

> Whisper-PMFA: Partial Multi-Scale Feature Aggregation for Speaker Verification using Whisper Models

# 摘要

> 本文引入了 Whisper 这一大规模预训练模型，旨在自动语音识别领域应用于说话人验证。我们创新性地提出了 PMFA 方法，通过 Whisper 编码器块的子集，提取出极具辨识度的说话人嵌入。实验显示，采用 Whisper 编码器的中后期块能更有效地保留说话人特征。在 VoxCeleb1 与 CN-Celeb1 数据集上，我们的系统分别实现了 1.42% 和 8.23% 的 EER，较 ECAPA-TDNN 和 ResNet34 基线有显著提升。研究还发现，多语言数据训练的 Whisper 模型能大幅提升跨语言的鲁棒性。此外，低秩适应方法的应用，在大幅减少模型参数的同时，仅轻微增加了 EER。

> In this paper, Whisper, a large-scale pre-trained model for automatic speech recognition, is proposed to apply to speaker verification. A partial multi-scale feature aggregation (PMFA) approach is proposed based on a subset of Whisper encoder blocks to derive highly discriminative speaker embeddings.Experimental results demonstrate that using the middle to later blocks of the Whisper encoder keeps more speaker information. On the VoxCeleb1 and CN-Celeb1 datasets, our system achieves 1.42% and 8.23% equal error rates (EERs) respectively, receiving 0.58% and 1.81% absolute EER reductions over the ECAPA-TDNN baseline, and 0.46% and 0.97% over the ResNet34 baseline. Furthermore, our results indicate that using Whisper models trained on multilingual data can effectively enhance the model's robustness across languages. Finally, the low-rank adaptation approach is evaluated, which reduces the trainable model parameters by approximately 45 times while only slightly increasing EER by 0.2%.

[Arxiv](https://arxiv.org/abs/2408.15585)