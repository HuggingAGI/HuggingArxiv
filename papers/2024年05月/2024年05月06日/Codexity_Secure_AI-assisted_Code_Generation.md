# Codexity：保障安全的 AI 代码创作助手

发布时间：2024年05月06日

`LLM应用

这篇论文讨论了如何利用大型语言模型（LLMs）来提高软件开发中的安全性，特别是通过一个名为Codexity的框架，该框架结合了静态分析工具来检测和防止由LLM生成的代码中的安全漏洞。这与LLM在实际应用中的使用相关，特别是在提高软件安全性方面，因此属于LLM应用分类。` `软件开发` `网络安全`

> Codexity: Secure AI-assisted Code Generation

# 摘要

> 尽管LLMs在软件开发领域大放异彩，但人工智能编程助手却可能成为软件安全的隐患。为此，我们推出了Codexity，一个融合五大LLM的安全代码生成框架。它借助静态分析工具的智慧，如Infer和CppCheck，为LLM生成的代码筑起安全屏障。在751个自动生成的漏洞样本的实战检验中，Codexity成功为开发者遮蔽了60%的安全漏洞，守护了代码的纯净。

> Despite the impressive performance of Large Language Models (LLMs) in software development activities, recent studies show the concern of introducing vulnerabilities into software codebase by AI programming assistants (e.g., Copilot, CodeWhisperer). In this work, we present Codexity, a security-focused code generation framework integrated with five LLMs. Codexity leverages the feedback of static analysis tools such as Infer and CppCheck to mitigate security vulnerabilities in LLM-generated programs. Our evaluation in a real-world benchmark with 751 automatically generated vulnerable subjects demonstrates Codexity can prevent 60% of the vulnerabilities being exposed to the software developer.

[Arxiv](https://arxiv.org/abs/2405.03927)