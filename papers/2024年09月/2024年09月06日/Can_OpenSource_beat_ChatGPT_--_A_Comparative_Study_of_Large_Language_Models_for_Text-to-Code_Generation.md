# 开源能否超越 ChatGPT？—— 这是一场关于文本到代码生成的大型语言模型的较量。

发布时间：2024年09月06日

`LLM应用` `软件工程` `人工智能`

> Can OpenSource beat ChatGPT? -- A Comparative Study of Large Language Models for Text-to-Code Generation

# 摘要

> 近年来，大型语言模型（如 Bard、BingChat、ChatGPT、Llama2 和 Code Llama）在软件工程等领域展现出巨大潜力。我们通过实证研究，将 LeetCode 上的编程问题描述输入这些模型，要求其生成 Python 解决方案，并使用 LeetCode 的测试功能评估输出质量。结果显示，ChatGPT 在处理编程挑战方面表现最为出色，甚至优于专攻代码的 Code Llama。我们还测量了生成代码的运行时间和内存使用情况，并进行了详细的错误分析，发现随着提示长度的增加，模型生成的代码错误率显著上升。这些发现为我们提供了对模型性能的深入理解，并指出了改进的方向。

> In recent years, large language models (LLMs) have emerged as powerful tools with potential applications in various fields, including software engineering. Within the scope of this research, we evaluate five different state-of-the-art LLMs - Bard, BingChat, ChatGPT, Llama2, and Code Llama - concerning their capabilities for text-to-code generation. In an empirical study, we feed prompts with textual descriptions of coding problems sourced from the programming website LeetCode to the models with the task of creating solutions in Python. Subsequently, the quality of the generated outputs is assessed using the testing functionalities of LeetCode. The results indicate large differences in performance between the investigated models. ChatGPT can handle these typical programming challenges by far the most effectively, surpassing even code-specialized models like Code Llama. To gain further insights, we measure the runtime as well as the memory usage of the generated outputs and compared them to the other code submissions on Leetcode. A detailed error analysis, encompassing a comparison of the differences concerning correct indentation and form of the generated code as well as an assignment of the incorrectly solved tasks to certain error categories allows us to obtain a more nuanced picture of the results and potential for improvement. The results also show a clear pattern of increasingly incorrect produced code when the models are facing a lot of context in the form of longer prompts.

[Arxiv](https://arxiv.org/abs/2409.04164)