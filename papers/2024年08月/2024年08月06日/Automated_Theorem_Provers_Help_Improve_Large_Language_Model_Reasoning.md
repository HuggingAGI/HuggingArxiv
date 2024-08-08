# 自动定理证明器助力大型语言模型推理能力的提升

发布时间：2024年08月06日

`LLM应用` `人工智能` `逻辑编程`

> Automated Theorem Provers Help Improve Large Language Model Reasoning

# 摘要

> 本文探讨了逻辑编程系统与自动一阶逻辑定理证明器（ATPs）如何助力大型语言模型（LLMs）在逻辑推理任务中提升准确性。我们首先通过PRONTOQA基准测试，评估了LLM在解决压路机问题时的推理表现。接着，我们展示了神经符号架构如何通过LLM将问题转化为形式逻辑语言，并借助自动推理引擎提高解题准确性。但此方法的成功关键在于LLM翻译的准确性。为此，我们定义了一套句法和语义错误分类框架，并据此识别了LLMs在基准测试中的常见错误。基于这些分析，我们进一步开发了自动纠正句法和语义错误的方法，特别是通过集成一阶逻辑ATP来纠正语义错误，这是我们的核心创新点。实验证明，这一方法能显著减少语义错误，从而大幅提升LLM在逻辑推理任务中的表现。

> In this paper we demonstrate how logic programming systems and Automated first-order logic Theorem Provers (ATPs) can improve the accuracy of Large Language Models (LLMs) for logical reasoning tasks where the baseline performance is given by direct LLM solutions. We first evaluate LLM reasoning on steamroller problems using the PRONTOQA benchmark. We show how accuracy can be improved with a neuro-symbolic architecture where the LLM acts solely as a front-end for translating a given problem into a formal logic language and an automated reasoning engine is called for solving it. However, this approach critically hinges on the correctness of the LLM translation. To assess this translation correctness, we secondly define a framework of syntactic and semantic error categories. We implemented the framework and used it to identify errors that LLMs make in the benchmark domain. Based on these findings, we thirdly extended our method with capabilities for automatically correcting syntactic and semantic errors. For semantic error correction we integrate first-order logic ATPs, which is our main and novel contribution. We demonstrate that this approach reduces semantic errors significantly and further increases the accurracy of LLM logical reasoning.

[Arxiv](https://arxiv.org/abs/2408.03492)