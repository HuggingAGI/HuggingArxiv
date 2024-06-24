# SpreadsheetBench：挑战真实世界电子表格操作的新里程碑

发布时间：2024年06月21日

`LLM应用

理由：这篇论文介绍了 SpreadsheetBench，一个专为大型语言模型（LLMs）设计的电子表格操作基准。它旨在模拟真实世界中的用户工作流程，并使用真实数据来评估模型的性能。这与“LLM应用”分类相符，因为它关注的是如何将LLM应用于特定的实际问题（电子表格操作），并评估其效果。这与理论研究或Agent、RAG的特定应用不同，而是更侧重于LLM在实际应用中的表现和挑战。` `电子表格` `数据处理`

> SpreadsheetBench: Towards Challenging Real World Spreadsheet Manipulation

# 摘要

> 我们推出了 SpreadsheetBench，这是一个专为大型语言模型（LLMs）设计的电子表格操作基准，它源自真实世界场景，旨在模拟用户的实际工作流程。与以往依赖合成数据和简化文件的基准不同，SpreadsheetBench 基于 912 个来自在线 Excel 论坛的真实问题，这些问题真实反映了用户的复杂需求。这些电子表格包含多种数据类型，如多表、非标准关系表及大量非文本元素。我们还提出了一种新的评估方法，类似于在线评判系统，通过为每个指令创建多个测试电子表格文件，确保评估能够应对不同值的电子表格。我们的评估显示，即使在单轮或多轮推理下，当前最先进的模型与人类表现之间仍存在显著差距，这凸显了 SpreadsheetBench 的挑战性。

> We introduce SpreadsheetBench, a challenging spreadsheet manipulation benchmark exclusively derived from real-world scenarios, designed to immerse current large language models (LLMs) in the actual workflow of spreadsheet users. Unlike existing benchmarks that rely on synthesized queries and simplified spreadsheet files, SpreadsheetBench is built from 912 real questions gathered from online Excel forums, which reflect the intricate needs of users. The associated spreadsheets from the forums contain a variety of tabular data such as multiple tables, non-standard relational tables, and abundant non-textual elements. Furthermore, we propose a more reliable evaluation metric akin to online judge platforms, where multiple spreadsheet files are created as test cases for each instruction, ensuring the evaluation of robust solutions capable of handling spreadsheets with varying values. Our comprehensive evaluation of various LLMs under both single-round and multi-round inference settings reveals a substantial gap between the state-of-the-art (SOTA) models and human performance, highlighting the benchmark's difficulty.

[Arxiv](https://arxiv.org/abs/2406.14991)