# 通过“指定与编辑”，我们致力于解决基于文本的图像编辑中的歧义问题。

发布时间：2024年07月29日

`LLM应用` `图像编辑` `人工智能`

> Specify and Edit: Overcoming Ambiguity in Text-Based Image Editing

# 摘要

> 当用户输入指令模糊时，基于文本的编辑扩散模型性能受限。为此，我们引入了 $\textit{Specify ANd Edit}$ (SANE)，一种零-shot 推理流程，专为基于扩散的编辑系统设计。通过利用大型语言模型 (LLM)，我们将模糊指令细化成具体操作，确保对图像的编辑精准满足用户需求。得益于创新的去噪引导技术，我们不仅优化了原始指令，还提升了编辑过程的透明度和结果的多样性。实验证明，SANE 在多种场景下均表现出色。此外，我们的方法适用于各类编辑任务，无论指令是否模糊。代码已公开，详见 https://github.com/fabvio/SANE。

> Text-based editing diffusion models exhibit limited performance when the user's input instruction is ambiguous. To solve this problem, we propose $\textit{Specify ANd Edit}$ (SANE), a zero-shot inference pipeline for diffusion-based editing systems. We use a large language model (LLM) to decompose the input instruction into specific instructions, i.e. well-defined interventions to apply to the input image to satisfy the user's request. We benefit from the LLM-derived instructions along the original one, thanks to a novel denoising guidance strategy specifically designed for the task. Our experiments with three baselines and on two datasets demonstrate the benefits of SANE in all setups. Moreover, our pipeline improves the interpretability of editing models, and boosts the output diversity. We also demonstrate that our approach can be applied to any edit, whether ambiguous or not. Our code is public at https://github.com/fabvio/SANE.

[Arxiv](https://arxiv.org/abs/2407.20232)