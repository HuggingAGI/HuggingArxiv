# 借助符号链式思维，精准演绎逻辑推理

发布时间：2024年05月28日

`LLM理论

理由：这篇论文介绍了一种新的链式思维框架SymbCoT，它结合了符号表达和逻辑规则来增强大型语言模型（LLMs）的逻辑推理能力。这种创新的方法涉及到LLMs的理论改进，特别是在处理逻辑推理方面的能力。因此，它属于LLM理论分类，因为它提出了一个理论上的新方法来改进LLMs的性能。` `人工智能` `逻辑推理`

> Faithful Logical Reasoning via Symbolic Chain-of-Thought

# 摘要

> 尽管心智理论链（CoT）技术提升了大型语言模型（LLMs）的推理能力，但在处理依赖符号表达和严格推理规则的逻辑推理时仍显不足。为此，我们提出了SymbCoT，一种结合符号表达和逻辑规则的全新链式思维框架，旨在强化LLMs的逻辑推理。SymbCoT首先将自然语言转换为符号格式，随后利用符号逻辑规则制定解题步骤，并通过验证器确保推理链的准确性。在5个标准数据集上的评估显示，SymbCoT不仅持续超越CoT方法，还刷新了行业最佳水平，展现出更忠实、灵活且可解释的逻辑推理能力。这是首次将符号元素融入CoT，用于LLMs的逻辑推理，相关代码已开源于GitHub。

> While the recent Chain-of-Thought (CoT) technique enhances the reasoning ability of large language models (LLMs) with the theory of mind, it might still struggle in handling logical reasoning that relies much on symbolic expressions and rigid deducing rules. To strengthen the logical reasoning capability of LLMs, we propose a novel Symbolic Chain-of-Thought, namely SymbCoT, a fully LLM-based framework that integrates symbolic expressions and logic rules with CoT prompting. Technically, building upon an LLM, SymbCoT 1) first translates the natural language context into the symbolic format, and then 2) derives a step-by-step plan to solve the problem with symbolic logical rules, 3) followed by a verifier to check the translation and reasoning chain. Via thorough evaluations on 5 standard datasets with both First-Order Logic and Constraint Optimization symbolic expressions, SymbCoT shows striking improvements over the CoT method consistently, meanwhile refreshing the current state-of-the-art performances. We further demonstrate that our system advances in more faithful, flexible, and explainable logical reasoning. To our knowledge, this is the first to combine symbolic expressions and rules into CoT for logical reasoning with LLMs. Code is open at https://github.com/Aiden0526/SymbCoT.

[Arxiv](https://arxiv.org/abs/2405.18357)