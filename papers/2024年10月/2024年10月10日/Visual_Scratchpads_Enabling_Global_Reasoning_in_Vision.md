# 视觉草稿板：助力视觉全局推理

发布时间：2024年10月10日

`LLM理论` `人工智能` `计算机视觉`

> Visual Scratchpads: Enabling Global Reasoning in Vision

# 摘要

> 现代视觉模型在依赖局部特征的基准测试中表现出色，但面对需要全局推理的任务时，却显得力不从心。这些任务让人联想到 Minsky 和 Papert 在 1969 年提出的连通性问题，揭示了早期感知器模型的局限性，并引发了第一次 AI 寒冬。本文通过引入四个涉及路径查找和迷宫的全局视觉基准，重新审视了这些挑战。我们发现：(1) 尽管现代大型视觉模型在表达能力上超越了早期模型，但在学习效率上仍显不足；为此，我们提出了“全局性程度”的概念来解析这一难题；(2) 引入“视觉草稿纸”后，全局推理变得可行，这种工具类似于语言模型中的文本草稿纸和思维链，能将复杂任务分解为简单步骤；(3) 我们还发现，某些“归纳草稿纸”在依赖较少信息的情况下，表现出更强的分布外泛化能力，并能在较小的模型尺寸下取得成功。

> Modern vision models have achieved remarkable success in benchmarks where local features provide critical information about the target. There is now a growing interest in solving tasks that require more global reasoning, where local features offer no significant information. These tasks are reminiscent of the connectivity tasks discussed by Minsky and Papert in 1969, which exposed the limitations of the perceptron model and contributed to the first AI winter. In this paper, we revisit such tasks by introducing four global visual benchmarks involving path findings and mazes. We show that: (1) although today's large vision models largely surpass the expressivity limitations of the early models, they still struggle with the learning efficiency; we put forward the "globality degree" notion to understand this limitation; (2) we then demonstrate that the picture changes and global reasoning becomes feasible with the introduction of "visual scratchpads"; similarly to the text scratchpads and chain-of-thoughts used in language models, visual scratchpads help break down global tasks into simpler ones; (3) we finally show that some scratchpads are better than others, in particular, "inductive scratchpads" that take steps relying on less information afford better out-of-distribution generalization and succeed for smaller model sizes.

[Arxiv](https://arxiv.org/abs/2410.08165)