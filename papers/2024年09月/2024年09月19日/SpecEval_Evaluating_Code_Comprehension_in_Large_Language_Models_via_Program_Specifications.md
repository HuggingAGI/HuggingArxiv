# SpecEval：借助程序规范，评估大型语言模型中的代码理解能力

发布时间：2024年09月19日

`LLM应用` `软件工程` `人工智能`

> SpecEval: Evaluating Code Comprehension in Large Language Models via Program Specifications

# 摘要

> 大型语言模型在自动化软件工程中表现出色，但现有评估框架在代码理解方面存在局限。为此，我们推出了SpecEval，一个通过程序规范评估LLM代码理解能力的黑盒框架。实验显示，LLM在规范任务上的表现不尽如人意，指出了未来提升的方向。

> Large Language models have achieved impressive performance in automated software engineering. Extensive efforts have been made to evaluate the abilities of code LLMs in various aspects, with an increasing number of benchmarks and evaluation frameworks proposed. Apart from the most sought-after capability of code generation, the capability of code comprehension is being granted growing attention. Nevertheless, existing works assessing the code comprehension capability of LLMs exhibit varied limitations. Evaluation frameworks like CRUXEval and REval usually focus on code reasoning tasks over a certain input case, leading to a limited range of execution traces covered, resulting in a loss in code semantics examined and the inability to assess the comprehensive understanding of LLMs concerning the target program. To tackle the challenges above, we propose SpecEval, a novel black-box evaluation framework to evaluate code comprehension in LLMs via program specifications. Inspired by the idea that specifications can comprehensively articulate program behaviors concerning all possible execution traces, we employ formal specifications to represent program semantics and perform thorough evaluations. In particular, four specification-related tasks are designed to assess the capability of LLMs from basic to advanced levels. Moreover, counterfactual analysis is conducted to study the performance variance of LLMs under semantics-preserving perturbations, and progressive consistency analysis is performed to study the performance consistency of LLMs over a series of tasks with sequential dependence. Systematic experiments are conducted on six state-of-the-art LLMs. Experimental results present a below-satisfactory performance of LLMs on specification-related tasks, revealing the limitations of existing LLMs in articulating program semantics, underscoring future directions for enhancement.

[Arxiv](https://arxiv.org/abs/2409.12866)