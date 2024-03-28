# Query-OPT 方法旨在通过在会议摘要场景下运用多查询指令，提升大型语言模型推理效率。这项研究针对大型语言模型，在会议内容总结任务中探究如何借助多查询指令进行优化推理过程。

发布时间：2024年02月29日

`LLM应用`

> Query-OPT: Optimizing Inference of Large Language Models via Multi-Query Instructions in Meeting Summarization

# 摘要

> 本研究致力于解决基于查询的会议摘要问题，即根据具体查询自动生成会议记录摘要。当利用LLMs处理这类任务时，即便背景相同，每出现新查询也需重新调用LLM的推理接口。然而，频繁调用LLM推理接口会大幅提高生产成本，使得LLMs在许多实际应用场景中难以施展拳脚。为此，我们探究了一种方法：能否在一个提示中合并针对同一背景的多个查询，从而有效减少调用量，并将其应用于会议摘要任务。为此，我们在单查询和多查询环境下对比测试了多种热门LLMs（如GPT-4、PaLM-2、LLaMA-2、Mistral以及FLAN-T5）的表现。实验发现，尽管多数LLMs都能应对多查询指导，但除GPT-4外，其余模型即使经过精细调整，仍无法稳定地按要求的输出格式生成恰当回复。因此，我们可以总结出，尽管多查询引导有助于通过降低推理接口调用量来优化会议摘要任务的成本，但能在预设格式下可靠生成回复的能力仅限于部分LLMs。

> This work focuses on the task of query-based meeting summarization in which the summary of a context (meeting transcript) is generated in response to a specific query. When using Large Language Models (LLMs) for this task, a new call to the LLM inference endpoint/API is required for each new query even if the context stays the same. However, repeated calls to the LLM inference endpoints would significantly increase the costs of using them in production, making LLMs impractical for many real-world use cases. To address this problem, in this paper, we investigate whether combining the queries for the same input context in a single prompt to minimize repeated calls can be successfully used in meeting summarization. In this regard, we conduct extensive experiments by comparing the performance of various popular LLMs: GPT-4, PaLM-2, LLaMA-2, Mistral, and FLAN-T5 in single-query and multi-query settings. We observe that while most LLMs tend to respond to the multi-query instructions, almost all of them (except GPT-4), even after fine-tuning, could not properly generate the response in the required output format. We conclude that while multi-query prompting could be useful to optimize the inference costs by reducing calls to the inference endpoints/APIs for the task of meeting summarization, this capability to reliably generate the response in the expected format is only limited to certain LLMs.

[Arxiv](https://arxiv.org/abs/2403.00067)