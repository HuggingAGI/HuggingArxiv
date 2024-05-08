# Codexity：保障安全的 AI 代码创作助手

发布时间：2024年05月06日

`LLM应用

解释：这篇论文介绍了一个名为Codexity的框架，它集成了五大语言模型，旨在通过静态分析工具的反馈来减少模型生成代码中的安全漏洞。这个框架直接应用于软件开发中，利用大型语言模型来提高代码生成的安全性，属于大型语言模型在实际应用中的一个具体案例，因此归类为LLM应用。` `软件开发` `安全

解释：根据论文摘要` `该研究关注的是在软件开发过程中使用大型语言模型生成代码的安全性问题` `并提出了一个名为Codexity的框架来减少安全漏洞。因此` `最相关的行业领域标签是“软件开发”和“安全”。`

> Codexity: Secure AI-assisted Code Generation

# 摘要

> 大型语言模型在软件开发中表现卓越，但人工智能编程助手却可能埋下安全隐患。为此，我们推出了Codexity，一个集成了五大语言模型的安全代码生成框架。它借助静态分析工具的反馈，有效减少模型生成代码中的安全漏洞。在包含751个自动生成漏洞的实际测试中，Codexity成功为开发者屏蔽了60%的安全风险。

> Despite the impressive performance of Large Language Models (LLMs) in software development activities, recent studies show the concern of introducing vulnerabilities into software codebase by AI programming assistants (e.g., Copilot, CodeWhisperer). In this work, we present Codexity, a security-focused code generation framework integrated with five LLMs. Codexity leverages the feedback of static analysis tools such as Infer and CppCheck to mitigate security vulnerabilities in LLM-generated programs. Our evaluation in a real-world benchmark with 751 automatically generated vulnerable subjects demonstrates Codexity can prevent 60% of the vulnerabilities being exposed to the software developer.

[Arxiv](https://arxiv.org/abs/2405.03927)