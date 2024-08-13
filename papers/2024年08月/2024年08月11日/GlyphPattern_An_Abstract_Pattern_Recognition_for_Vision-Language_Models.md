# GlyphPattern：视觉-语言模型中的抽象模式识别技术

发布时间：2024年08月11日

`LLM应用` `人工智能`

> GlyphPattern: An Abstract Pattern Recognition for Vision-Language Models

# 摘要

> 基于大型语言模型的视觉-语言模型 (VLMs) 在跨视觉和文本数据的推理方面取得了显著进展。然而，我们的研究揭示了 VLMs 在抽象模式识别方面的关键挑战。为此，我们推出了 GlyphPattern 数据集，该数据集包含 954 个项目，结合了 40 种书写系统的 318 个视觉模式描述与三种视觉呈现方式。GlyphPattern 旨在测试 VLMs 对视觉模式的自然语言描述的理解和判断能力。这些模式源自对人类书写系统的大规模认知研究，因此在空间和组合性方面极为丰富。实验表明，即使是顶尖的 VLMs 也难以应对 GlyphPattern 的挑战（如 GPT-4o 准确率仅为 55%），且少量样本提示带来的改进有限。深入的错误分析显示，这一挑战涉及视觉处理、自然语言理解及模式泛化等多个层面。

> Vision-Language Models (VLMs) building upon the foundation of powerful large language models have made rapid progress in reasoning across visual and textual data. While VLMs perform well on vision tasks that they are trained on, our results highlight key challenges in abstract pattern recognition. We present GlyphPattern, a 954 item dataset that pairs 318 human-written descriptions of visual patterns from 40 writing systems with three visual presentation styles.
  GlyphPattern evaluates abstract pattern recognition in VLMs, requiring models to understand and judge natural language descriptions of visual patterns. GlyphPattern patterns are drawn from a large-scale cognitive science investigation of human writing systems; as a result, they are rich in spatial reference and compositionality. Our experiments show that GlyphPattern is challenging for state-of-the-art VLMs (GPT-4o achieves only 55% accuracy), with marginal gains from few-shot prompting. Our detailed error analysis reveals challenges at multiple levels, including visual processing, natural language understanding, and pattern generalization.

[Arxiv](https://arxiv.org/abs/2408.05894)