# HySem：专为非结构化表格提取设计的，优化上下文长度的 LLM 处理流程

发布时间：2024年08月18日

`LLM应用` `信息技术`

> HySem: A context length optimized LLM pipeline for unstructured tabular extraction

# 摘要

> 制药行业的监管报告依赖于详细表格，但这些表格因非结构化而常被忽视。提取和语义化表格数据因多样性而具挑战。大型语言模型（LLM）虽潜力巨大，但准确性和上下文限制仍是难题。我们推出的HySem，通过创新上下文优化技术，从HTML表格生成精准语义JSON。专为中小型制药企业设计，运行于普通硬件，利用开源模型自动修正LLM内容中的错误。HySem在准确性上领先，与OpenAI GPT-4o相比亦表现出色，有效克服了上下文限制，对支持大型表格至关重要。

> Regulatory compliance reporting in the pharmaceutical industry relies on detailed tables, but these are often under-utilized beyond compliance due to their unstructured format and arbitrary content. Extracting and semantically representing tabular data is challenging due to diverse table presentations. Large Language Models (LLMs) demonstrate substantial potential for semantic representation, yet they encounter challenges related to accuracy and context size limitations, which are crucial considerations for the industry applications. We introduce HySem, a pipeline that employs a novel context length optimization technique to generate accurate semantic JSON representations from HTML tables. This approach utilizes a custom fine-tuned model specifically designed for cost- and privacy-sensitive small and medium pharmaceutical enterprises. Running on commodity hardware and leveraging open-source models, our auto-correcting agents rectify both syntax and semantic errors in LLM-generated content. HySem surpasses its peer open-source models in accuracy and provides competitive performance when benchmarked against OpenAI GPT-4o and effectively addresses context length limitations, which is a crucial factor for supporting larger tables.

[Arxiv](https://arxiv.org/abs/2408.09434)