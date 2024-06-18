# R-Eval：统一工具包，专为评估增强检索的大型语言模型在领域知识方面的表现而设计。

发布时间：2024年06月17日

`RAG

理由：这篇论文主要关注的是检索增强的大型语言模型（RALLMs）的评估工具，特别是介绍了R-Eval工具包，这是一个专门设计来评估与LLMs结合的RAG工作流程的Python工具包。RAG（Retrieval-Augmented Generation）是一种特定的技术框架，它结合了检索和生成模型来提高语言模型的性能。因此，这篇论文的内容与RAG技术紧密相关，而不是Agent、LLM应用或LLM理论。论文的重点在于评估和改进RAG工作流程，这是RAG分类的核心内容。` `评估工具`

> R-Eval: A Unified Toolkit for Evaluating Domain Knowledge of Retrieval Augmented Large Language Models

# 摘要

> 大型语言模型虽在通用NLP任务上表现卓越，但在特定领域问题上的表现却不尽如人意。为此，研究者们提出了多种检索增强的大型语言模型（RALLMs）。然而，现有评估工具仅提供有限基准，并未深入挖掘各领域知识的深度。为此，我们开发了R-Eval工具包，一个专为简化与LLMs结合的RAG工作流程评估而设计的Python工具包。它支持主流RAG工作流程，并允许用户根据特定领域需求定制测试数据，旨在提供用户友好、模块化且可扩展的解决方案。我们对21个RALLMs在三个任务级别和两个关键领域进行了深入评估，发现不同任务和领域中RALLMs的有效性差异显著。这强调了在选择RAG工作流程与LLM组合时，必须同时考虑任务和领域需求。我们承诺将持续维护我们的平台https://github.com/THU-KEG/R-Eval，以助力工业界与研究者的进步。

> Large language models have achieved remarkable success on general NLP tasks, but they may fall short for domain-specific problems. Recently, various Retrieval-Augmented Large Language Models (RALLMs) are proposed to address this shortcoming. However, existing evaluation tools only provide a few baselines and evaluate them on various domains without mining the depth of domain knowledge. In this paper, we address the challenges of evaluating RALLMs by introducing the R-Eval toolkit, a Python toolkit designed to streamline the evaluation of different RAG workflows in conjunction with LLMs. Our toolkit, which supports popular built-in RAG workflows and allows for the incorporation of customized testing data on the specific domain, is designed to be user-friendly, modular, and extensible. We conduct an evaluation of 21 RALLMs across three task levels and two representative domains, revealing significant variations in the effectiveness of RALLMs across different tasks and domains. Our analysis emphasizes the importance of considering both task and domain requirements when choosing a RAG workflow and LLM combination. We are committed to continuously maintaining our platform at https://github.com/THU-KEG/R-Eval to facilitate both the industry and the researchers.

[Arxiv](https://arxiv.org/abs/2406.11681)