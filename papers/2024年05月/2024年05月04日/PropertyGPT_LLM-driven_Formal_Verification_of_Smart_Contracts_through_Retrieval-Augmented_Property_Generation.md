# PropertyGPT，一种利用大型语言模型（LLM）进行智能合约形式化验证的创新方法，通过增强检索的属性生成技术，为智能合约的安全性分析提供了新的视角。

发布时间：2024年05月04日

`LLM应用` `软件工程`

> PropertyGPT: LLM-driven Formal Verification of Smart Contracts through Retrieval-Augmented Property Generation

# 摘要

> 本文着眼于大型语言模型（LLMs）的最新发展，研究了如何利用尖端的LLMs，如GPT-4，来转化现有的人工编写属性（例如Certora审计报告中的属性），并为未知代码自动创建定制属性。我们通过将现有属性嵌入向量数据库并检索参考属性，利用基于LLM的in-context learning来生成新属性。尽管这一基本流程较为简单，但要确保生成的属性不仅（i）可编译，（ii）恰当，且（iii）能在运行时验证，却面临诸多挑战。为此，我们利用编译和静态分析反馈作为外部参考，指导LLMs逐步改进属性生成。在评估属性的恰当性时，我们从多个相似性维度进行排名，并采用加权算法筛选出前K个属性作为最终输出。至于属性的可验证性，我们专门设计了一个证明器来形式化验证属性的正确性。我们将这些方法集成到一个创新的系统中，名为PropertyGPT，该系统收录了来自23个Certora项目的623个人工编写的属性。实验结果表明，PropertyGPT能够产生全面且高品质的属性，其召回率达到了80%。此外，PropertyGPT成功识别了37个测试中的26个CVE/攻击事件，并揭露了12个零日漏洞，赢得了总计8256美元的漏洞赏金。

> With recent advances in large language models (LLMs), this paper explores the potential of leveraging state-of-the-art LLMs, such as GPT-4, to transfer existing human-written properties (e.g., those from Certora auditing reports) and automatically generate customized properties for unknown code. To this end, we embed existing properties into a vector database and retrieve a reference property for LLM-based in-context learning to generate a new prop- erty for a given code. While this basic process is relatively straight- forward, ensuring that the generated properties are (i) compilable, (ii) appropriate, and (iii) runtime-verifiable presents challenges. To address (i), we use the compilation and static analysis feedback as an external oracle to guide LLMs in iteratively revising the generated properties. For (ii), we consider multiple dimensions of similarity to rank the properties and employ a weighted algorithm to identify the top-K properties as the final result. For (iii), we design a dedicated prover to formally verify the correctness of the generated prop- erties. We have implemented these strategies into a novel system called PropertyGPT, with 623 human-written properties collected from 23 Certora projects. Our experiments show that PropertyGPT can generate comprehensive and high-quality properties, achieving an 80% recall compared to the ground truth. It successfully detected 26 CVEs/attack incidents out of 37 tested and also uncovered 12 zero-day vulnerabilities, resulting in $8,256 bug bounty rewards.

[Arxiv](https://arxiv.org/abs/2405.02580)