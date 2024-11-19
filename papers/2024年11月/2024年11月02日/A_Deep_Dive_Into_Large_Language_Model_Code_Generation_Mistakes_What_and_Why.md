# 深入探寻大型语言模型代码生成的错误：究竟是什么以及为何会这样？

发布时间：2024年11月02日

`LLM应用` `软件开发` `代码生成`

> A Deep Dive Into Large Language Model Code Generation Mistakes: What and Why?

# 摘要

> 近期，大型语言模型（LLMs）的发展促使其在自动代码生成领域广泛应用。但这些模型仍会生成不符合规范的有缺陷代码。以往研究多聚焦于 LLM 生成的独立函数中的错误，而忽视了在真实的软件开发场景中，成功生成代码需要像外部依赖这样的软件上下文。本文兼顾了这两种代码生成情形，明确了一系列因 LLM 对编码问题规范理解有误而产生的	extit{非语法错误}。经过大量人工分析，确定了七类非语法错误，其中四类是以往研究未曾涉及的。为更透彻地理解这些错误，我们从多个角度给出了导致错误的六个缘由。另外，我们探究了 LLM 在检测错误及其原因方面的成效。我们的评估显示，采用 ReAct 提示技术的 GPT-4 在识别 LLM 错误的原因（比如具有误导性的函数签名）时，F1 分数能高达 0.65。我们坚信，这些发现为提升 LLM 生成代码的质量提供了宝贵的思路。

> Recent advancements in Large Language Models (LLMs) have led to their widespread application in automated code generation. However, these models can still generate defective code that deviates from the specification. Previous research has mainly focused on the mistakes in LLM-generated standalone functions, overlooking real-world software development situations where the successful generation of the code requires software contexts such as external dependencies. In this paper, we considered both of these code generation situations and identified a range of \textit{non-syntactic mistakes} arising from LLMs' misunderstandings of coding question specifications. Seven categories of non-syntactic mistakes were identified through extensive manual analyses, four of which were missed by previous works. To better understand these mistakes, we proposed six reasons behind these mistakes from various perspectives. Moreover, we explored the effectiveness of LLMs in detecting mistakes and their reasons. Our evaluation demonstrated that GPT-4 with the ReAct prompting technique can achieve an F1 score of up to 0.65 when identifying reasons for LLM's mistakes, such as misleading function signatures. We believe that these findings offer valuable insights into enhancing the quality of LLM-generated code.

[Arxiv](https://arxiv.org/abs/2411.01414)