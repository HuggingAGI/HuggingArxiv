# 利用多模态CLIP推理进行元少样本图像分类研究

发布时间：2024年03月26日

`LLM应用

这篇论文摘要讨论了大型语言和视觉模型（如CLIP）在少样本分类任务中的应用，特别是在元少样本学习测试中的表现。它展示了这些多模态模型如何通过学习图像与文本的联合嵌入，在无需额外训练的情况下，超越现有的元少样本学习模型。这表明了大型语言模型在实际应用中的潜力和鲁棒性，因此属于LLM应用分类。` `元学习` `多模态学习`

> Multimodal CLIP Inference for Meta-Few-Shot Image Classification

# 摘要

> 近期文献中，少样本分类多被视为N-way k-shot元学习问题。这些模型通常在特定条件下训练，以在标准测试中表现卓越，且不依赖外部数据。随着大型语言和视觉模型的进步，一个疑问浮现：这些模型能否直接在元少样本学习测试中大放异彩？特别是像CLIP这样的多模态模型，通过学习图像与文本的联合嵌入，引起了广泛关注。多模态训练已被证实能增强模型在模糊情况下的鲁棒性，这在少样本学习中尤为关键。本研究显示，CLIP的文本与图像编码器结合，在无需额外训练的情况下，已在多个广泛认可的基准测试中超越了现有的元少样本学习模型。这一成果不仅验证了CLIP等多模态模型的潜力与稳健性，也为未来利用此类模型的研究奠定了基础。

> In recent literature, few-shot classification has predominantly been defined by the N-way k-shot meta-learning problem. Models designed for this purpose are usually trained to excel on standard benchmarks following a restricted setup, excluding the use of external data. Given the recent advancements in large language and vision models, a question naturally arises: can these models directly perform well on meta-few-shot learning benchmarks? Multimodal foundation models like CLIP, which learn a joint (image, text) embedding, are of particular interest. Indeed, multimodal training has proven to enhance model robustness, especially regarding ambiguities, a limitation frequently observed in the few-shot setup. This study demonstrates that combining modalities from CLIP's text and image encoders outperforms state-of-the-art meta-few-shot learners on widely adopted benchmarks, all without additional training. Our results confirm the potential and robustness of multimodal foundation models like CLIP and serve as a baseline for existing and future approaches leveraging such models.

[Arxiv](https://arxiv.org/abs/2405.10954)