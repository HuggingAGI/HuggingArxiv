# Mind Your Step (by Step)：思维链可能会降低人类在思考后表现更差的任务上的性能

发布时间：2024年10月27日

`LLM应用` `认知心理学` `语言模型`

> Mind Your Step (by Step): Chain-of-Thought can Reduce Performance on Tasks where Thinking Makes Humans Worse

# 摘要

> 链思维（CoT）提示已成为处理大型语言和多模态模型的常用策略。尽管 CoT 在众多任务中能提升性能，但其有效设置的确定仍在探索中。尤其在哪些情况下 CoT 会系统性降低模型性能，仍是未解之谜。本文从认知心理学获取灵感，试图找出 CoT 降低性能的任务特点，研究（i）言语思维或深思影响人类表现不佳的情形，以及（ii）适用于人类表现的约束能否推广至语言模型。像隐式统计学习、视觉识别和包含异常的模式分类就属于此类。在这三个方面的大量实验中，我们发现，与零样本相比，使用推理时间推理时，众多先进模型的性能显著下降（比如，OpenAI o1-preview 与 GPT-4o 相比，绝对准确率最多降低 36.3%）。我们还确定了三个满足条件（i）但不满足（ii）的任务，发现虽然言语思维降低了人类在这些任务中的表现，但 CoT 能保持或提升模型性能。总之，我们的结果表明，模型和人类的认知过程并非完全一致，但考虑思维对人类表现产生负面作用的情况，有助于我们确定对模型产生负面影响的情形。通过将有关人类深思的文献与 CoT 的评估相结合，我们提供了一个新工具，可用于理解提示选择和推理时间推理的影响。

> Chain-of-thought (CoT) prompting has become a widely used strategy for working with large language and multimodal models. While CoT has been shown to improve performance across many tasks, determining the settings in which it is effective remains an ongoing effort. In particular, it is still an open question in what settings CoT systematically reduces model performance. In this paper, we seek to identify the characteristics of tasks where CoT reduces performance by drawing inspiration from cognitive psychology, looking at cases where (i) verbal thinking or deliberation hurts performance in humans, and (ii) the constraints governing human performance generalize to language models. Three such cases are implicit statistical learning, visual recognition, and classifying with patterns containing exceptions. In extensive experiments across all three settings, we find that a diverse collection of state-of-the-art models exhibit significant drop-offs in performance (e.g., up to 36.3% absolute accuracy for OpenAI o1-preview compared to GPT-4o) when using inference-time reasoning compared to zero-shot counterparts. We also identify three tasks that satisfy condition (i) but not (ii), and find that while verbal thinking reduces human performance in these tasks, CoT retains or increases model performance. Overall, our results show that while there is not an exact parallel between the cognitive processes of models and those of humans, considering cases where thinking has negative consequences for human performance can help us identify settings where it negatively impacts models. By connecting the literature on human deliberation with evaluations of CoT, we offer a new tool that can be used in understanding the impact of prompt choices and inference-time reasoning.

[Arxiv](https://arxiv.org/abs/2410.21333)