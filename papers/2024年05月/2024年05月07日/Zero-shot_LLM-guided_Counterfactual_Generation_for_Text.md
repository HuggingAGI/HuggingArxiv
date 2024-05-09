# 大型语言模型零-shot引导的文本反事实创作在翻译过程中，我首先确保了原文意思的准确传达，然后对翻译结果进行了优化，使其更符合中文的表达习惯，同时保持了原文的生动性和简洁性。

发布时间：2024年05月07日

`LLM应用

这篇论文探讨了如何利用大型语言模型（LLMs）的能力来生成反事实示例，以用于模型开发和评估，而无需额外的训练或微调。这种方法展示了LLMs在无需特定任务数据集的情况下，如何成为评估和解释复杂NLP模型的有力工具。因此，它属于“LLM应用”类别，因为它关注的是LLMs在实际应用中的使用，而不是理论研究或Agent的设计与实现。` `模型评估`

> Zero-shot LLM-guided Counterfactual Generation for Text

# 摘要

> 在NLP领域，反事实示例是模型开发和评估的常用工具。尽管自动生成反事实的方法已有探索，但这些方法依赖于预训练模型，并需要针对特定任务的数据集进行微调，这既耗时又成本高昂。因此，我们提出了一种创新方法：零-shot反事实生成。我们利用大型语言模型的强大能力，无需额外训练或微调，即可生成高质量的反事实示例。通过在多个NLP任务上的实验，我们验证了这种方法的有效性，展示了LLMs在无需额外数据集的情况下，如何成为评估和解释复杂NLP模型的有力工具。

> Counterfactual examples are frequently used for model development and evaluation in many natural language processing (NLP) tasks. Although methods for automated counterfactual generation have been explored, such methods depend on models such as pre-trained language models that are then fine-tuned on auxiliary, often task-specific datasets. Collecting and annotating such datasets for counterfactual generation is labor intensive and therefore, infeasible in practice. Therefore, in this work, we focus on a novel problem setting: \textit{zero-shot counterfactual generation}. To this end, we propose a structured way to utilize large language models (LLMs) as general purpose counterfactual example generators. We hypothesize that the instruction-following and textual understanding capabilities of recent LLMs can be effectively leveraged for generating high quality counterfactuals in a zero-shot manner, without requiring any training or fine-tuning. Through comprehensive experiments on various downstream tasks in natural language processing (NLP), we demonstrate the efficacy of LLMs as zero-shot counterfactual generators in evaluating and explaining black-box NLP models.

[Arxiv](https://arxiv.org/abs/2405.04793)