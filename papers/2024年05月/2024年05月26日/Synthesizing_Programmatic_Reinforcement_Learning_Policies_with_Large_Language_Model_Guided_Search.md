# 借助大型语言模型引导的搜索，合成程序化强化学习策略

发布时间：2024年05月26日

`Agent

理由：这篇论文主要讨论了程序化强化学习（PRL）中的一个具体方法，即LLM引导搜索框架（LLM-GS），并探讨了如何利用大型语言模型（LLM）来提高搜索效率和生成精确程序。这个框架涉及到了利用LLM的能力来辅助生成和优化程序，这在强化学习中通常与智能体的策略生成和优化相关。因此，这篇论文更符合Agent分类，因为它关注的是如何通过LLM来增强智能体（Agent）在特定任务中的表现。` `编程语言`

> Synthesizing Programmatic Reinforcement Learning Policies with Large Language Model Guided Search

# 摘要

> 程序化强化学习（PRL）通过程序表示策略，旨在实现可解释性和泛化，已展现出潜力。然而，当前顶尖的PRL方法因样本效率低下而受限，需要大量程序与环境的交互。为此，我们提出了LLM引导搜索框架（LLM-GS），利用LLM的编程知识和常识推理提升搜索效率。针对LLM在特定领域语言（DSL）中生成精确程序的难题，我们采用了Pythonic-DSL策略，先让LLM生成Python代码，再转换为DSL程序。此外，我们设计了计划性爬山算法，以高效探索程序空间并持续优化程序。在Karel领域的实验验证了LLM-GS框架的高效与有效性，消融研究也证实了Pythonic-DSL策略和计划性爬山算法的重要性。

> Programmatic reinforcement learning (PRL) has been explored for representing policies through programs as a means to achieve interpretability and generalization. Despite promising outcomes, current state-of-the-art PRL methods are hindered by sample inefficiency, necessitating tens of millions of program-environment interactions. To tackle this challenge, we introduce a novel LLM-guided search framework (LLM-GS). Our key insight is to leverage the programming expertise and common sense reasoning of LLMs to enhance the efficiency of assumption-free, random-guessing search methods. We address the challenge of LLMs' inability to generate precise and grammatically correct programs in domain-specific languages (DSLs) by proposing a Pythonic-DSL strategy - an LLM is instructed to initially generate Python codes and then convert them into DSL programs. To further optimize the LLM-generated programs, we develop a search algorithm named Scheduled Hill Climbing, designed to efficiently explore the programmatic search space to consistently improve the programs. Experimental results in the Karel domain demonstrate the superior effectiveness and efficiency of our LLM-GS framework. Extensive ablation studies further verify the critical role of our Pythonic-DSL strategy and Scheduled Hill Climbing algorithm.

![借助大型语言模型引导的搜索，合成程序化强化学习策略](../../../paper_images/2405.16450/x1.png)

![借助大型语言模型引导的搜索，合成程序化强化学习策略](../../../paper_images/2405.16450/x2.png)

![借助大型语言模型引导的搜索，合成程序化强化学习策略](../../../paper_images/2405.16450/stairclimbersparse.png)

![借助大型语言模型引导的搜索，合成程序化强化学习策略](../../../paper_images/2405.16450/mazesparse.png)

![借助大型语言模型引导的搜索，合成程序化强化学习策略](../../../paper_images/2405.16450/fourcorners.png)

![借助大型语言模型引导的搜索，合成程序化强化学习策略](../../../paper_images/2405.16450/topoff.png)

![借助大型语言模型引导的搜索，合成程序化强化学习策略](../../../paper_images/2405.16450/harvester.png)

![借助大型语言模型引导的搜索，合成程序化强化学习策略](../../../paper_images/2405.16450/cleanhouse.png)

![借助大型语言模型引导的搜索，合成程序化强化学习策略](../../../paper_images/2405.16450/doorkey.png)

![借助大型语言模型引导的搜索，合成程序化强化学习策略](../../../paper_images/2405.16450/onestroke.png)

![借助大型语言模型引导的搜索，合成程序化强化学习策略](../../../paper_images/2405.16450/seeder.png)

![借助大型语言模型引导的搜索，合成程序化强化学习策略](../../../paper_images/2405.16450/snake.png)

![借助大型语言模型引导的搜索，合成程序化强化学习策略](../../../paper_images/2405.16450/x4.png)

![借助大型语言模型引导的搜索，合成程序化强化学习策略](../../../paper_images/2405.16450/doorkey.png)

![借助大型语言模型引导的搜索，合成程序化强化学习策略](../../../paper_images/2405.16450/cleanhouse.png)

![借助大型语言模型引导的搜索，合成程序化强化学习策略](../../../paper_images/2405.16450/doorkey.png)

![借助大型语言模型引导的搜索，合成程序化强化学习策略](../../../paper_images/2405.16450/cleanhouse.png)

![借助大型语言模型引导的搜索，合成程序化强化学习策略](../../../paper_images/2405.16450/revised_fig.png)

![借助大型语言模型引导的搜索，合成程序化强化学习策略](../../../paper_images/2405.16450/x5.png)

![借助大型语言模型引导的搜索，合成程序化强化学习策略](../../../paper_images/2405.16450/x6.png)

![借助大型语言模型引导的搜索，合成程序化强化学习策略](../../../paper_images/2405.16450/x7.png)

![借助大型语言模型引导的搜索，合成程序化强化学习策略](../../../paper_images/2405.16450/x8.png)

![借助大型语言模型引导的搜索，合成程序化强化学习策略](../../../paper_images/2405.16450/x9.png)

![借助大型语言模型引导的搜索，合成程序化强化学习策略](../../../paper_images/2405.16450/x10.png)

![借助大型语言模型引导的搜索，合成程序化强化学习策略](../../../paper_images/2405.16450/x11.png)

![借助大型语言模型引导的搜索，合成程序化强化学习策略](../../../paper_images/2405.16450/x12.png)

![借助大型语言模型引导的搜索，合成程序化强化学习策略](../../../paper_images/2405.16450/x13.png)

![借助大型语言模型引导的搜索，合成程序化强化学习策略](../../../paper_images/2405.16450/x14.png)

![借助大型语言模型引导的搜索，合成程序化强化学习策略](../../../paper_images/2405.16450/doorkey_revising_initial.png)

![借助大型语言模型引导的搜索，合成程序化强化学习策略](../../../paper_images/2405.16450/doorkey_revising_demonstration_ends.png)

![借助大型语言模型引导的搜索，合成程序化强化学习策略](../../../paper_images/2405.16450/doorkey_revising_ending.png)

[Arxiv](https://arxiv.org/abs/2405.16450)