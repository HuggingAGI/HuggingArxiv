# 一个用于生成基于 LLM 的模糊驱动程序的代码知识图增强系统

发布时间：2024年11月18日

`LLM应用` `软件测试` `代码知识图谱`

> A Code Knowledge Graph-Enhanced System for LLM-Based Fuzz Driver Generation

# 摘要

> 大型语言模型（LLMs）先进编程能力的迅猛发展，为软件测试的创新手段开辟了道路。模糊测试作为提升软件可靠性、检测漏洞的关键手段，往往依赖人工编写的模糊驱动程序，这限制了其可扩展性与效率。为解决此难题，我们推出了 CodeGraphGPT 这一全新系统，它将代码知识图谱与 LLM 驱动的智能代理相融合，实现模糊驱动程序生成过程的自动化。把模糊驱动程序的创建视作代码生成任务，CodeGraphGPT 借助程序分析构建代码库的知识图谱，其中节点代表诸如函数或文件之类的代码实体，边则捕捉它们的关系。这让系统能够生成定制的模糊驱动程序和输入种子，解决编译错误，分析崩溃报告，同时适应特定的 API 使用场景。另外，对知识图谱的查询有助于明确精准的测试目标，并在模糊循环中明确每个模糊驱动程序的目的。我们在八个开源软件项目上对 CodeGraphGPT 进行评估，相比前沿方法，代码覆盖率平均提升 8.73％。而且，它使崩溃案例分析中的人工工作量降低 84.4％，并找出 11 个现实中的错误，包括 9 个此前未被报告的错误。此项工作凸显了将 LLMs 与代码知识图谱相结合如何强化模糊驱动程序的生成，为漏洞检测和软件质量提升提供了高效的解决方案。

> The rapid development of large language models (LLMs) with advanced programming capabilities has paved the way for innovative approaches in software testing. Fuzz testing, a cornerstone for improving software reliability and detecting vulnerabilities, often relies on manually written fuzz drivers, limiting scalability and efficiency. To address this challenge, we propose CodeGraphGPT, a novel system that integrates code knowledge graphs with an LLM-powered intelligent agent to automate the fuzz driver generation process. By framing fuzz driver creation as a code generation task, CodeGraphGPT leverages program analysis to construct a knowledge graph of code repositories, where nodes represent code entities, such as functions or files, and edges capture their relationships. This enables the system to generate tailored fuzz drivers and input seeds, resolve compilation errors, and analyze crash reports, all while adapting to specific API usage scenarios. Additionally, querying the knowledge graph helps identify precise testing targets and contextualize the purpose of each fuzz driver within the fuzzing loop. We evaluated CodeGraphGPT on eight open-source software projects, achieving an average improvement of 8.73\% in code coverage compared to state-of-the-art methods. Moreover, it reduced the manual workload in crash case analysis by 84.4\% and identified 11 real-world bugs, including nine previously unreported ones. This work highlights how integrating LLMs with code knowledge graphs enhances fuzz driver generation, offering an efficient solution for vulnerability detection and software quality improvement.

[Arxiv](https://arxiv.org/abs/2411.11532)