# PropertyGPT：利用大型语言模型（LLM）进行智能合约的形式化验证，通过增强检索的属性生成技术实现。

发布时间：2024年05月04日

`分类：LLM应用

这篇论文的摘要描述了如何利用大型语言模型（LLMs）来自动生成定制属性，这是一个典型的LLM应用场景。论文中提到了使用GPT-4这样的先进模型，并通过编译和静态分析反馈来改进属性生成，这些都是LLM应用的具体实践。此外，论文还介绍了一个名为PropertyGPT的系统，该系统在实验中表现出了良好的性能，这也是LLM应用的一个例子。因此，将这篇论文归类为LLM应用是合适的。` `软件工程` `程序验证`

> PropertyGPT: LLM-driven Formal Verification of Smart Contracts through Retrieval-Augmented Property Generation

# 摘要

> 本文借助大型语言模型（LLMs）的前沿进展，研究了如何利用如GPT-4这样的先进模型，将人类编写的属性（如Certora审计报告中的属性）进行转移，自动为未知代码创建定制属性。我们通过将现有属性嵌入向量数据库并检索参考属性，利用基于LLM的上下文学习生成新属性。尽管基本流程简单明了，但确保生成的属性既（i）可编译，（ii）合适，又（iii）可运行时验证，却颇具挑战。为此，我们利用编译和静态分析反馈作为外部指导，帮助LLMs逐步改进属性生成。在评估属性合适性时，我们从多个相似性维度进行排名，并采用加权算法筛选出前K个最佳属性。对于属性的运行时验证，我们开发了专门的证明器来形式化验证其正确性。这些策略已被集成到一个创新的系统中，名为PropertyGPT，它收集了23个Certora项目中的623个人类编写的属性。实验结果表明，PropertyGPT能够产出全面且优质的属性，与基准真值的召回率达到80%。该系统成功识别了37个测试中的26个CVE/攻击事件，并挖掘出12个零日漏洞，赢得了总计8256美元的漏洞赏金。

> With recent advances in large language models (LLMs), this paper explores the potential of leveraging state-of-the-art LLMs, such as GPT-4, to transfer existing human-written properties (e.g., those from Certora auditing reports) and automatically generate customized properties for unknown code. To this end, we embed existing properties into a vector database and retrieve a reference property for LLM-based in-context learning to generate a new prop- erty for a given code. While this basic process is relatively straight- forward, ensuring that the generated properties are (i) compilable, (ii) appropriate, and (iii) runtime-verifiable presents challenges. To address (i), we use the compilation and static analysis feedback as an external oracle to guide LLMs in iteratively revising the generated properties. For (ii), we consider multiple dimensions of similarity to rank the properties and employ a weighted algorithm to identify the top-K properties as the final result. For (iii), we design a dedicated prover to formally verify the correctness of the generated prop- erties. We have implemented these strategies into a novel system called PropertyGPT, with 623 human-written properties collected from 23 Certora projects. Our experiments show that PropertyGPT can generate comprehensive and high-quality properties, achieving an 80% recall compared to the ground truth. It successfully detected 26 CVEs/attack incidents out of 37 tested and also uncovered 12 zero-day vulnerabilities, resulting in $8,256 bug bounty rewards.

[Arxiv](https://arxiv.org/abs/2405.02580)