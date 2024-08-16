# 提升对比语言与音频预训练中的多粒度对齐技术

发布时间：2024年08月15日

`LLM应用

解释：这篇论文讨论了音频-语言联合学习模型（如 CLAP）在多模态理解任务中的应用，并提出了一种改进方法来增强音频和语言之间的对齐。这涉及到语言模型（LLM）在多模态场景中的应用，特别是在提高模型性能和可解释性方面。因此，它属于LLM应用分类。` `音频处理` `语言技术`

> Advancing Multi-grained Alignment for Contrastive Language-Audio Pre-training

# 摘要

> 近期，音频-语言联合学习如 CLAP 在多模态理解任务中大放异彩。这些模型通过对比损失将单模态局部特征聚合为全局表示，实现粗粒度跨模态对齐。但帧级与文本的对应常被忽略，影响可解释性和细粒度任务。我们研究旨在通过共享码本和局部感知块，以及硬负样本引导损失，改进音频-语言对齐的粗细粒度。实验证明，我们的模型在多个任务上不仅超越了 CLAP，还与顶尖模型不相上下。

> Recent advances have been witnessed in audio-language joint learning, such as CLAP, that shows much success in multi-modal understanding tasks. These models usually aggregate uni-modal local representations, namely frame or word features, into global ones, on which the contrastive loss is employed to reach coarse-grained cross-modal alignment. However, frame-level correspondence with texts may be ignored, making it ill-posed on explainability and fine-grained challenges which may also undermine performances on coarse-grained tasks. In this work, we aim to improve both coarse- and fine-grained audio-language alignment in large-scale contrastive pre-training. To unify the granularity and latent distribution of two modalities, a shared codebook is adopted to represent multi-modal global features with common bases, and each codeword is regularized to encode modality-shared semantics, bridging the gap between frame and word features. Based on it, a locality-aware block is involved to purify local patterns, and a hard-negative guided loss is devised to boost alignment. Experiments on eleven zero-shot coarse- and fine-grained tasks suggest that our model not only surpasses the baseline CLAP significantly but also yields superior or competitive results compared to current SOTA works.

[Arxiv](https://arxiv.org/abs/2408.07919)