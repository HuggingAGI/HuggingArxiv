# LLMs 能否生成捕获程序实际或预期行为的测试预言？

发布时间：2024年10月28日

`LLM应用` `软件测试` `软件开发`

> Do LLMs generate test oracles that capture the actual or the expected program behaviour?

# 摘要

> 软件测试是软件开发周期中提升代码质量的关键环节。通常而言，单元测试由测试前缀和测试预言构成，测试预言能捕捉开发人员期望的行为。传统测试生成技术（如 Randoop 和 Evosuite）存在一个已知的局限性，即它们所生成的测试预言捕捉的是实际的程序行为，而非预期行为。近来的方法借助在海量数据上训练的大型语言模型（LLMs）来生成类似开发人员的代码和测试用例。我们探究 LLM 生成的测试预言究竟是捕捉了实际的还是预期的软件行为。为此，我们通过研究 LLMs 在测试预言分类和生成这两项任务上的表现开展了对照实验来解答此问题。该研究涵盖了针对 24 个开源 Java 库的由开发人员编写的以及自动生成的测试用例和预言，还有不同的经过良好测试的提示。我们的研究结果表明，基于 LLM 的测试生成方法同样易于生成捕捉实际程序行为而非预期行为的预言。另外，LLMs 更擅长生成测试预言，而非对正确的进行分类，并且当代码包含有意义的测试或变量名称时，能够生成更优的测试预言。最后，LLM 生成的测试预言比 Evosuite 生成的具有更强的故障检测能力。

> Software testing is an essential part of the software development cycle to improve the code quality. Typically, a unit test consists of a test prefix and a test oracle which captures the developer's intended behaviour. A known limitation of traditional test generation techniques (e.g. Randoop and Evosuite) is that they produce test oracles that capture the actual program behaviour rather than the expected one. Recent approaches leverage Large Language Models (LLMs), trained on an enormous amount of data, to generate developer-like code and test cases. We investigate whether the LLM-generated test oracles capture the actual or expected software behaviour. We thus, conduct a controlled experiment to answer this question, by studying LLMs performance on two tasks, namely, test oracle classification and generation. The study includes developer-written and automatically generated test cases and oracles for 24 open-source Java repositories, and different well tested prompts. Our findings show that LLM-based test generation approaches are also prone on generating oracles that capture the actual program behaviour rather than the expected one. Moreover, LLMs are better at generating test oracles rather than classifying the correct ones, and can generate better test oracles when the code contains meaningful test or variable names. Finally, LLM-generated test oracles have higher fault detection potential than the Evosuite ones.

[Arxiv](https://arxiv.org/abs/2410.21136)