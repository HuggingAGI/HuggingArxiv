# 大型语言模型：代码执行的新探索

发布时间：2024年10月09日

`LLM应用` `软件开发` `人工智能`

> Large Language Models as Code Executors: An Exploratory Study

# 摘要

> 大型语言模型 (LLM) 的能力已从自然语言处理扩展至代码理解和生成等复杂任务。本文首次探索 LLM 作为代码执行器，直接输入代码片段并返回执行结果。我们全面评估了 OpenAI 的 o1、GPT-4o、GPT-3.5、DeepSeek 和 Qwen-Coder 等 LLM 的执行能力，发现 o1 模型准确率超 90%，其他模型则较低。此外，我们创新的迭代指令提示 (IIP) 技术逐行处理代码，平均提升较弱模型准确率 7.22%（最高 18.96%），相对 CoT 提示提升 3.86%（最高 19.46%）。此研究不仅展示了 LLM 在编码领域的巨大潜力，也为自动化编程和复杂任务完成奠定了基础。

> The capabilities of Large Language Models (LLMs) have significantly evolved, extending from natural language processing to complex tasks like code understanding and generation. We expand the scope of LLMs' capabilities to a broader context, using LLMs to execute code snippets to obtain the output. This paper pioneers the exploration of LLMs as code executors, where code snippets are directly fed to the models for execution, and outputs are returned. We are the first to comprehensively examine this feasibility across various LLMs, including OpenAI's o1, GPT-4o, GPT-3.5, DeepSeek, and Qwen-Coder. Notably, the o1 model achieved over 90% accuracy in code execution, while others demonstrated lower accuracy levels. Furthermore, we introduce an Iterative Instruction Prompting (IIP) technique that processes code snippets line by line, enhancing the accuracy of weaker models by an average of 7.22% (with the highest improvement of 18.96%) and an absolute average improvement of 3.86% against CoT prompting (with the highest improvement of 19.46%). Our study not only highlights the transformative potential of LLMs in coding but also lays the groundwork for future advancements in automated programming and the completion of complex tasks.

[Arxiv](https://arxiv.org/abs/2410.06667)