# PromptWizard：基于任务感知的代理驱动提示优化框架

发布时间：2024年05月28日

`LLM应用

这篇论文介绍了一个名为PromptWizard的新框架，该框架用于自动化和优化大型语言模型（LLMs）的提示工程。它通过迭代地合成和细化针对特定任务的提示来提高模型性能，这与手动提示工程相比更为高效和通用。论文中提到的PromptWizard的功能和性能评估表明，它在多个任务和数据集上优于现有方法，这直接关联到LLM的应用层面，特别是在提示优化和模型性能提升方面。因此，这篇论文应归类于LLM应用。` `人工智能`

> PromptWizard: Task-Aware Agent-driven Prompt Optimization Framework

# 摘要

> 大型语言模型（LLMs）在多个领域中彻底改变了人工智能，展示了卓越的能力。其成功的核心在于提示的概念，它指导模型输出生成。然而，手动提示工程既耗时又特定于领域，需要自动化解决方案。本文介绍了PromptWizard，这是一种新颖的框架，利用LLMs迭代地合成和细化针对特定任务的提示。与现有方法不同，PromptWizard优化了提示指令和上下文示例，最大化模型性能。该框架通过变异指令和整合负面示例来迭代细化提示，加深理解和确保多样性。它还借助批评者进一步增强指令和示例，合成新的指令和示例，丰富了详细的推理步骤，以实现最佳性能。PromptWizard提供了几个关键特性和能力，包括与最先进方法相比的计算效率，适应不同数量的训练数据场景的能力，以及与较小的LLMs的有效性。在8个数据集上的35项任务中进行严格评估，证明了PromptWizard在提示优化方面的优越性，展示了其有效性和可扩展性。

> Large language models (LLMs) have revolutionized AI across diverse domains, showcasing remarkable capabilities. Central to their success is the concept of prompting, which guides model output generation. However, manual prompt engineering is labor-intensive and domain-specific, necessitating automated solutions. This paper introduces PromptWizard, a novel framework leveraging LLMs to iteratively synthesize and refine prompts tailored to specific tasks. Unlike existing approaches, PromptWizard optimizes both prompt instructions and in-context examples, maximizing model performance. The framework iteratively refines prompts by mutating instructions and incorporating negative examples to deepen understanding and ensure diversity. It further enhances both instructions and examples with the aid of a critic, synthesizing new instructions and examples enriched with detailed reasoning steps for optimal performance. PromptWizard offers several key features and capabilities, including computational efficiency compared to state-of-the-art approaches, adaptability to scenarios with varying amounts of training data, and effectiveness with smaller LLMs. Rigorous evaluation across 35 tasks on 8 datasets demonstrates PromptWizard's superiority over existing prompt strategies, showcasing its efficacy and scalability in prompt optimization.

[Arxiv](https://arxiv.org/abs/2405.18369)