# 提升大型语言模型的图对齐能力

发布时间：2024年10月15日

`LLM应用` `图数据` `人工智能`

> Enhance Graph Alignment for Large Language Models

# 摘要

> 图结构数据在现实世界中无处不在。得益于强大的涌现能力，大型语言模型 (LLM) 在图建模方面展现出巨大潜力。关键在于将图数据转换为 LLM 能够理解的格式。图-token 方法通过将图转换为 token 序列，并通过指令调优与文本 token 对齐，使 LLM 能够处理图信息。自监督指令调优帮助 LLM 获取图的通用知识，而监督微调则使其专门用于图上的下游任务。然而，现有方法在自监督任务和下游任务之间存在错位，导致负迁移。为此，我们提出了图对齐大型语言模型 (GALLM)，通过引入与下游任务对齐的模板，解决了这一问题。实验结果表明，GALLM 在监督学习、多数据集泛化能力和零-shot 能力方面均有显著提升，展现了其作为图基础模型的巨大潜力。

> Graph-structured data is prevalent in the real world. Recently, due to the powerful emergent capabilities, Large Language Models (LLMs) have shown promising performance in modeling graphs. The key to effectively applying LLMs on graphs is converting graph data into a format LLMs can comprehend. Graph-to-token approaches are popular in enabling LLMs to process graph information. They transform graphs into sequences of tokens and align them with text tokens through instruction tuning, where self-supervised instruction tuning helps LLMs acquire general knowledge about graphs, and supervised fine-tuning specializes LLMs for the downstream tasks on graphs. Despite their initial success, we find that existing methods have a misalignment between self-supervised tasks and supervised downstream tasks, resulting in negative transfer from self-supervised fine-tuning to downstream tasks. To address these issues, we propose Graph Alignment Large Language Models (GALLM) to benefit from aligned task templates. In the self-supervised tuning stage, we introduce a novel text matching task using templates aligned with downstream tasks. In the task-specific tuning stage, we propose two category prompt methods that learn supervision information from additional explanation with further aligned templates. Experimental evaluations on four datasets demonstrate substantial improvements in supervised learning, multi-dataset generalizability, and particularly in zero-shot capability, highlighting the model's potential as a graph foundation model.

[Arxiv](https://arxiv.org/abs/2410.11370)