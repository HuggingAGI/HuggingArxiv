# HySem：专为非结构化表格提取设计的，优化上下文长度的 LLM 处理流程

发布时间：2024年08月18日

`LLM应用` `信息技术`

> HySem: A context length optimized LLM pipeline for unstructured tabular extraction

# 摘要

> 制药行业的监管报告依赖于详细表格，但这些表格因非结构化而常被忽视。提取和语义化表格数据因多样性而具挑战。大型语言模型（LLM）虽潜力巨大，但准确性和上下文限制成难题。我们推出HySem，利用创新上下文优化技术，从HTML表格生成精确语义JSON。此法专为中小型制药企业设计，兼顾成本与隐私。在普通硬件上，结合开源模型，自动校正LLM内容中的错误。HySem在准确性上领先，与GPT-4o比肩，有效克服上下文限制，助力更大表格处理。

> Regulatory compliance reporting in the pharmaceutical industry relies on detailed tables, but these are often under-utilized beyond compliance due to their unstructured format and arbitrary content. Extracting and semantically representing tabular data is challenging due to diverse table presentations. Large Language Models (LLMs) demonstrate substantial potential for semantic representation, yet they encounter challenges related to accuracy and context size limitations, which are crucial considerations for the industry applications. We introduce HySem, a pipeline that employs a novel context length optimization technique to generate accurate semantic JSON representations from HTML tables. This approach utilizes a custom fine-tuned model specifically designed for cost- and privacy-sensitive small and medium pharmaceutical enterprises. Running on commodity hardware and leveraging open-source models, our auto-correcting agents rectify both syntax and semantic errors in LLM-generated content. HySem surpasses its peer open-source models in accuracy and provides competitive performance when benchmarked against OpenAI GPT-4o and effectively addresses context length limitations, which is a crucial factor for supporting larger tables.

[Arxiv](https://arxiv.org/abs/2408.09434)