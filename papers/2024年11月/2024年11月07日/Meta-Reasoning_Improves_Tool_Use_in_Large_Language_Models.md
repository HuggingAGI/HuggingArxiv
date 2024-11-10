# 元推理在大型语言模型中提高了工具的使用。

发布时间：2024年11月07日

`LLM应用`

> Meta-Reasoning Improves Tool Use in Large Language Models

# 摘要

> 外部工具帮助大型语言模型（LLMs）在它们通常会失败的任务中取得成功。在现有的框架中，LLMs 通过上下文演示或在带注释的数据上进行完整模型微调来学习工具使用。由于这些方法不易扩展，最近的趋势是放弃它们，转而采用轻量级、参数高效的调优范式。这些方法通过打开或关闭少数额外的自定义参数，允许在冻结的 LLM 及其专门微调的版本之间快速切换。因此，我们假设可以利用冻结模型的泛化能力来改进工具选择。我们提出了通过元推理进行工具选择（TECTON），这是一个两阶段系统，首先使用自定义微调的 LM 头对任务进行推理并输出候选工具。然后，在禁用自定义头的情况下，它进行元推理（即对先前的推理过程进行推理）以做出最终选择。我们表明，TECTON 在一系列数学推理数据集上都取得了显著的收益 - 包括分布内和分布外。

> External tools help large language models (LLMs) succeed at tasks where they would otherwise typically fail. In existing frameworks, LLMs learn tool use either by in-context demonstrations or via full model fine-tuning on annotated data. As these approaches do not easily scale, a recent trend is to abandon them in favor of lightweight, parameter-efficient tuning paradigms. These methods allow quickly alternating between the frozen LLM and its specialised fine-tuned version, by switching on or off a handful of additional custom parameters. Hence, we postulate that the generalization ability of the frozen model can be leveraged to improve tool selection. We present Tool selECTion via meta-reasONing (TECTON), a two-phase system that first reasons over a task using a custom fine-tuned LM head and outputs candidate tools. Then, with the custom head disabled, it meta-reasons (i.e., it reasons over the previous reasoning process) to make a final choice. We show that TECTON results in substantial gains - both in-distribution and out-of-distribution - on a range of math reasoning datasets.

[Arxiv](https://arxiv.org/abs/2411.04535)