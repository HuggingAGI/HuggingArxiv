# $M^3$GPT：引领前沿的运动理解与生成多模态多任务框架

发布时间：2024年05月25日

`LLM应用

这篇论文介绍了一个名为$M^3$GPT的多模态、多任务框架，专门用于运动理解和生成。它通过整合文本、音乐及运动/舞蹈等多模态信号，并在原始运动空间进行模型生成，展示了在运动相关任务中的卓越表现和强大的零-shot泛化能力。这种应用性质的研究，特别是在大型语言模型（LLM）的背景下，处理多模态数据和任务，符合LLM应用的分类。` `运动科学` `人工智能`

> $M^3$GPT: An Advanced Multimodal, Multitask Framework for Motion Comprehension and Generation

# 摘要

> 本文推出的$M^3$GPT，是一个创新的多模态、多任务框架，专为运动理解和生成设计。其核心原则有三：首先，通过离散向量量化技术，将文本、音乐及运动/舞蹈等多模态信号统一整合至大型语言模型中，实现模态间的无缝对接。其次，直接在原始运动空间进行模型生成，避免了传统分词方法的信息损耗，提升了生成内容的丰富性和准确性。最后，利用文本这一LLMs最擅长的模态作为纽带，加强不同运动任务间的联系与协同，促进相互增益。$M^3$GPT不仅是首个能基于多信号理解并生成运动的模型，其广泛的实验结果也证明了它在各类运动相关任务中的卓越表现和在极具挑战性任务上的强大零-shot泛化能力。

> This paper presents $M^3$GPT, an advanced \textbf{M}ultimodal, \textbf{M}ultitask framework for \textbf{M}otion comprehension and generation. $M^3$GPT operates on three fundamental principles. The first focuses on creating a unified representation space for various motion-relevant modalities. We employ discrete vector quantization for multimodal control and generation signals, such as text, music and motion/dance, enabling seamless integration into a large language model (LLM) with a single vocabulary. The second involves modeling model generation directly in the raw motion space. This strategy circumvents the information loss associated with discrete tokenizer, resulting in more detailed and comprehensive model generation. Third, $M^3$GPT learns to model the connections and synergies among various motion-relevant tasks. Text, the most familiar and well-understood modality for LLMs, is utilized as a bridge to establish connections between different motion tasks, facilitating mutual reinforcement. To our knowledge, $M^3$GPT is the first model capable of comprehending and generating motions based on multiple signals. Extensive experiments highlight $M^3$GPT's superior performance across various motion-relevant tasks and its powerful zero-shot generalization capabilities for extremely challenging tasks.

![$M^3$GPT：引领前沿的运动理解与生成多模态多任务框架](../../../paper_images/2405.16273/x1.png)

![$M^3$GPT：引领前沿的运动理解与生成多模态多任务框架](../../../paper_images/2405.16273/x2.png)

![$M^3$GPT：引领前沿的运动理解与生成多模态多任务框架](../../../paper_images/2405.16273/x3.png)

![$M^3$GPT：引领前沿的运动理解与生成多模态多任务框架](../../../paper_images/2405.16273/x4.png)

![$M^3$GPT：引领前沿的运动理解与生成多模态多任务框架](../../../paper_images/2405.16273/x5.png)

![$M^3$GPT：引领前沿的运动理解与生成多模态多任务框架](../../../paper_images/2405.16273/x6.png)

[Arxiv](https://arxiv.org/abs/2405.16273)