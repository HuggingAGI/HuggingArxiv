# LLMM代码生成能力的提升，我们借助了语法增强技术。本研究致力于探究如何通过针对性地增加和调整语法结构，优化大型语言模型在代码生成任务上的表现。

发布时间：2024年03月03日

`Agent`

> Improving LLM Code Generation with Grammar Augmentation

# 摘要

> 我们创新性地推出了 SynCode 框架，专为配合大型语言模型高效、广泛地解析代码句法而设计。SynCode 深度结合了各类编程语言的语法规则，利用预先构建的基于语法终结符的 DFA 遮罩存储这一高效查询工具。实验证明，在给定编程语言的上下文无关文法环境下，SynCode 能够确保句法有效符号得以保留，同时剔除无效部分，展现出其在正确性和完备性上的优势。无论何种遵循 CFG 的编程语言，SynCode 均能实现无缝对接，例如已成功应用于 Python 和 Go 的 CFG 测试案例。实验数据显示，当将 SynCode 与顶级 LLMs 结合使用时，句法错误率降低了高达 96.07%，充分体现了 SynCode 在提升代码生成句法精准度方面的重大贡献。我们的代码已在 GitHub 上公开，地址为 https://github.com/uiuc-focal-lab/syncode。

> We present SynCode a novel framework for efficient and general syntactical decoding of code with large language models (LLMs). SynCode leverages the grammar of a programming language, utilizing an offline-constructed efficient lookup table called DFA mask store based on language grammar terminals. We demonstrate SynCode's soundness and completeness given the context-free grammar (CFG) of the programming language, presenting its ability to retain syntactically valid tokens while rejecting invalid ones. The framework seamlessly integrates with any language defined by CFG, as evidenced by experiments on CFGs for Python and Go. The results underscore the significant reduction of 96.07% of syntax errors achieved when SynCode is combined with state-of-the-art LLMs, showcasing its substantial impact on enhancing syntactical precision in code generation.
  Our code is available at https://github.com/uiuc-focal-lab/syncode.

[Arxiv](https://arxiv.org/abs/2403.01632)