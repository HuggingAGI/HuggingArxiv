# 揭秘LLMs的词汇敏感度：通过组合优化提升提示效果

发布时间：2024年05月31日

`Agent

这篇论文主要探讨了大型语言模型（LLMs）对任务指令中微妙词汇变化的敏感性，并提出了一种名为提示词汇增强（COPLE）的框架来优化词汇选择，以提升模型性能。这种方法涉及使用代理任务的反馈进行迭代优化，属于Agent的范畴，因为它涉及创建一个能够自我优化和适应环境的智能体。因此，这篇论文应归类为Agent。` `机器学习`

> Unveiling the Lexical Sensitivity of LLMs: Combinatorial Optimization for Prompt Enhancement

# 摘要

> 大型语言模型（LLMs）以其卓越的指令遵循能力，轻松应对各类下游任务。然而，这种灵活性背后，它们对任务指令中的微妙词汇变化异常敏感，即便这些变化对人类而言微不足道。我们发现，仅更换一个语义相近的词汇，模型的任务表现就可能截然不同。为此，我们开发了提示词汇增强（COPLE），一种基于组合优化的黑盒框架，它通过迭代优化词汇，依据代理任务的反馈，采用词影响搜索策略，有效提升了模型性能。实验证明，即便是精心设计的人工提示，也难逃模型对词汇的敏感性，而COPLE则成功挽救了模型在遵循指令和执行任务中的能力下降。

> Large language models (LLMs) demonstrate exceptional instruct-following ability to complete various downstream tasks. Although this impressive ability makes LLMs flexible task solvers, their performance in solving tasks also heavily relies on instructions. In this paper, we reveal that LLMs are over-sensitive to lexical variations in task instructions, even when the variations are imperceptible to humans. By providing models with neighborhood instructions, which are closely situated in the latent representation space and differ by only one semantically similar word, the performance on downstream tasks can be vastly different. Following this property, we propose a black-box Combinatorial Optimization framework for Prompt Lexical Enhancement (COPLE). COPLE performs iterative lexical optimization according to the feedback from a batch of proxy tasks, using a search strategy related to word influence. Experiments show that even widely-used human-crafted prompts for current benchmarks suffer from the lexical sensitivity of models, and COPLE recovers the declined model ability in both instruct-following and solving downstream tasks.

![揭秘LLMs的词汇敏感度：通过组合优化提升提示效果](../../../paper_images/2405.20701/overview.eps)

![揭秘LLMs的词汇敏感度：通过组合优化提升提示效果](../../../paper_images/2405.20701/word-change-acc.eps)

![揭秘LLMs的词汇敏感度：通过组合优化提升提示效果](../../../paper_images/2405.20701/ablation_word-rate.eps)

![揭秘LLMs的词汇敏感度：通过组合优化提升提示效果](../../../paper_images/2405.20701/ablation_sample-rate.eps)

![揭秘LLMs的词汇敏感度：通过组合优化提升提示效果](../../../paper_images/2405.20701/ablation_max-candidate.eps)

![揭秘LLMs的词汇敏感度：通过组合优化提升提示效果](../../../paper_images/2405.20701/compare_with_optimal.eps)

[Arxiv](https://arxiv.org/abs/2405.20701)