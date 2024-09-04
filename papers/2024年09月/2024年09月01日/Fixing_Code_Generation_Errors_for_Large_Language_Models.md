# 解决大型语言模型中的代码生成问题

发布时间：2024年09月01日

`LLM应用` `软件开发` `人工智能`

> Fixing Code Generation Errors for Large Language Models

# 摘要

> 代码生成借助人工智能技术，尤其是大型语言模型（LLM），自动产出源代码，加速软件开发并减少重复劳动。但LLM生成的代码常因无法通过测试而需大量人力纠错。以往研究多聚焦于优化提示或提升LLM性能，却忽视了其失败根源。本文中，我们重现了包括GPT-3.5-turbo在内的14个LLM，在HumanEval数据集上，深入剖析了12,837个代码错误，识别出19种错误原因。实证显示，其中三种可直接修复。为此，我们提出LlmFix修复法，通过三步流程：调整代码缩进、删除冗余代码、补充缺失模块，有效解决了这些问题。实验证实，LlmFix大幅提升了14个LLM在HumanEval和MBPP数据集上的表现，平均提升分别为9.5%和5.4%。

> Code generation leverages artificial intelligence technologies, particularly Large Language Models (LLMs), to automatically produce source code, enhancing software development efficiency and reducing repetitive tasks. However, the LLMs' generated code often fails to pass test cases and requires substantial human effort to fix errors. Previous studies focused on better prompts or improving LLMs' capability but ignored why LLMs failed. In this paper, we first reproduced 14 LLMs, including GPT-3.5-turbo and 13 open-source LLMs, on the HumanEval dataset. We extracted 12,837 code generation errors and conducted an in-depth analysis of their causes, which led to the identification of 19 distinct error causes. Our empirical analysis indicated that three of these causes can be directly fixed. Consequently, we proposed a fixing method called LlmFix, which addresses these three types of errors through a three-step process: filtering code for indentation correction, truncating redundant generated code, and importing missing modules. Experimental results demonstrate that LlmFix can fix these three types of errors, significantly improving the performance of 14 LLMs on HumanEval and MBPP datasets with average increases of 9.5% and 5.4%, respectively.

[Arxiv](https://arxiv.org/abs/2409.00676)