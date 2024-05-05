# 自组织智能体：构建超大规模代码生成与优化的大型语言模型多智能体框架。

发布时间：2024年04月02日

`Agent` `软件开发` `自动代码生成`

> Self-Organized Agents: A LLM Multi-Agent Framework toward Ultra Large-Scale Code Generation and Optimization

# 摘要

> 最新的自动代码生成技术，借助大型语言模型（LLM）代理，正将我们推向自动化软件开发的新纪元。不过，目前的单一代理方法在处理大规模、复杂代码库的生成与优化时，因上下文长度限制而受限。为解决这一问题，我们设计了自组织多代理框架（SoA），这是一个创新的多代理系统，旨在实现大规模代码的高效生成与优化。在SoA框架下，各代理自主运作，负责生成和调整代码片段，同时协同合作，共同构建完整的代码库。该框架的核心优势在于能够根据问题的复杂性自动增减代理数量，实现动态扩展。这意味着，随着代理数量的增加，整体代码量可以无限扩展，而每个代理所管理的代码量却保持不变。我们在HumanEval基准测试中对SoA进行了评估，结果显示，相较于单一代理系统，SoA的每个代理处理的代码量更少，但整体生成的代码量却显著增加。此外，SoA在Pass@1准确度上比单一代理系统高出5%，显示出其强大的性能。

> Recent advancements in automatic code generation using large language model (LLM) agent have brought us closer to the future of automated software development. However, existing single-agent approaches face limitations in generating and improving large-scale, complex codebases due to constraints in context length. To tackle this challenge, we propose Self-Organized multi-Agent framework (SoA), a novel multi-agent framework that enables the scalable and efficient generation and optimization of large-scale code. In SoA, self-organized agents operate independently to generate and modify code components while seamlessly collaborating to construct the overall codebase. A key feature of our framework is the automatic multiplication of agents based on problem complexity, allowing for dynamic scalability. This enables the overall code volume to be increased indefinitely according to the number of agents, while the amount of code managed by each agent remains constant. We evaluate SoA on the HumanEval benchmark and demonstrate that, compared to a single-agent system, each agent in SoA handles significantly less code, yet the overall generated code is substantially greater. Moreover, SoA surpasses the powerful single-agent baseline by 5% in terms of Pass@1 accuracy.

![自组织智能体：构建超大规模代码生成与优化的大型语言模型多智能体框架。](../../../paper_images/2404.02183/x1.png)

![自组织智能体：构建超大规模代码生成与优化的大型语言模型多智能体框架。](../../../paper_images/2404.02183/x2.png)

![自组织智能体：构建超大规模代码生成与优化的大型语言模型多智能体框架。](../../../paper_images/2404.02183/x3.png)

![自组织智能体：构建超大规模代码生成与优化的大型语言模型多智能体框架。](../../../paper_images/2404.02183/x4.png)

![自组织智能体：构建超大规模代码生成与优化的大型语言模型多智能体框架。](../../../paper_images/2404.02183/x5.png)

[Arxiv](https://arxiv.org/abs/2404.02183)