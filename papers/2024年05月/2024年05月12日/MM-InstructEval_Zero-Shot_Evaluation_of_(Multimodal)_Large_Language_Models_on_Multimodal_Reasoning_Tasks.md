# MM-InstructEval：大型多模态语言模型在多模态推理任务上的零-shot性能评估在这项研究中，我们引入了 MM-InstructEval，这是一个用于评估大型多模态语言模型在多模态推理任务上的零-shot性能的框架。通过这个框架，我们旨在探索这些模型在无需额外训练的情况下，如何理解和处理结合了文本和视觉信息的多模态输入，并执行复杂的推理任务。我们的目标是提供一个全面的评估工具，以揭示这些先进模型在多模态环境下的实际能力和潜在局限性。

发布时间：2024年05月12日

`RAG

理由：这篇论文主要关注的是多模态大型语言模型（MLLMs）的评估框架，特别是针对视觉与文本结合的多模态任务的性能评估。它提出了一个名为MM-InstructEval的评估框架，并通过多元指标来衡量模型的表现。这与RAG（Retrieval-Augmented Generation）的范畴相符，因为RAG是一种结合了检索和生成的方法，用于处理多模态数据和复杂任务。论文中的评估框架旨在提升对MLLMs在复杂多模态任务中性能的理解，这与RAG的目标相一致，即通过结合检索和生成来提高模型的性能和适应性。因此，这篇论文更适合归类为RAG，而不是Agent、LLM应用或LLM理论。` `多模态学习` `人工智能评估`

> MM-InstructEval: Zero-Shot Evaluation of (Multimodal) Large Language Models on Multimodal Reasoning Tasks

# 摘要

> 随着多模态大型语言模型（MLLMs）的兴起，对其评估的研究激增。然而，现有的评估大多局限于单一模态的理解和推理，忽略了在视觉与文本结合的复杂多模态任务中的关键性能评估。这些跨模态推理任务更具挑战性，需要深入理解多模态环境。为此，我们提出了MM-InstructEval评估框架，它通过多元指标全面衡量不同模型和指令在视觉-文本多模态任务中的表现。该框架不仅提升了对MLLMs在复杂任务中性能的研究，还推动了MLLMs的零-shot评估的全面性。我们通过“最佳性能”指标确定模型性能的极限，用“平均相对增益”分析整体表现，以“稳定性”衡量对变化的敏感度。以往研究往往忽视模型与指令间的互动，我们通过“适应性”指标填补了这一空白，量化了它们之间的适应性。我们的评估覆盖了31个模型，包括23个MLLMs，跨越16个数据集，涉及6类任务，采用10种指令。这一广泛分析为我们带来了新的洞见。

> The rising popularity of multimodal large language models (MLLMs) has sparked a significant increase in research dedicated to evaluating these models. However, current evaluation studies predominantly concentrate on the ability of models to comprehend and reason within a unimodal (vision-only) context, overlooking critical performance evaluations in complex multimodal reasoning tasks that integrate both visual and text contexts. Furthermore, tasks that demand reasoning across multiple modalities pose greater challenges and require a deep understanding of multimodal contexts. In this paper, we introduce a comprehensive assessment framework named MM-InstructEval, which integrates a diverse array of metrics to provide an extensive evaluation of the performance of various models and instructions across a broad range of multimodal reasoning tasks with vision-text contexts. MM-InstructEval enhances the research on the performance of MLLMs in complex multimodal reasoning tasks, facilitating a more thorough and holistic zero-shot evaluation of MLLMs. We firstly utilize the "Best Performance" metric to determine the upper performance limit of each model across various datasets. The "Mean Relative Gain" metric provides an analysis of the overall performance across different models and instructions, while the "Stability" metric evaluates their sensitivity to variations. Historically, the research has focused on evaluating models independently or solely assessing instructions, overlooking the interplay between models and instructions. To address this gap, we introduce the "Adaptability" metric, designed to quantify the degree of adaptability between models and instructions. Evaluations are conducted on 31 models (23 MLLMs) across 16 multimodal datasets, covering 6 tasks, with 10 distinct instructions. The extensive analysis enables us to derive novel insights.

[Arxiv](https://arxiv.org/abs/2405.07229)