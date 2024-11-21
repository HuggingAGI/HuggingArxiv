# 仓库层面的组合代码翻译与验证

发布时间：2024年10月31日

`LLM应用` `软件开发` `代码翻译`

> Repository-Level Compositional Code Translation and Validation

# 摘要

> 代码翻译能把程序从一种编程语言（PL）转换成另一种。已有若干基于规则的代码转换器被设计出来，用于实现不同 PL 对之间的代码翻译自动化。然而，随着 PL 的演进，这些规则可能会过时，也无法推广到其他 PL。近来的研究探索了借助大型语言模型（LLMs）来自动化代码翻译。一个关键发现是，这类技术在精心打造的基准测试中或许表现出色，但难以推广到具有依赖关系、自定义类型、PL 特定功能等的真实世界项目的规模和复杂度上。
  我们提出了 AlphaTrans，这是一种神经符号方法，用于实现存储库级别的代码翻译自动化。AlphaTrans 对源代码和测试代码都进行翻译，并采用多重验证级别来确保翻译能保留源程序的功能。为了给 LLMs 分解问题，AlphaTrans 借助程序分析将程序分解为片段，并按反向调用顺序进行翻译。我们利用 AlphaTrans 翻译了十个由<836, 8575, 2719>个类、方法和测试构成的真实世界开源项目。AlphaTrans 翻译了这些项目的整个存储库，涵盖 6899 个源代码片段。99.1%的翻译代码片段语法正确，AlphaTrans 对 25.8%的翻译进行了运行时行为和功能正确性的验证。平均而言，集成的翻译和验证需 36 小时来完成一个项目的翻译，展现出其在实际应用中的可扩展性。对于语法或语义不正确的翻译，AlphaTrans 会生成一份报告，包含现有翻译、堆栈跟踪、测试错误或断言失败。我们将这些成果提供给两位开发人员，用于修复四个项目中的翻译错误。他们平均能在 20.1 小时内修复问题，并实现所有测试通过。

> Code translation transforms programs from one programming language (PL) to another. Several rule-based transpilers have been designed to automate code translation between different pairs of PLs. However, the rules can become obsolete as the PLs evolve and cannot generalize to other PLs. Recent studies have explored the automation of code translation using Large Language Models (LLMs). One key observation is that such techniques may work well for crafted benchmarks but fail to generalize to the scale and complexity of real-world projects with dependencies, custom types, PL-specific features, etc.
  We propose AlphaTrans, a neuro-symbolic approach to automate repository-level code translation. AlphaTrans translates both source and test code, and employs multiple levels of validation to ensure the translation preserves the functionality of the source program. To break down the problem for LLMs, AlphaTrans leverages program analysis to decompose the program into fragments and translates them in the reverse call order. We leveraged AlphaTrans to translate ten real-world open-source projects consisting of <836, 8575, 2719> classes, methods, and tests. AlphaTrans translated the entire repository of these projects consisting of 6899 source code fragments. 99.1% of the translated code fragments are syntactically correct, and AlphaTrans validates the translations' runtime behavior and functional correctness for 25.8%. On average, the integrated translation and validation take 36 hours to translate a project, showing its scalability in practice. For the syntactically or semantically incorrect translations, AlphaTrans generates a report including existing translation, stack trace, test errors, or assertion failures. We provided these artifacts to two developers to fix the translation bugs in four projects. They were able to fix the issues in 20.1 hours on average and achieve all passing tests.

[Arxiv](https://arxiv.org/abs/2410.24117)