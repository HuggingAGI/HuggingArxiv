# 不仅仅是微调，持续预训练正在释放临床大型语言模型的无限潜能。

发布时间：2024年09月23日

`LLM应用` `人工智能`

> Beyond Fine-tuning: Unleashing the Potential of Continuous Pretraining for Clinical LLMs

# 摘要

> 大型语言模型（LLM）在临床应用中展现出巨大潜力。本研究探讨了四种技术——持续预训练、指令微调、NEFTune 和提示工程——在临床场景中的应用效果。我们使用 Mistral 7B 和 Mixtral 8x7B 模型，结合 500 亿标记的临床数据集和 500 亿标记的微调数据集进行实验。结果显示，尽管超过 2500 亿标记的持续预训练提升有限，但为后续微调打下坚实基础。特别地，NEFTune 在提升生成质量的同时，还带来了额外收益。复杂的提示工程进一步增强了性能。这些发现强调了定制微调策略和创新技术在优化临床 LLM 性能中的关键作用。

> Large Language Models (LLMs) have demonstrated significant potential in transforming clinical applications. In this study, we investigate the efficacy of four techniques in adapting LLMs for clinical use-cases: continuous pretraining, instruct fine-tuning, NEFTune, and prompt engineering. We employ these methods on Mistral 7B and Mixtral 8x7B models, leveraging a large-scale clinical pretraining dataset of 50 billion tokens and an instruct fine-tuning dataset of 500 million tokens. Our evaluation across various clinical tasks reveals the impact of each technique. While continuous pretraining beyond 250 billion tokens yields marginal improvements on its own, it establishes a strong foundation for instruct fine-tuning. Notably, NEFTune, designed primarily to enhance generation quality, surprisingly demonstrates additional gains on our benchmark. Complex prompt engineering methods further enhance performance. These findings show the importance of tailoring fine-tuning strategies and exploring innovative techniques to optimize LLM performance in the clinical domain.

[Arxiv](https://arxiv.org/abs/2409.14988)