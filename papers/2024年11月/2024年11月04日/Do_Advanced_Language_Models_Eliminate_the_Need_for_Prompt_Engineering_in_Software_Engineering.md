# 先进的语言模型是否消除了软件工程中提示工程的需求？

发布时间：2024年11月04日

`LLM应用` `软件工程` `语言模型`

> Do Advanced Language Models Eliminate the Need for Prompt Engineering in Software Engineering?

# 摘要

> 大型语言模型（LLM）极大地推进了软件工程（SE）任务，提示工程技术提高了它们在代码相关领域的性能。然而，基础大型语言模型（如非推理模型 GPT-4o 和推理模型 o1）的快速发展引发了关于这些提示工程技术持续有效性的疑问。本文进行了一项广泛的实证研究，在这些先进的大型语言模型的背景下重新评估了各种提示工程技术。聚焦于三个具有代表性的 SE 任务，即代码生成、代码翻译和代码总结，我们评估了提示工程技术在先进模型中是否仍然能带来改进，推理模型与非推理模型相比的实际效果，以及使用这些先进模型的好处是否能证明其增加的成本是合理的。我们的研究结果表明，为早期大型语言模型开发的提示工程技术在应用于先进模型时可能提供的益处减少，甚至会阻碍性能。在推理大型语言模型中，复杂的内置推理能力降低了复杂提示的影响，有时使得简单的零样本提示更有效。此外，虽然推理模型在需要复杂推理的任务中优于非推理模型，但在不需要推理的任务中优势极小，并且可能产生不必要的成本。基于我们的研究，我们为从业者在选择适当的提示工程技术和基础大型语言模型方面提供了实用的指导，考虑了诸如任务需求、运营成本和环境影响等因素。我们的工作有助于更深入地理解在软件工程任务中有效利用先进的大型语言模型，为未来的研究和应用开发提供信息。

> Large Language Models (LLMs) have significantly advanced software engineering (SE) tasks, with prompt engineering techniques enhancing their performance in code-related areas. However, the rapid development of foundational LLMs such as the non-reasoning model GPT-4o and the reasoning model o1 raises questions about the continued effectiveness of these prompt engineering techniques. This paper presents an extensive empirical study that reevaluates various prompt engineering techniques within the context of these advanced LLMs. Focusing on three representative SE tasks, i.e., code generation, code translation, and code summarization, we assess whether prompt engineering techniques still yield improvements with advanced models, the actual effectiveness of reasoning models compared to non-reasoning models, and whether the benefits of using these advanced models justify their increased costs. Our findings reveal that prompt engineering techniques developed for earlier LLMs may provide diminished benefits or even hinder performance when applied to advanced models. In reasoning LLMs, the ability of sophisticated built-in reasoning reduces the impact of complex prompts, sometimes making simple zero-shot prompting more effective. Furthermore, while reasoning models outperform non-reasoning models in tasks requiring complex reasoning, they offer minimal advantages in tasks that do not need reasoning and may incur unnecessary costs. Based on our study, we provide practical guidance for practitioners on selecting appropriate prompt engineering techniques and foundational LLMs, considering factors such as task requirements, operational costs, and environmental impact. Our work contributes to a deeper understanding of effectively harnessing advanced LLMs in SE tasks, informing future research and application development.

[Arxiv](https://arxiv.org/abs/2411.02093)