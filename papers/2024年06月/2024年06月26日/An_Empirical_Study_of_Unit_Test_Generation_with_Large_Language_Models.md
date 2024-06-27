# 大型语言模型在单元测试生成领域的实证探索

发布时间：2024年06月26日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在自动化单元测试生成中的应用，特别是在开源模型中的应用。它比较了不同结构和规模的开源LLMs，并评估了提示策略对性能的影响。这与LLM的理论研究不同，因为它关注的是LLM在实际软件开发任务中的应用，而不是模型本身的理论基础或机制。此外，它也不涉及Agent或RAG的相关概念。因此，最合适的分类是LLM应用。` `软件开发` `自动化测试`

> An Empirical Study of Unit Test Generation with Large Language Models

# 摘要

> 单元测试在软件开发中至关重要，但手动编写既费时又具挑战性。大型语言模型（LLMs）的出现为自动化单元测试生成开辟了新途径。尽管现有研究多聚焦于闭源模型如ChatGPT和CodeX，但开源LLMs在数据隐私保护和某些任务上的表现已显示出其优势。有效的提示策略对发挥LLMs潜力至关重要。本研究首次基于17个Java项目，对比了五种不同结构和规模的开源LLMs，以及全面的评估指标，揭示了提示因素对性能的显著影响，并与商业GPT-4及传统工具Evosuite进行了比较，指出了基于LLM的单元测试生成中的局限。研究结果为未来基于LLM的单元测试生成提供了指导和启示。

> Unit testing is an essential activity in software development for verifying the correctness of software components. However, manually writing unit tests is challenging and time-consuming. The emergence of Large Language Models (LLMs) offers a new direction for automating unit test generation. Existing research primarily focuses on closed-source LLMs (e.g., ChatGPT and CodeX) with fixed prompting strategies, leaving the capabilities of advanced open-source LLMs with various prompting settings unexplored. Particularly, open-source LLMs offer advantages in data privacy protection and have demonstrated superior performance in some tasks. Moreover, effective prompting is crucial for maximizing LLMs' capabilities. In this paper, we conduct the first empirical study to fill this gap, based on 17 Java projects, five widely-used open-source LLMs with different structures and parameter sizes, and comprehensive evaluation metrics. Our findings highlight the significant influence of various prompt factors, show the performance of open-source LLMs compared to the commercial GPT-4 and the traditional Evosuite, and identify limitations in LLM-based unit test generation. We then derive a series of implications from our study to guide future research and practical use of LLM-based unit test generation.

[Arxiv](https://arxiv.org/abs/2406.18181)