# CLMASP：结合大型语言模型与答案集编程，助力机器人任务规划

发布时间：2024年06月05日

`Agent

理由：这篇论文主要探讨了如何将大型语言模型（LLMs）生成的计划转化为机器人可执行的方案，通过结合LLMs与答案集编程（ASP）来实现这一目标。这种方法涉及到了将抽象的LLM输出转化为具体的机器人操作，这涉及到代理（Agent）的行为规划和执行。因此，这篇论文更符合Agent分类，因为它关注的是如何使LLM生成的计划能够被机器人这样的实体执行。` `机器人技术` `人工智能`

> CLMASP: Coupling Large Language Models with Answer Set Programming for Robotic Task Planning

# 摘要

> 大型语言模型（LLMs）凭借其广泛的基础知识和适度的推理能力，成为开放世界任务规划的得力助手。然而，将这些模型生成的计划转化为特定机器人可执行的方案，却是一大挑战。为此，本文提出了CLMASP方法，它巧妙地将LLMs与答案集编程（ASP）结合，ASP以其非单调逻辑编程的特性，擅长处理机器人动作知识的表示与推理。CLMASP首先由LLM草拟计划框架，随后通过向量数据库针对特定场景进行定制。接着，ASP程序利用机器人动作知识对计划进行精炼，将抽象的LLM输出转化为实际可行的机器人操作。我们在VirtualHome平台上的实验显示，CLMASP的效果显著，将可执行率从LLM方法的不足2%提升至超过90%。

> Large Language Models (LLMs) possess extensive foundational knowledge and moderate reasoning abilities, making them suitable for general task planning in open-world scenarios. However, it is challenging to ground a LLM-generated plan to be executable for the specified robot with certain restrictions. This paper introduces CLMASP, an approach that couples LLMs with Answer Set Programming (ASP) to overcome the limitations, where ASP is a non-monotonic logic programming formalism renowned for its capacity to represent and reason about a robot's action knowledge. CLMASP initiates with a LLM generating a basic skeleton plan, which is subsequently tailored to the specific scenario using a vector database. This plan is then refined by an ASP program with a robot's action knowledge, which integrates implementation details into the skeleton, grounding the LLM's abstract outputs in practical robot contexts. Our experiments conducted on the VirtualHome platform demonstrate CLMASP's efficacy. Compared to the baseline executable rate of under 2% with LLM approaches, CLMASP significantly improves this to over 90%.

![CLMASP：结合大型语言模型与答案集编程，助力机器人任务规划](../../../paper_images/2406.03367/x1.png)

[Arxiv](https://arxiv.org/abs/2406.03367)