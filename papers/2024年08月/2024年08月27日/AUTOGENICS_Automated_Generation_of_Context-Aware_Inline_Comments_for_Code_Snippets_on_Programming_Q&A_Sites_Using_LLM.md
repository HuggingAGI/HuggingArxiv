# AUTOGENICS：利用 LLM 技术，自动为编程问答网站的代码片段生成智能内联注释，提升上下文感知能力。

发布时间：2024年08月27日

`LLM应用` `软件开发`

> AUTOGENICS: Automated Generation of Context-Aware Inline Comments for Code Snippets on Programming Q&A Sites Using LLM

# 摘要

> 源代码中的内联注释能提升理解、重用和可读性，但在 Stack Overflow 等问答网站上，由于时间限制，答案中的代码片段常缺乏注释。这导致在线代码示例难以理解和使用，尤其是对新手开发者。为此，我们开发了 AUTOGENICS 工具，利用大型语言模型为 SO 答案中的代码片段自动生成内联注释。我们通过随机选取 400 个代码片段并手动评估其生成的注释，发现 LLM 在此方面表现出色。此外，我们调查了 14 位 SO 用户，结果与手动评估相符，但对短代码片段效果不佳。为解决此问题，AUTOGENICS 通过提取问题文本的上下文并优化注释，提升了注释的质量。我们的评估显示，AUTOGENICS 生成的注释在四个关键指标上均优于标准 LLM。这一工具有望提高代码理解效率，节省开发者时间，并增强其学习和准确重用代码的能力。

> Inline comments in the source code facilitate easy comprehension, reusability, and enhanced readability. However, code snippets in answers on Q&A sites like Stack Overflow (SO) often lack comments because answerers volunteer their time and often skip comments or explanations due to time constraints. Existing studies show that these online code examples are difficult to read and understand, making it difficult for developers (especially novices) to use them correctly and leading to misuse. Given these challenges, we introduced AUTOGENICS, a tool designed to integrate with SO to generate effective inline comments for code snippets in SO answers exploiting large language models (LLMs). Our contributions are threefold. First, we randomly select 400 answer code snippets from SO and generate inline comments for them using LLMs. We then manually evaluate these comments' effectiveness using four key metrics: accuracy, adequacy, conciseness, and usefulness. Overall, LLMs demonstrate promising effectiveness in generating inline comments for SO answer code snippets. Second, we surveyed 14 active SO users to perceive the effectiveness of these inline comments. The survey results are consistent with our previous manual evaluation. However, according to our evaluation, LLMs-generated comments are less effective for shorter code snippets and sometimes produce noisy comments. Third, to address the gaps, we introduced AUTOGENICS, which extracts additional context from question texts and generates context-aware inline comments. It also optimizes comments by removing noise (e.g., comments in import statements and variable declarations). We evaluate the effectiveness of AUTOGENICS-generated comments using the same four metrics that outperform those of standard LLMs. AUTOGENICS might (a) enhance code comprehension, (b) save time, and improve developers' ability to learn and reuse code more accurately.

[Arxiv](https://arxiv.org/abs/2408.15411)