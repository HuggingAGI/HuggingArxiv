# 通过重新阅读，大型语言模型的推理能力得到了显著提升。

发布时间：2024年02月29日

`LLM应用

理由：这篇论文介绍了一种新的提示方法Re2，旨在提高大型语言模型（LLMs）的推理能力。它通过重复阅读问题来深化理解过程，并展示了这种方法在多个数据集上的有效性和通用性。这表明论文主要关注于LLM的实际应用，即如何通过特定的提示方法来增强模型的推理能力，而不是探讨LLM的理论基础或Agent的设计与实现。因此，它属于LLM应用分类。` `人工智能`

> Re-Reading Improves Reasoning in Large Language Models

# 摘要

> 我们提出了一种名为Re2的简单而高效的提示方法，旨在增强大型语言模型（LLMs）的推理能力。Re2通过重复阅读问题，将重点从输出转向输入，深化了理解过程。这种方法不仅与现有的思维激发提示方法（如思维链（CoT））兼容，还能在单向解码器LLMs中实现“双向”编码，提升推理效率。通过在14个数据集上的112次实验，我们验证了Re2的有效性和通用性。结果显示，Re2通过重复阅读策略，显著提升了LLMs在多种场景下的推理性能。此外，Re2的灵活性使其能与不同LLMs、提示方法及集成策略有效结合。相关代码已公开于\url{https://github.com/Tebmer/Rereading-LLM-Reasoning/}。

> To enhance the reasoning capabilities of off-the-shelf Large Language Models (LLMs), we introduce a simple, yet general and effective prompting method, Re2, i.e., \textbf{Re}-\textbf{Re}ading the question as input. Unlike most thought-eliciting prompting methods, such as Chain-of-Thought (CoT), which aim to elicit the reasoning process in the output, Re2 shifts the focus to the input by processing questions twice, thereby enhancing the understanding process. Consequently, Re2 demonstrates strong generality and compatibility with most thought-eliciting prompting methods, including CoT. Crucially, Re2 facilitates a "bidirectional" encoding in unidirectional decoder-only LLMs because the first pass could provide global information for the second pass. We begin with a preliminary empirical study as the foundation of Re2, illustrating its potential to enable "bidirectional" attention mechanisms. We then evaluate Re2 on extensive reasoning benchmarks across 14 datasets, spanning 112 experiments, to validate its effectiveness and generality. Our findings indicate that, with the exception of a few scenarios on vanilla ChatGPT, Re2 consistently enhances the reasoning performance of LLMs through a simple re-reading strategy. Further analyses reveal Re2's adaptability, showing how it can be effectively integrated with different LLMs, thought-eliciting prompting, and ensemble strategies. Our code is available at \url{https://github.com/Tebmer/Rereading-LLM-Reasoning/}

[Arxiv](https://arxiv.org/abs/2309.06275)