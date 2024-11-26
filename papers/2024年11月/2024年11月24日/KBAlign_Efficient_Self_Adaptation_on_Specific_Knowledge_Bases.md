# KBAda：在特定知识库上实现高效的自我适应

发布时间：2024年11月24日

`LLM应用` `语言模型` `知识学习`

> KBAlign: Efficient Self Adaptation on Specific Knowledge Bases

# 摘要

> 人类能够运用一些技巧，提前从特定材料中迅速获取知识，比如创建自我评估问题，从而让我们更高效地完成相关任务。然而，大型语言模型（LLMs）往往依赖检索增强生成瞬间利用知识材料，或者需要诸如人类偏好数据和更强大的LLM标注等外部信号来进行知识适配。为了激发LLMs的自学习潜能，我们提出了KBAda，这是一种专为高效适应涉及知识库的下游任务而设计的方法。我们的方法通过利用带有自我标注数据（如问答对和修订建议）的迭代训练，让模型能够高效地掌握知识内容。在多个数据集上的实验结果表明，我们的方法成效显著，以低成本大幅提升了下游任务中需要特定知识的模型性能。特别值得一提的是，我们的方法在完全依靠自我监督的情况下，实现了使用GPT-4-turbo标注所能达到的90%以上的性能提升。我们将实验数据、模型和过程分析向社区公布，以供进一步探索（https://github.com/thunlp/KBAda）。

> Humans can utilize techniques to quickly acquire knowledge from specific materials in advance, such as creating self-assessment questions, enabling us to achieving related tasks more efficiently. In contrast, large language models (LLMs) usually relies on retrieval-augmented generation to exploit knowledge materials in an instant manner, or requires external signals such as human preference data and stronger LLM annotations to conduct knowledge adaptation. To unleash the self-learning potential of LLMs, we propose KBAlign, an approach designed for efficient adaptation to downstream tasks involving knowledge bases. Our method utilizes iterative training with self-annotated data such as Q&A pairs and revision suggestions, enabling the model to grasp the knowledge content efficiently. Experimental results on multiple datasets demonstrate the effectiveness of our approach, significantly boosting model performance in downstream tasks that require specific knowledge at a low cost. Notably, our approach achieves over 90% of the performance improvement that can be obtained by using GPT-4-turbo annotation, while relying entirely on self-supervision. We release our experimental data, models, and process analyses to the community for further exploration (https://github.com/thunlp/KBAlign).

[Arxiv](https://arxiv.org/abs/2411.14790)