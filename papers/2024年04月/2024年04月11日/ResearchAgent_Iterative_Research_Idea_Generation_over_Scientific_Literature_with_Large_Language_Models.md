# ResearchAgent：借助大型语言模型，通过科学文献实现研究创意的迭代产生

发布时间：2024年04月11日

`Agent` `科学研究` `自动化写作`

> ResearchAgent: Iterative Research Idea Generation over Scientific Literature with Large Language Models

# 摘要

> 科学研究是提升人类生活品质的关键，但其复杂性、缓慢进展和专业门槛限制了其发展。为了提升科研效率，我们设计了一个研究助手——ResearchAgent，它利用大型语言模型自动撰写研究点子，包括问题提出、方法论构建和实验设计，并根据科学文献不断优化。该助手以一篇核心论文为中心，通过学术网络连接相关文献，同时从实体知识库中提取与概念相关的实体信息，这些信息跨越众多论文而共享。借鉴人类在同行交流中不断完善想法的方式，我们还引入了多个评审助手，它们提供连续的评审和反馈。这些评审助手配备了符合人类偏好的大型语言模型，其评价标准基于真实的人类评价。通过在多个学科的科学出版物上进行实验验证，我们的研究助手展现出了在创造新颖、清晰、有效研究点子方面的卓越能力，这一点得到了人类和模型评估的一致认可。

> Scientific Research, vital for improving human life, is hindered by its inherent complexity, slow pace, and the need for specialized experts. To enhance its productivity, we propose a ResearchAgent, a large language model-powered research idea writing agent, which automatically generates problems, methods, and experiment designs while iteratively refining them based on scientific literature. Specifically, starting with a core paper as the primary focus to generate ideas, our ResearchAgent is augmented not only with relevant publications through connecting information over an academic graph but also entities retrieved from an entity-centric knowledge store based on their underlying concepts, mined and shared across numerous papers. In addition, mirroring the human approach to iteratively improving ideas with peer discussions, we leverage multiple ReviewingAgents that provide reviews and feedback iteratively. Further, they are instantiated with human preference-aligned large language models whose criteria for evaluation are derived from actual human judgments. We experimentally validate our ResearchAgent on scientific publications across multiple disciplines, showcasing its effectiveness in generating novel, clear, and valid research ideas based on human and model-based evaluation results.

[Arxiv](https://arxiv.org/abs/2404.07738)