# AI 程序员就在我们身边：我们正重新构思编程语言的语法规则，以期生成更高效的代码。

发布时间：2024年04月25日

`LLM应用` `编程语言` `人工智能`

> AI Coders Are Among Us: Rethinking Programming Language Grammar Towards Efficient Code Generation

# 摘要

> 随着大型语言模型（LLMs）时代的到来，人工智能（AI）模型已成为编程语言的新的重要受众。这些模型不仅能在编程竞赛中大放异彩，还能像专业开发者一样编写代码，处理包括数学计算在内的多种任务。但现有的程序设计多以人类为中心，包含了大量提高代码可读性的语法和格式标记。这种设计虽然方便了人类，却给 LLMs 带来了额外的计算负担。为了提升推理效率和降低成本，我们提出了一种面向 AI 的语法概念，旨在以更适合 AI 模型的方式呈现代码。采用这种语法的代码摒弃了不必要的格式，用最少的标记高效传达语义。为了验证这一概念，我们开发了首个面向 AI 的 Python 语法——Simple Python（SimPy），它通过一系列启发式规则对传统 Python 语法进行了精简。SimPy 编写的程序与标准 Python 保持相同的抽象语法树（AST）结构，可通过修改后的 AST 解析器执行。我们还研究了如何让现有的 LLMs 熟练掌握并使用 SimPy，同时确保这些改变对人类开发者无影响。相较于传统 Python，SimPy 在 CodeLlama 和 GPT-4 上分别减少了 13.5% 和 10.4% 的标记使用，且在性能上与 Python 代码训练的模型相当，甚至有所提升。

> Besides humans and machines, Artificial Intelligence (AI) models have emerged to be another important audience of programming languages, as we come to the era of large language models (LLMs). LLMs can now excel at coding competitions and even program like developers to address various tasks, such as math calculation. Yet, the grammar and layout of existing programs are designed for humans. Particularly, abundant grammar tokens and formatting tokens are included to make the code more readable to humans. While beneficial, such a human-centric design imposes an unnecessary computational burden on LLMs where each token, either consumed or generated, consumes computational resources. To improve inference efficiency and reduce computational costs, we propose the concept of AI-oriented grammar, which aims to represent the code in a way that better suits the working mechanism of AI models. Code written with AI-oriented grammar discards formats and uses a minimum number of tokens to convey code semantics effectively. To demonstrate the feasibility of this concept, we explore and implement the first AI-oriented grammar for Python, named Simple Python (SimPy). SimPy is crafted by revising the original Python grammar through a series of heuristic rules. Programs written in SimPy maintain identical Abstract Syntax Tree (AST) structures to those in standard Python, allowing execution via a modified AST parser. In addition, we explore methods to enable existing LLMs to proficiently understand and use SimPy, and ensure the changes remain imperceptible for human developers. Compared with the original Python, SimPy not only reduces token usage by 13.5% and 10.4% for CodeLlama and GPT-4, but can also achieve equivalent, even improved, performance over the models trained on Python code.

![AI 程序员就在我们身边：我们正重新构思编程语言的语法规则，以期生成更高效的代码。](../../../paper_images/2404.16333/x1.png)

![AI 程序员就在我们身边：我们正重新构思编程语言的语法规则，以期生成更高效的代码。](../../../paper_images/2404.16333/x2.png)

![AI 程序员就在我们身边：我们正重新构思编程语言的语法规则，以期生成更高效的代码。](../../../paper_images/2404.16333/x3.png)

![AI 程序员就在我们身边：我们正重新构思编程语言的语法规则，以期生成更高效的代码。](../../../paper_images/2404.16333/x4.png)

[Arxiv](https://arxiv.org/abs/2404.16333)