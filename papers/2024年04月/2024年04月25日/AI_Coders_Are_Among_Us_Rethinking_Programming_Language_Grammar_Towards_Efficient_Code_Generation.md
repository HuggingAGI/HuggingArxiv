# AI 程序员悄然崛起：探索编程语言的语法革新，以提升代码生成的效率。

发布时间：2024年04月25日

`LLM应用` `人工智能`

> AI Coders Are Among Us: Rethinking Programming Language Grammar Towards Efficient Code Generation

# 摘要

> 随着大型语言模型（LLM）时代的到来，人工智能（AI）模型已成为编程语言的新兴重要受众。如今，LLM不仅在编程竞赛中大放异彩，还能像专业开发者一样编写代码，处理包括数学计算在内的多种任务。但现有的程序设计以人为中心，包含了大量提高代码可读性的语法和格式标记，这给LLM带来了额外的计算负担。为了提升推理效率和降低成本，我们提出了一种面向AI的语法概念，旨在以更适合AI模型工作方式的形式来表示代码。采用这种语法的代码去除了不必要的格式，以最精简的标记数量有效传递代码含义。为了验证这一概念，我们探索并实现了首个面向AI的Python语法——Simple Python（SimPy）。SimPy通过一系列启发式规则对传统Python语法进行了优化，保持了与标准Python相同的抽象语法树（AST）结构，并通过改进的AST解析器执行。我们还研究了如何使现有的LLM熟练掌握并使用SimPy，同时确保这些改变对人类开发者无影响。相较于传统Python，SimPy在CodeLlama和GPT-4上的标记使用量分别减少了13.5%和10.4%，并且能够在训练有素的Python代码模型上达到甚至超越原有性能。

> Besides humans and machines, Artificial Intelligence (AI) models have emerged to be another important audience of programming languages, as we come to the era of large language models (LLMs). LLMs can now excel at coding competitions and even program like developers to address various tasks, such as math calculation. Yet, the grammar and layout of existing programs are designed for humans. Particularly, abundant grammar tokens and formatting tokens are included to make the code more readable to humans. While beneficial, such a human-centric design imposes an unnecessary computational burden on LLMs where each token, either consumed or generated, consumes computational resources. To improve inference efficiency and reduce computational costs, we propose the concept of AI-oriented grammar, which aims to represent the code in a way that better suits the working mechanism of AI models. Code written with AI-oriented grammar discards formats and uses a minimum number of tokens to convey code semantics effectively. To demonstrate the feasibility of this concept, we explore and implement the first AI-oriented grammar for Python, named Simple Python (SimPy). SimPy is crafted by revising the original Python grammar through a series of heuristic rules. Programs written in SimPy maintain identical Abstract Syntax Tree (AST) structures to those in standard Python, allowing execution via a modified AST parser. In addition, we explore methods to enable existing LLMs to proficiently understand and use SimPy, and ensure the changes remain imperceptible for human developers. Compared with the original Python, SimPy not only reduces token usage by 13.5% and 10.4% for CodeLlama and GPT-4, but can also achieve equivalent, even improved, performance over the models trained on Python code.

![AI 程序员悄然崛起：探索编程语言的语法革新，以提升代码生成的效率。](../../../paper_images/2404.16333/x1.png)

![AI 程序员悄然崛起：探索编程语言的语法革新，以提升代码生成的效率。](../../../paper_images/2404.16333/x2.png)

![AI 程序员悄然崛起：探索编程语言的语法革新，以提升代码生成的效率。](../../../paper_images/2404.16333/x3.png)

![AI 程序员悄然崛起：探索编程语言的语法革新，以提升代码生成的效率。](../../../paper_images/2404.16333/x4.png)

[Arxiv](https://arxiv.org/abs/2404.16333)