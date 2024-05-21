# 利用多模态CLIP推理进行元少样本图像分类研究

发布时间：2024年03月26日

`LLM应用

这篇论文探讨了大型语言与视觉模型（如CLIP）在少样本分类任务中的应用，特别是在元少样本学习测试中的表现。论文通过实证研究展示了CLIP模型在无需额外训练的情况下，如何超越了顶尖的元少样本学习模型。这一发现不仅验证了多模态模型的潜力和稳健性，也为未来利用此类模型的研究提供了基础。因此，这篇论文属于LLM应用分类，因为它关注的是大型语言模型在实际应用中的性能和效果。` `元学习` `多模态学习`

> Multimodal CLIP Inference for Meta-Few-Shot Image Classification

# 摘要

> 近期文献中，少样本分类多被视为N-way k-shot元学习问题。这些模型通常在特定条件下训练，旨在标准测试中脱颖而出，且不依赖外部数据。随着大型语言与视觉模型的进步，一个疑问浮现：这些模型能否直接在元少样本学习测试中大放异彩？特别是像CLIP这样的多模态模型，它们通过学习图像与文本的联合嵌入，展现出独特魅力。多模态训练确实增强了模型应对模糊性的能力，这在少样本学习中尤为关键。本研究显示，CLIP的文本与图像编码器结合，在无需额外训练的情况下，已在广泛认可的基准测试中超越了顶尖的元少样本学习模型。我们的发现不仅验证了CLIP等多模态模型的潜力与稳健性，也为未来利用此类模型的研究奠定了基石。

> In recent literature, few-shot classification has predominantly been defined by the N-way k-shot meta-learning problem. Models designed for this purpose are usually trained to excel on standard benchmarks following a restricted setup, excluding the use of external data. Given the recent advancements in large language and vision models, a question naturally arises: can these models directly perform well on meta-few-shot learning benchmarks? Multimodal foundation models like CLIP, which learn a joint (image, text) embedding, are of particular interest. Indeed, multimodal training has proven to enhance model robustness, especially regarding ambiguities, a limitation frequently observed in the few-shot setup. This study demonstrates that combining modalities from CLIP's text and image encoders outperforms state-of-the-art meta-few-shot learners on widely adopted benchmarks, all without additional training. Our results confirm the potential and robustness of multimodal foundation models like CLIP and serve as a baseline for existing and future approaches leveraging such models.

[Arxiv](https://arxiv.org/abs/2405.10954)