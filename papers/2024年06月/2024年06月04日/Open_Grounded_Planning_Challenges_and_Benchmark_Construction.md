# 开放基础规划：挑战与基准建设探索

发布时间：2024年06月04日

`Agent

这篇论文主要关注的是如何利用大型语言模型（LLMs）进行类人规划，特别是在开放且可执行的环境中的规划任务。它提出了一项新任务——开放基础规划，并为此设立了基准，测试了当前顶尖的LLMs及规划策略。这个研究方向更偏向于Agent的范畴，因为它涉及到模型的自主决策和规划能力，这是Agent研究的核心内容。因此，将这篇论文分类到Agent是合适的。` `人工智能`

> Open Grounded Planning: Challenges and Benchmark Construction

# 摘要

> 随着大型语言模型（LLMs）的兴起，人们越来越关注如何利用这些模型进行类人规划。现有研究要么依赖LLMs的语言生成能力来制定自由风格的计划，要么通过强化学习在受限环境中优化决策。但这些方法与现实世界中开放且可执行的规划需求相去甚远。本文提出了一项新任务——开放基础规划，旨在让模型根据可变的动作集生成切实可行的计划。我们为此任务设立了一个涵盖多领域的基准，并测试了当前顶尖的LLMs及五种规划策略，发现它们在开放领域的基础规划上仍显不足。本文不仅定义了这一新任务，还为其奠定了数据基础，并指出了未来研究的方向和挑战。

> The emergence of large language models (LLMs) has increasingly drawn attention to the use of LLMs for human-like planning. Existing work on LLM-based planning either focuses on leveraging the inherent language generation capabilities of LLMs to produce free-style plans, or employs reinforcement learning approaches to learn decision-making for a limited set of actions within restricted environments. However, both approaches exhibit significant discrepancies from the open and executable requirements in real-world planning. In this paper, we propose a new planning task--open grounded planning. The primary objective of open grounded planning is to ask the model to generate an executable plan based on a variable action set, thereby ensuring the executability of the produced plan. To this end, we establishes a benchmark for open grounded planning spanning a wide range of domains. Then we test current state-of-the-art LLMs along with five planning approaches, revealing that existing LLMs and methods still struggle to address the challenges posed by grounded planning in open domains. The outcomes of this paper define and establish a foundational dataset for open grounded planning, and shed light on the potential challenges and future directions of LLM-based planning.

![开放基础规划：挑战与基准建设探索](../../../paper_images/2406.02903/x1.png)

![开放基础规划：挑战与基准建设探索](../../../paper_images/2406.02903/x2.png)

![开放基础规划：挑战与基准建设探索](../../../paper_images/2406.02903/x3.png)

![开放基础规划：挑战与基准建设探索](../../../paper_images/2406.02903/x4.png)

![开放基础规划：挑战与基准建设探索](../../../paper_images/2406.02903/x5.png)

![开放基础规划：挑战与基准建设探索](../../../paper_images/2406.02903/x6.png)

![开放基础规划：挑战与基准建设探索](../../../paper_images/2406.02903/x7.png)

![开放基础规划：挑战与基准建设探索](../../../paper_images/2406.02903/x8.png)

![开放基础规划：挑战与基准建设探索](../../../paper_images/2406.02903/x9.png)

![开放基础规划：挑战与基准建设探索](../../../paper_images/2406.02903/x10.png)

![开放基础规划：挑战与基准建设探索](../../../paper_images/2406.02903/x11.png)

![开放基础规划：挑战与基准建设探索](../../../paper_images/2406.02903/x12.png)

![开放基础规划：挑战与基准建设探索](../../../paper_images/2406.02903/x13.png)

![开放基础规划：挑战与基准建设探索](../../../paper_images/2406.02903/x14.png)

![开放基础规划：挑战与基准建设探索](../../../paper_images/2406.02903/x15.png)

![开放基础规划：挑战与基准建设探索](../../../paper_images/2406.02903/x16.png)

![开放基础规划：挑战与基准建设探索](../../../paper_images/2406.02903/x17.png)

[Arxiv](https://arxiv.org/abs/2406.02903)