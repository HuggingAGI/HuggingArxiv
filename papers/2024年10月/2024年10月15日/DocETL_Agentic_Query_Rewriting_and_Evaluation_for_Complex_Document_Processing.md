# DocETL：针对复杂文档处理的智能查询重写与评估

发布时间：2024年10月15日

`Agent` `数据处理` `文档分析`

> DocETL: Agentic Query Rewriting and Evaluation for Complex Document Processing

# 摘要

> 处理复杂文档等非结构化数据一直是数据处理的难题。虽然大型语言模型 (LLM) 在这方面展现出潜力，但现有框架主要关注降低成本而非提高准确性。这导致在复杂任务中，LLM 的输出往往不尽人意。为此，我们推出了 DocETL 系统，专门优化复杂文档处理流程，并弥补 LLM 的不足。DocETL 提供声明性接口，让用户轻松定义处理流程，并通过基于代理的框架自动优化。我们引入了逻辑重写、代理引导的计划评估机制和高效优化算法，确保在时间限制内找到高质量的解决方案。实验证明，DocETL 在非结构化文档分析任务中的表现远超现有基线，输出质量提升高达 4.6 倍。DocETL 已开源，截至 2024 年 10 月，已在 GitHub 上获得超过 800 颗星，广泛应用于多个领域。

> Analyzing unstructured data, such as complex documents, has been a persistent challenge in data processing. Large Language Models (LLMs) have shown promise in this regard, leading to recent proposals for declarative frameworks for LLM-powered unstructured data processing. However, these frameworks focus on reducing cost when executing user-specified operations using LLMs, rather than improving accuracy, executing most operations as-is. This is problematic for complex tasks and data, where LLM outputs for user-defined operations are often inaccurate, even with optimized prompts.
  We present DocETL, a system that optimizes complex document processing pipelines, while accounting for LLM shortcomings. DocETL offers a declarative interface for users to define such pipelines and uses an agent-based framework to automatically optimize them, leveraging novel agent-based rewrites (that we call {\em rewrite directives}) and an optimization and evaluation framework that we introduce. We introduce {\em (i)} logical rewriting of pipelines, tailored for LLM-based tasks, {\em (ii)} an agent-guided plan evaluation mechanism that synthesizes and orchestrates task-specific validation prompts, and {\em (iii)} an optimization algorithm that efficiently finds promising plans, considering the time constraints of LLM-based plan generation and evaluation. Our evaluation on three different unstructured document analysis tasks demonstrates that DocETL finds plans with outputs that are $1.34$ to $4.6\times$ higher quality (e.g., more accurate, comprehensive) than well-engineered baselines, addressing a critical gap in existing declarative frameworks for unstructured data analysis. DocETL is open-source at \ttt{docetl.org}, and as of October 2024, has amassed over 800 GitHub Stars, with users spanning a variety of domains.

[Arxiv](https://arxiv.org/abs/2410.12189)