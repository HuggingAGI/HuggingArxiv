# ResearchAgent：借助大型语言模型，对科学文献进行迭代式的研究创意生成

发布时间：2024年04月11日

`分类：Agent` `科学研究` `自动化写作`

> ResearchAgent: Iterative Research Idea Generation over Scientific Literature with Large Language Models

# 摘要

> 科学研究对于提升人类生活质量至关重要，但其复杂性、缓慢的进展和对专家的依赖限制了其效率。为了提升科研生产力，我们设计了一个名为“研究代理”的智能写作助手，它由大型语言模型提供支持，能够自动生成问题、方法和实验设计，并通过科学文献不断迭代优化。该代理以一篇核心论文为起点，生成研究思路，并通过学术网络连接相关文献，以及从一个以实体为中心的知识库中检索与论文概念相关的实体，这些实体在多篇论文中被挖掘和共享。同时，借鉴人类通过同行评审不断改进研究思路的做法，我们引入了多个“审稿代理”，它们提供连续的评审和反馈。这些审稿代理是基于与人类偏好一致的大型语言模型构建的，其评审标准来源于实际的人类评价。我们在多个学科领域对“研究代理”进行了实验验证，结果表明，它在生成新颖、清晰且有效的研究构想方面具有显著效果，这一效果得到了人类评审和模型评估的双重认可。

> Scientific Research, vital for improving human life, is hindered by its inherent complexity, slow pace, and the need for specialized experts. To enhance its productivity, we propose a ResearchAgent, a large language model-powered research idea writing agent, which automatically generates problems, methods, and experiment designs while iteratively refining them based on scientific literature. Specifically, starting with a core paper as the primary focus to generate ideas, our ResearchAgent is augmented not only with relevant publications through connecting information over an academic graph but also entities retrieved from an entity-centric knowledge store based on their underlying concepts, mined and shared across numerous papers. In addition, mirroring the human approach to iteratively improving ideas with peer discussions, we leverage multiple ReviewingAgents that provide reviews and feedback iteratively. Further, they are instantiated with human preference-aligned large language models whose criteria for evaluation are derived from actual human judgments. We experimentally validate our ResearchAgent on scientific publications across multiple disciplines, showcasing its effectiveness in generating novel, clear, and valid research ideas based on human and model-based evaluation results.

[Arxiv](https://arxiv.org/abs/2404.07738)