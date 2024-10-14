# 别改代码，改写代码：利用 LLM 实现精准代码重写的新思路

发布时间：2024年10月11日

`LLM应用` `软件开发` `人工智能`

> Don't Transform the Code, Code the Transforms: Towards Precise Code Rewriting using LLMs

# 摘要

> 重写、重构和优化代码的工具需快速且准确，但大型语言模型 (LLM) 天生不具备这些特质。尽管如此，利用 LLM 改进代码仍潜力巨大。我们探索了如何利用 LLM 进行代码转换，而非直接修改代码。提出了一种基于思维链的方法，通过少量输入/输出代码示例合成转换，结合执行与反馈。与直接重写相比，LLM 生成的转换更易检查、调试和验证，重写逻辑清晰且易调整。运行代码转换的计算量远低于 LLM 重写。我们在 16 个 Python 代码转换中测试，发现 LLM 生成的转换在 7 个中完全精确，其余则优于直接重写。我们期待推动更多研究，提升 LLM 代码重写的精度。

> Tools for rewriting, refactoring and optimizing code should be fast and correct. Large language models (LLMs), by their nature, possess neither of these qualities. Yet, there remains tremendous opportunity in using LLMs to improve code.
  We explore the use of LLMs not to transform code, but to code transforms. We propose a chain-of-thought approach to synthesizing code transformations from a small number of input/output code examples that incorporates execution and feedback. Unlike the direct rewrite approach, LLM-generated transformations are easy to inspect, debug, and validate. The logic of the rewrite is explicitly coded and easy to adapt. The compute required to run code transformations is minute compared to that of LLM rewriting.
  We test our approach on 16 Python code transformations and find that LLM- generated transforms are perfectly precise for 7 of them and less imprecise than direct LLM rewriting on the others. We hope to encourage further research to improving the precision of LLM code rewriting.

[Arxiv](https://arxiv.org/abs/2410.08806)