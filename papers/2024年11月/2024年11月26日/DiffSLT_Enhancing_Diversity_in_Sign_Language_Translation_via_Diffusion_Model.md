# DiffSLT：借由扩散模型提升手语翻译的多样性

发布时间：2024年11月26日

`LLM应用` `手语翻译` `机器翻译`

> DiffSLT: Enhancing Diversity in Sign Language Translation via Diffusion Model

# 摘要

> 手语翻译（SLT）颇具挑战性，因其要把手语视频转化为自然语言。过往研究更看重准确性而非多样性。然而，多样性对于处理机器翻译中的词汇和句法歧义极为关键，这意味着它对手语翻译可能同样有益。在本项工作中，我们提出了 DiffSLT，这是一个新颖的无标注手语翻译框架，借助扩散模型，既能保留手语语义，又能实现多样化翻译。DiffSLT 以输入视频的视觉特征为条件，将随机噪声转化为目标潜在表示。为强化视觉条件，我们设计了指导融合模块，充分利用视觉特征的多层次时空信息。我们还引入了 DiffSLT-P，这是 DiffSLT 的一个变体，以伪标注和视觉特征为条件，提供关键的文本引导并缩小模态差距。正因如此，DiffSLT 和 DiffSLT-P 大幅提升了相较于以往无标注手语翻译方法的多样性，并在两个手语翻译数据集上取得了最先进的性能，显著提高了翻译质量。

> Sign language translation (SLT) is challenging, as it involves converting sign language videos into natural language. Previous studies have prioritized accuracy over diversity. However, diversity is crucial for handling lexical and syntactic ambiguities in machine translation, suggesting it could similarly benefit SLT. In this work, we propose DiffSLT, a novel gloss-free SLT framework that leverages a diffusion model, enabling diverse translations while preserving sign language semantics. DiffSLT transforms random noise into the target latent representation, conditioned on the visual features of input video. To enhance visual conditioning, we design Guidance Fusion Module, which fully utilizes the multi-level spatiotemporal information of the visual features. We also introduce DiffSLT-P, a DiffSLT variant that conditions on pseudo-glosses and visual features, providing key textual guidance and reducing the modality gap. As a result, DiffSLT and DiffSLT-P significantly improve diversity over previous gloss-free SLT methods and achieve state-of-the-art performance on two SLT datasets, thereby markedly improving translation quality.

[Arxiv](https://arxiv.org/abs/2411.17248)