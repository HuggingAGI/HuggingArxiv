# 开发者能否巧妙引导？这是一项针对代码文档生成进行的控制实验研究。

发布时间：2024年08月01日

`LLM应用` `软件开发`

> Can Developers Prompt? A Controlled Experiment for Code Documentation Generation

# 摘要

> 大型语言模型（LLM）在自动化代码文档创建与维护等繁琐任务上潜力巨大，但开发人员如何有效引导LLM生成简洁实用的文档尚待探索。我们进行了一项实验，涉及20位专业人士和30名计算机科学学生，任务是为Python函数编写文档。实验组在类似ChatGPT的VS Code扩展中自由输入即兴提示，对照组则使用预设的少量样本提示。结果表明，无论是专业人士还是学生，大多未能掌握或运用提示工程技巧。学生们尤其觉得即兴提示生成的文档在可读性、简洁度和实用性上远逊于精心准备的提示。部分专业人士通过在即兴提示中加入“Docstring”关键词，提升了文档质量。学生期待更多提示制定支持，而专业人士则青睐即兴提示的灵活性。两组参与者均视工具为迭代优化文档的辅助手段，而非完美解决方案。未来研究需深入探讨开发人员的提示技能与偏好，以及他们在特定任务中的支持需求。

> Large language models (LLMs) bear great potential for automating tedious development tasks such as creating and maintaining code documentation. However, it is unclear to what extent developers can effectively prompt LLMs to create concise and useful documentation. We report on a controlled experiment with 20 professionals and 30 computer science students tasked with code documentation generation for two Python functions. The experimental group freely entered ad-hoc prompts in a ChatGPT-like extension of Visual Studio Code, while the control group executed a predefined few-shot prompt. Our results reveal that professionals and students were unaware of or unable to apply prompt engineering techniques. Especially students perceived the documentation produced from ad-hoc prompts as significantly less readable, less concise, and less helpful than documentation from prepared prompts. Some professionals produced higher quality documentation by just including the keyword Docstring in their ad-hoc prompts. While students desired more support in formulating prompts, professionals appreciated the flexibility of ad-hoc prompting. Participants in both groups rarely assessed the output as perfect. Instead, they understood the tools as support to iteratively refine the documentation. Further research is needed to understand which prompting skills and preferences developers have and which support they need for certain tasks.

[Arxiv](https://arxiv.org/abs/2408.00686)