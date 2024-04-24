# NExT：引导大型语言模型理解代码执行的逻辑

发布时间：2024年04月22日

`LLM应用` `人工智能`

> NExT: Teaching Large Language Models to Reason about Code Execution

# 摘要

> 理解并推理程序的执行是人类开发者的核心能力之一。例如，程序员能够通过自然语言在心中模拟代码的运行，以此来调试和修复代码（俗称“橡胶鸭调试法”）。但是，通常在程序的文本形式上训练的大型语言模型（LLM）可能缺少对程序运行时语义理解的深度。为了克服这一难题，我们引入了NExT方法，它教导LLM通过思维链（CoT）推理来审视程序的执行轨迹（即执行行的变量状态）并理解其运行时行为。NExT通过自我训练技术，创建了一个无需繁琐手动标注的合成训练集，这些训练集包含了能够导向正确任务解决方案（如修正后的程序）的执行感知理由。在基于MBPP和HumanEval的程序修复任务上的实验显示，NExT显著提升了PaLM 2模型的修复成功率，分别提升了26.1%和14.3%，并且在自动化指标和人工评估中，理由的质量也得到了显著提升。此外，我们的模型还能在测试时程序轨迹缺失的情况下进行泛化应用。

> A fundamental skill among human developers is the ability to understand and reason about program execution. As an example, a programmer can mentally simulate code execution in natural language to debug and repair code (aka. rubber duck debugging). However, large language models (LLMs) of code are typically trained on the surface textual form of programs, thus may lack a semantic understanding of how programs execute at run-time. To address this issue, we propose NExT, a method to teach LLMs to inspect the execution traces of programs (variable states of executed lines) and reason about their run-time behavior through chain-of-thought (CoT) rationales. Specifically, NExT uses self-training to bootstrap a synthetic training set of execution-aware rationales that lead to correct task solutions (e.g., fixed programs) without laborious manual annotation. Experiments on program repair tasks based on MBPP and HumanEval demonstrate that NExT improves the fix rate of a PaLM 2 model, by 26.1% and 14.3% absolute, respectively, with significantly improved rationale quality as verified by automated metrics and human raters. Our model can also generalize to scenarios where program traces are absent at test-time.

[Arxiv](https://arxiv.org/abs/2404.14662)