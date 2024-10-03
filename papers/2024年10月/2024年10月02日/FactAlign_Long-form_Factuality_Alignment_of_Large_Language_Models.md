# FactAlign：大型语言模型的长篇事实对齐技术

发布时间：2024年10月02日

`LLM应用` `人工智能`

> FactAlign: Long-form Factuality Alignment of Large Language Models

# 摘要

> 大型语言模型作为下一代信息访问引擎展现出巨大潜力，但其可靠性因幻觉和生成非事实内容的问题而受限。特别是在长篇回应中，评估和确保事实准确性尤为复杂。为此，我们提出了 FactAlign，一个旨在提升 LLM 长篇回应事实性并保持其有用性的创新对齐框架。我们引入了 fKTO，一种细粒度的句子级对齐算法，扩展了 Kahneman-Tversky 优化方法。通过利用最新的自动事实性评估技术，FactAlign 利用细粒度的事实性评估来指导对齐过程。实验表明，FactAlign 不仅显著提高了 LLM 回应的事实准确性，还增强了其有用性。进一步分析显示，FactAlign 能够训练 LLM 在不牺牲事实精度的前提下提供更多信息，从而提升了事实 F1 分数。所有相关资源，包括源代码、数据集和训练模型，均已在 https://github.com/MiuLab/FactAlign 公开。

> Large language models have demonstrated significant potential as the next-generation information access engines. However, their reliability is hindered by issues of hallucination and generating non-factual content. This is particularly problematic in long-form responses, where assessing and ensuring factual accuracy is complex. In this paper, we address this gap by proposing FactAlign, a novel alignment framework designed to enhance the factuality of LLMs' long-form responses while maintaining their helpfulness. We introduce fKTO, a fine-grained, sentence-level alignment algorithm that extends the Kahneman-Tversky Optimization (KTO) alignment method. Leveraging recent advances in automatic factuality evaluation, FactAlign utilizes fine-grained factuality assessments to guide the alignment process. Our experiments on open-domain prompts and information-seeking questions demonstrate that FactAlign significantly improves the factual accuracy of LLM responses while also improving their helpfulness. Further analyses identify that FactAlign is capable of training LLMs to provide more information without losing factual precision, thus improving the factual F1 score. Our source code, datasets, and trained models are publicly available at https://github.com/MiuLab/FactAlign

[Arxiv](https://arxiv.org/abs/2410.01691)