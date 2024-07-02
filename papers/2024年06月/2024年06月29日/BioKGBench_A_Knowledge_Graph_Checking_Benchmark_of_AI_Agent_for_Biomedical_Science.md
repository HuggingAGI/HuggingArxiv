# BioKGBench：生物医学领域AI代理的知识图谱验证基准

发布时间：2024年06月29日

`Agent` `生物医学` `知识图谱`

> BioKGBench: A Knowledge Graph Checking Benchmark of AI Agent for Biomedical Science

# 摘要

> AI Scientist 在生物医学领域的应用日益受到瞩目，其中一种常见策略是构建由大型语言模型 (LLM) 驱动的辅助代理。然而，评估这些系统的方法要么直接依赖 LLM 的问答 (QA)，要么采用生物医学实验方式。从 AI Scientist 的角度出发，如何精准地基准测试生物医学代理仍是一个未被充分探索的领域。受科学家核心能力——理解文献的启发，我们推出了 BioKGBench。与仅侧重于事实问答的传统基准不同，LLM 在此方面存在幻觉问题，我们将“理解文献”细分为两个基本能力：一是通过科学主张验证理解研究论文中的非结构化文本，二是与结构化知识图谱问答 (KGQA) 交互的能力。接着，我们设计了名为 KGCheck 的新代理任务，结合 KGQA 和基于领域的检索增强生成 (RAG) 来揭示现有大规模知识图谱数据库中的事实错误。我们为两个基本任务收集了超过两千个数据，并为代理任务准备了 225 个高质量注释数据。令人惊讶的是，顶尖的日常和生物医学代理在我们的基准测试中表现不佳。为此，我们提出了一个简单而有效的基线——BKGAgent。在广泛使用的热门知识图谱上，我们发现了超过 90 个事实错误，为代理提供了发现机会，并验证了我们方法的有效性。相关代码和数据已公开在 https://github.com/westlake-autolab/BioKGBench。

> Pursuing artificial intelligence for biomedical science, a.k.a. AI Scientist, draws increasing attention, where one common approach is to build a copilot agent driven by Large Language Models (LLMs). However, to evaluate such systems, people either rely on direct Question-Answering (QA) to the LLM itself, or in a biomedical experimental manner. How to precisely benchmark biomedical agents from an AI Scientist perspective remains largely unexplored. To this end, we draw inspiration from one most important abilities of scientists, understanding the literature, and introduce BioKGBench. In contrast to traditional evaluation benchmark that only focuses on factual QA, where the LLMs are known to have hallucination issues, we first disentangle "Understanding Literature" into two atomic abilities, i) "Understanding" the unstructured text from research papers by performing scientific claim verification, and ii) Ability to interact with structured Knowledge-Graph Question-Answering (KGQA) as a form of "Literature" grounding. We then formulate a novel agent task, dubbed KGCheck, using KGQA and domain-based Retrieval-Augmented Generation (RAG) to identify the factual errors of existing large-scale knowledge graph databases. We collect over two thousand data for two atomic tasks and 225 high-quality annotated data for the agent task. Surprisingly, we discover that state-of-the-art agents, both daily scenarios and biomedical ones, have either failed or inferior performance on our benchmark. We then introduce a simple yet effective baseline, dubbed BKGAgent. On the widely used popular knowledge graph, we discover over 90 factual errors which provide scenarios for agents to make discoveries and demonstrate the effectiveness of our approach. The code and data are available at https://github.com/westlake-autolab/BioKGBench.

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x1.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/subKG.jpg)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/BKGAgent.jpg)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/restrict_corpus_exp.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/errorcase.jpg)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x2.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x3.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x4.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x5.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x7.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x8.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x9.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x10.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x11.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x12.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x13.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x14.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x15.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x16.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x17.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x18.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x19.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x20.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x21.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x22.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x23.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x24.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x25.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x26.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x27.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x28.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x29.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x30.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x31.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x32.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x33.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x34.png)

![BioKGBench：生物医学领域AI代理的知识图谱验证基准](../../../paper_images/2407.00466/x35.png)

[Arxiv](https://arxiv.org/abs/2407.00466)