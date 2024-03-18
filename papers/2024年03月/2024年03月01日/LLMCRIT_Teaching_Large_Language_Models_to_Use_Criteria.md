# [LLMCRIT 计划旨在教授大型语言模型如何运用评判标准。](https://arxiv.org/abs/2403.01069)

发布时间：2024年03月01日

`LLM应用`

> LLMCRIT: Teaching Large Language Models to Use Criteria

> 在执行任务时，人类依据一套明确的准则，并以此判断任务完成好坏。为了助力人与模型提升任务表现，我们设想让模型学会运用准则给出反馈。目前相关领域的研究大多局限于某几项准则或评估维度。为此，我们创新性地设计了一种通用框架，赋能大型语言模型（LLMs）能针对各种任务，在生成自然语言反馈时运用全面详尽的准则。我们特别构建了一个半自动化“模型嵌入循环”框架，它能从不同写作任务的汇集指南中提炼准则，并为每个准则创建情境演示。我们选取了来自真实应用场景的三项任务——撰写论文引言、编写Python代码以及创作Reddit帖子，通过多种LLMs评估了我们的反馈生成框架。实验结果显示，融合准则和演示具有微妙而显著的效果，同时揭示了如何更高效地引导LLMs运用准则的重要洞见。

> Humans follow criteria when they execute tasks, and these criteria are directly used to assess the quality of task completion. Therefore, having models learn to use criteria to provide feedback can help humans or models to perform tasks better. However, existing research in this field tends to consider only a limited set of criteria or quality assessment aspects. To fill this gap, we propose a general framework that enables large language models (LLMs) to use comprehensive criteria for a task in delivering natural language feedback on task execution. In particular, we present a model-in-the-loop framework that semi-automatically derives criteria from collected guidelines for different writing tasks and constructs in-context demonstrations for each criterion. We choose three tasks from real-world scenarios to operationalize this idea: paper introduction writing, Python code writing, and Reddit post writing, and evaluate our feedback generation framework using different LLMs. The results reveal the fine-grained effects of incorporating criteria and demonstrations and provide valuable insights on how to teach LLMs to use criteria more effectively.

[Arxiv](https://arxiv.org/abs/2403.01069)