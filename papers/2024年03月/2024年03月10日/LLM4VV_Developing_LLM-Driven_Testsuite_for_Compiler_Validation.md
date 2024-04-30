# LLM4VV：构建基于大型语言模型的编译器验证测试集

发布时间：2024年03月10日

`LLM应用` `软件工程` `并行计算`

> LLM4VV: Developing LLM-Driven Testsuite for Compiler Validation

# 摘要

> 大型语言模型（LLMs）作为处理自然语言相关应用的强有力新工具，展现出卓越的代码生成才能。本研究旨在自动化生成测试用例，以验证并确认OpenACC这一基于指令的并行编程范式的编译器实现。在本论文中，我们深入探讨了包括开源模型如Meta Codellama、Codellama的Phind微调版、Deepseek Deepseek Coder，以及闭源模型如OpenAI的GPT-3.5-Turbo和GPT-4-Turbo在内的尖端LLMs的潜力。利用自有的测试套件数据集和OpenACC规范，我们对这些开源和GPT-3.5-Turbo模型进行了进一步的微调。此外，我们还尝试了多种提示工程技术，包括代码模板、RAG（检索增强生成）辅助模板、单次示例、RAG辅助单次示例、以及包含代码模板和RAG的表达性提示。本文汇总了通过上述方法生成的逾5000个测试的研究成果。我们的研究成果包括：（a）探究当前相关LLMs在代码生成上的能力，（b）调研微调与提示技巧，以及（c）分析LLMs生成测试的结果，并对一组代表性测试进行了手动分析。研究发现，Deepseek-Coder-33b-Instruct模型生成的通过测试数量最多，紧随其后的是GPT-4-Turbo。

> Large language models (LLMs) are a new and powerful tool for a wide span of applications involving natural language and demonstrate impressive code generation abilities. The goal of this work is to automatically generate tests and use these tests to validate and verify compiler implementations of a directive-based parallel programming paradigm, OpenACC. To do so, in this paper, we explore the capabilities of state-of-the-art LLMs, including open-source LLMs -- Meta Codellama, Phind fine-tuned version of Codellama, Deepseek Deepseek Coder and closed-source LLMs -- OpenAI GPT-3.5-Turbo and GPT-4-Turbo. We further fine-tuned the open-source LLMs and GPT-3.5-Turbo using our own testsuite dataset along with using the OpenACC specification. We also explored these LLMs using various prompt engineering techniques that include code template, template with retrieval-augmented generation (RAG), one-shot example, one-shot with RAG, expressive prompt with code template and RAG. This paper highlights our findings from over 5000 tests generated via all the above mentioned methods. Our contributions include: (a) exploring the capabilities of the latest and relevant LLMs for code generation, (b) investigating fine-tuning and prompt methods, and (c) analyzing the outcome of LLMs generated tests including manually analysis of representative set of tests. We found the LLM Deepseek-Coder-33b-Instruct produced the most passing tests followed by GPT-4-Turbo.

[Arxiv](https://arxiv.org/abs/2310.04963)