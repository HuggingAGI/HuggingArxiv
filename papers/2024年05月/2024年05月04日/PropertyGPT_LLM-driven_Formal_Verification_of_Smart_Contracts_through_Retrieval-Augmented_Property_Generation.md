# PropertyGPT：利用大型语言模型（LLM）进行智能合约的形式化验证，通过增强检索的属性生成技术实现。

发布时间：2024年05月04日

`LLM应用` `软件工程` `代码审计`

> PropertyGPT: LLM-driven Formal Verification of Smart Contracts through Retrieval-Augmented Property Generation

# 摘要

> 本文借助大型语言模型（LLMs）的前沿发展，探索了利用如GPT-4这样的先进模型，将人类编写的属性（如Certora审计报告中的属性）迁移并自动生成未知代码的定制属性的可能性。我们通过将现有属性嵌入向量数据库并检索参考属性，利用基于LLM的In-context learning为特定代码生成新属性。尽管这一基本流程较为简单，但确保生成的属性不仅（i）可编译，（ii）恰当，且（iii）能在运行时验证，却非易事。为应对（i）的挑战，我们利用编译和静态分析反馈作为外部指导，辅助LLMs逐步改进生成的属性。在（ii）方面，我们从多个相似性维度评估属性，并采用加权算法挑选出最佳的K个属性。对于（iii），我们专门设计了一个验证器来形式化地验证属性的正确性。这些策略已被集成到我们新开发的PropertyGPT系统中，该系统收录了来自23个Certora项目的623个人工编写的属性。实验结果表明，PropertyGPT能够产生全面且高品质的属性，其召回率达到了80%，并成功识别了37个测试中的26个CVE/攻击事件，同时揭露了12个零日漏洞，赢得了总计8256美元的漏洞赏金。

> With recent advances in large language models (LLMs), this paper explores the potential of leveraging state-of-the-art LLMs, such as GPT-4, to transfer existing human-written properties (e.g., those from Certora auditing reports) and automatically generate customized properties for unknown code. To this end, we embed existing properties into a vector database and retrieve a reference property for LLM-based in-context learning to generate a new prop- erty for a given code. While this basic process is relatively straight- forward, ensuring that the generated properties are (i) compilable, (ii) appropriate, and (iii) runtime-verifiable presents challenges. To address (i), we use the compilation and static analysis feedback as an external oracle to guide LLMs in iteratively revising the generated properties. For (ii), we consider multiple dimensions of similarity to rank the properties and employ a weighted algorithm to identify the top-K properties as the final result. For (iii), we design a dedicated prover to formally verify the correctness of the generated prop- erties. We have implemented these strategies into a novel system called PropertyGPT, with 623 human-written properties collected from 23 Certora projects. Our experiments show that PropertyGPT can generate comprehensive and high-quality properties, achieving an 80% recall compared to the ground truth. It successfully detected 26 CVEs/attack incidents out of 37 tested and also uncovered 12 zero-day vulnerabilities, resulting in $8,256 bug bounty rewards.

[Arxiv](https://arxiv.org/abs/2405.02580)