# 基于 LLM 的单元测试生成：属性检索法

发布时间：2024年10月17日

`RAG` `软件开发` `测试自动化`

> LLM-based Unit Test Generation via Property Retrieval

# 摘要

> 自动单元测试生成研究广泛，LLM 近期潜力巨大。然而，现有工具为追求高代码覆盖率，常牺牲实用性、正确性和可维护性。为此，我们提出基于属性的检索增强，超越传统 RAG，考虑任务特定上下文，定制属性检索机制。在单元测试生成中，我们细分测试过程为 Given、When、Then 阶段，检索焦点方法及其他方法的上下文，形成属性关系，扩展检索范围。APT 工具实现此方法，通过迭代策略生成测试，评估显示其在正确性、完整性和可维护性上优于现有工具。此外，我们引入代码上下文感知检索机制，为 LLM 提供新视角，助力其他代码任务。

> Automated unit test generation has been widely studied, with Large Language Models (LLMs) recently showing significant potential. Moreover, in the context of unit test generation, these tools prioritize high code coverage, often at the expense of practical usability, correctness, and maintainability. In response, we propose Property-Based Retrieval Augmentation, a novel mechanism that extends LLM-based Retrieval-Augmented Generation (RAG) beyond basic vector, text similarity, and graph-based methods. Our approach considers task-specific context and introduces a tailored property retrieval mechanism. Specifically, in the unit test generation task, we account for the unique structure of unit tests by dividing the test generation process into Given, When, and Then phases. When generating tests for a focal method, we not only retrieve general context for the code under test but also consider task-specific context such as pre-existing tests of other methods, which can provide valuable insights for any of the Given, When, and Then phases. This forms property relationships between focal method and other methods, thereby expanding the scope of retrieval beyond traditional RAG. We implement this approach in a tool called APT, which sequentially performs preprocessing, property retrieval, and unit test generation, using an iterative strategy where newly generated tests guide the creation of subsequent ones. We evaluated APT on 12 open-source projects with 1515 methods, and the results demonstrate that APT consistently outperforms existing tools in terms of correctness, completeness, and maintainability of the generated tests. Moreover, we introduce a novel code-context-aware retrieval mechanism for LLMs beyond general context, offering valuable insights and potential applications for other code-related tasks.

[Arxiv](https://arxiv.org/abs/2410.13542)