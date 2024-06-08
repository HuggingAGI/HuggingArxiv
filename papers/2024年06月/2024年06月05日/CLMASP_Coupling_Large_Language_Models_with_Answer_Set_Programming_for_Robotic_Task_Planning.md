# CLMASP：融合大型语言模型与答案集编程，助力机器人任务规划

发布时间：2024年06月05日

`Agent

这篇论文主要探讨了如何将大型语言模型（LLMs）生成的计划转化为机器人可执行的方案，特别是在有限制条件下的应用。论文提出的CLMASP方法结合了LLMs和答案集编程（ASP），以提高计划的可执行性。这种方法涉及到将LLM的输出转化为具体行动计划，适用于机器人的操作环境，因此属于Agent类别的研究，即如何使LLM生成的计划能够被智能体（如机器人）实际执行。` `机器人技术` `人工智能`

> CLMASP: Coupling Large Language Models with Answer Set Programming for Robotic Task Planning

# 摘要

> 大型语言模型（LLMs）具备广泛的基础知识和适度的推理能力，非常适合在开放世界中进行任务规划。但将LLM生成的计划转化为特定机器人可执行的方案，尤其是在有限制条件下，颇具挑战。本文提出的CLMASP方法，巧妙结合LLMs与答案集编程（ASP），有效克服了这一难题。ASP以其强大的机器人动作知识表示和推理能力著称。CLMASP首先由LLM生成初步计划框架，再通过向量数据库针对具体场景进行调整。随后，ASP程序利用机器人动作知识对计划进行精炼，将实施细节融入框架，确保LLM的抽象输出在实际机器人操作中得以实现。我们在VirtualHome平台上的实验显示，CLMASP的执行率从LLM方法的不足2%大幅提升至超过90%，效果显著。

> Large Language Models (LLMs) possess extensive foundational knowledge and moderate reasoning abilities, making them suitable for general task planning in open-world scenarios. However, it is challenging to ground a LLM-generated plan to be executable for the specified robot with certain restrictions. This paper introduces CLMASP, an approach that couples LLMs with Answer Set Programming (ASP) to overcome the limitations, where ASP is a non-monotonic logic programming formalism renowned for its capacity to represent and reason about a robot's action knowledge. CLMASP initiates with a LLM generating a basic skeleton plan, which is subsequently tailored to the specific scenario using a vector database. This plan is then refined by an ASP program with a robot's action knowledge, which integrates implementation details into the skeleton, grounding the LLM's abstract outputs in practical robot contexts. Our experiments conducted on the VirtualHome platform demonstrate CLMASP's efficacy. Compared to the baseline executable rate of under 2% with LLM approaches, CLMASP significantly improves this to over 90%.

![CLMASP：融合大型语言模型与答案集编程，助力机器人任务规划](../../../paper_images/2406.03367/x1.png)

[Arxiv](https://arxiv.org/abs/2406.03367)