# 关于大型语言模型的代码重构能力的实证研究

发布时间：2024年11月04日

`LLM应用` `软件开发` `代码重构`

> An Empirical Study on the Code Refactoring Capability of Large Language Models

# 摘要

> 大型语言模型（LLMs）已显示出通过自动代码生成和重构来增强软件开发的潜力，减少开发时间并提高代码质量。本研究对 StarCoder2 进行了实证评估，这是一个针对代码生成优化的 LLM，在 30 个开源 Java 项目中进行代码重构。我们将 StarCoder2 的性能与人类开发人员进行比较，重点关注（1）代码质量改进，（2）重构的类型和有效性，以及（3）通过一次性和思维链提示的增强。我们的结果表明，StarCoder2 减少代码异味的程度比开发人员高出 20.1％，在诸如长语句和幻数等系统性问题上表现出色，而开发人员在处理复杂的、依赖上下文的问题方面表现更好。一次性提示使单元测试通过率提高了 6.15％，代码异味减少率提高了 3.52％。每个输入生成五个重构进一步使通过率提高了 28.8％，这表明将一次性提示与多个重构相结合可优化性能。这些发现为 StarCoder2 的潜力以及将 LLMs 集成到软件重构中的最佳实践提供了见解，支持在实际应用中更高效和有效地改进代码。

> Large Language Models (LLMs) have shown potential to enhance software development through automated code generation and refactoring, reducing development time and improving code quality. This study empirically evaluates StarCoder2, an LLM optimized for code generation, in refactoring code across 30 open-source Java projects. We compare StarCoder2's performance against human developers, focusing on (1) code quality improvements, (2) types and effectiveness of refactorings, and (3) enhancements through one-shot and chain-of-thought prompting. Our results indicate that StarCoder2 reduces code smells by 20.1% more than developers, excelling in systematic issues like Long Statement and Magic Number, while developers handle complex, context-dependent issues better. One-shot prompting increases the unit test pass rate by 6.15% and improves code smell reduction by 3.52%. Generating five refactorings per input further increases the pass rate by 28.8%, suggesting that combining one-shot prompting with multiple refactorings optimizes performance. These findings provide insights into StarCoder2's potential and best practices for integrating LLMs into software refactoring, supporting more efficient and effective code improvement in real-world applications.

[Arxiv](https://arxiv.org/abs/2411.02320)