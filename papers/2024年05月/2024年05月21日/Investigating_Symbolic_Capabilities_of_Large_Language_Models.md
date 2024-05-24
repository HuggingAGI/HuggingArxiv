# 探究大型语言模型的符号处理能力

发布时间：2024年05月21日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）在符号计算和推理方面的表现，并通过一系列符号任务的评估来分析LLMs的能力。研究内容涉及模型的计算能力、评估框架以及模型在面对符号复杂性增加时的挑战，这些都是对LLMs理论层面的深入探讨。因此，这篇论文更适合归类于LLM理论。` `符号计算` `人工智能`

> Investigating Symbolic Capabilities of Large Language Models

# 摘要

> 提示技术极大地提升了大型语言模型（LLMs）在推理、规划及解决数学问题等多项复杂任务中的表现。尽管如此，多数研究仍偏重于语言推理和文字问题，对LLMs在符号计算和推理方面的潜力视而不见。本研究通过严格评估LLMs在加法、乘法、模运算、数值精度和符号计数等一系列符号任务上的表现，旨在弥合这一差距。我们分析了八种LLMs，包括四款企业级和四款开源模型，其中三款专为数学任务预训练。评估框架依托Chomsky层级，为模型计算能力提供了坚实衡量。评估中采用了最小解释提示和零-shot思维链技术，使模型能自主探索解题过程。研究显示，随着符号数量的增加，LLMs在上下文无关和上下文敏感的符号任务上的表现明显下滑。即便经过微调的GPT3.5也仅略有提升，与其他模型趋势一致。总体上，所有模型在这些符号密集任务上的泛化能力有限。此研究凸显了LLMs在应对符号复杂性增加时的挑战，并指出需通过专门训练、记忆和架构调整来提升其在符号推理任务中的能力。

> Prompting techniques have significantly enhanced the capabilities of Large Language Models (LLMs) across various complex tasks, including reasoning, planning, and solving math word problems. However, most research has predominantly focused on language-based reasoning and word problems, often overlooking the potential of LLMs in handling symbol-based calculations and reasoning. This study aims to bridge this gap by rigorously evaluating LLMs on a series of symbolic tasks, such as addition, multiplication, modulus arithmetic, numerical precision, and symbolic counting. Our analysis encompasses eight LLMs, including four enterprise-grade and four open-source models, of which three have been pre-trained on mathematical tasks. The assessment framework is anchored in Chomsky's Hierarchy, providing a robust measure of the computational abilities of these models. The evaluation employs minimally explained prompts alongside the zero-shot Chain of Thoughts technique, allowing models to navigate the solution process autonomously. The findings reveal a significant decline in LLMs' performance on context-free and context-sensitive symbolic tasks as the complexity, represented by the number of symbols, increases. Notably, even the fine-tuned GPT3.5 exhibits only marginal improvements, mirroring the performance trends observed in other models. Across the board, all models demonstrated a limited generalization ability on these symbol-intensive tasks. This research underscores LLMs' challenges with increasing symbolic complexity and highlights the need for specialized training, memory and architectural adjustments to enhance their proficiency in symbol-based reasoning tasks.

[Arxiv](https://arxiv.org/abs/2405.13209)