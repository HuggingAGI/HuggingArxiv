# 计算笔记本中的数据整理代码生成，融入上下文情境

发布时间：2024年09月20日

`LLM应用` `数据科学` `数据整理`

> Contextualized Data-Wrangling Code Generation in Computational Notebooks

# 摘要

> 数据整理是数据科学中不可或缺但耗时的环节。代码生成有望通过将用户意图转化为可执行代码，自动化这一过程。然而，精确生成数据整理代码需全面考虑笔记本中的多重上下文。笔记本常将非线性分析任务线性化，导致上下文依赖不明确。直接用源代码块训练模型，难以充分利用上下文。为此，我们构建了富含上下文的高质量数据集CoCoNote，包含58,221个示例，助力数据整理代码生成。我们提出CoCoMine方法，通过数据流分析和笔记本重放，提取清晰的多模态上下文依赖示例。实验证明，结合数据上下文显著提升代码生成质量。我们还推出了DataCoder，分别处理数据与代码&文本上下文，进一步增强生成效果。相关代码和数据已公开发布。

> Data wrangling, the process of preparing raw data for further analysis in computational notebooks, is a crucial yet time-consuming step in data science. Code generation has the potential to automate the data wrangling process to reduce analysts' overhead by translating user intents into executable code. Precisely generating data wrangling code necessitates a comprehensive consideration of the rich context present in notebooks, including textual context, code context and data context. However, notebooks often interleave multiple non-linear analysis tasks into linear sequence of code blocks, where the contextual dependencies are not clearly reflected. Directly training models with source code blocks fails to fully exploit the contexts for accurate wrangling code generation.
  To bridge the gap, we aim to construct a high quality datasets with clear and rich contexts to help training models for data wrangling code generation tasks. In this work, we first propose an automated approach, CoCoMine to mine data-wrangling code generation examples with clear multi-modal contextual dependency. It first adopts data flow analysis to identify the code blocks containing data wrangling codes. Then, CoCoMine extracts the contextualized datawrangling code examples through tracing and replaying notebooks. With CoCoMine, we construct CoCoNote, a dataset containing 58,221 examples for Contextualized Data-wrangling Code generation in Notebooks. To demonstrate the effectiveness of our dataset, we finetune a range of pretrained code models and prompt various large language models on our task. Furthermore, we also propose DataCoder, which encodes data context and code&textual contexts separately to enhance code generation. Experiment results demonstrate the significance of incorporating data context in data-wrangling code generation and the effectiveness of our model. We release code and data at url...

[Arxiv](https://arxiv.org/abs/2409.13551)