# TRIP-PAL：结合大型语言模型与自动规划器，确保旅行规划无忧

发布时间：2024年06月14日

`Agent

理由：这篇论文介绍了一种名为TRIP-PAL的混合方法，它结合了大型语言模型（LLM）和自动规划器来解决旅行规划问题。在这个系统中，LLM负责收集和转换信息，而自动规划器则负责生成满足约束的旅行计划。这种结合了LLM和规划器的系统可以被视为一个智能代理（Agent），因为它能够根据用户的需求和约束条件自主地规划行动。因此，这篇论文更适合归类到Agent分类中。` `智能规划`

> TRIP-PAL: Travel Planning with Guarantees by Combining Large Language Models and Automated Planners

# 摘要

> 旅行规划是一项复杂任务，涉及在满足约束的同时，规划一系列访问地点的行动以提升用户满意度。传统方法通过特定形式语言定义问题，并从网络提取信息，再由问题解决器生成方案。新兴的大型语言模型（LLM）则直接根据用户需求输出计划。尽管LLM拥有丰富的旅行知识，能提供兴趣点和路线等高级信息，但现有模型生成的计划往往缺乏连贯性，未能充分满足约束，且无法保证方案质量。为此，我们开发了TRIP-PAL，一种融合LLM与自动规划器的混合方法：LLM负责收集并转换旅行及用户信息为规划器可用的数据结构，而自动规划器则生成满足约束、优化用户效用的旅行计划。实验证明，TRIP-PAL在多种旅行场景下，生成旅行计划的表现优于单一LLM。

> Travel planning is a complex task that involves generating a sequence of actions related to visiting places subject to constraints and maximizing some user satisfaction criteria. Traditional approaches rely on problem formulation in a given formal language, extracting relevant travel information from web sources, and use an adequate problem solver to generate a valid solution. As an alternative, recent Large Language Model (LLM) based approaches directly output plans from user requests using language. Although LLMs possess extensive travel domain knowledge and provide high-level information like points of interest and potential routes, current state-of-the-art models often generate plans that lack coherence, fail to satisfy constraints fully, and do not guarantee the generation of high-quality solutions. We propose TRIP-PAL, a hybrid method that combines the strengths of LLMs and automated planners, where (i) LLMs get and translate travel information and user information into data structures that can be fed into planners; and (ii) automated planners generate travel plans that guarantee constraint satisfaction and optimize for users' utility. Our experiments across various travel scenarios show that TRIP-PAL outperforms an LLM when generating travel plans.

[Arxiv](https://arxiv.org/abs/2406.10196)