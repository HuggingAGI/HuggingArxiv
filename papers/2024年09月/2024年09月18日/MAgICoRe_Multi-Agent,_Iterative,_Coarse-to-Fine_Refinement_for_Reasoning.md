# MAgICoRe：一种多代理、迭代式的从粗到细推理优化方法

发布时间：2024年09月18日

`Agent` `人工智能`

> MAgICoRe: Multi-Agent, Iterative, Coarse-to-Fine Refinement for Reasoning

# 摘要

> 大型语言模型 (LLM) 的推理能力可以通过生成多个样本并进行投票的策略来提升，但这种方法往往达到性能瓶颈。改进方案则通过 LLM 生成的反馈来提升解决方案质量，但面临三大挑战：过度改进、错误定位困难和改进不足。为此，我们提出了 MAgICoRe，通过区分问题难度，采用粗粒度聚合解决简单问题，细粒度和迭代的多代理改进解决复杂问题。结合外部逐步奖励模型 (RM) 分数，我们构建了由求解器、评审员和改进器组成的多代理循环，确保有效改进。实验表明，MAgICoRe 在 Llama-3-8B 和 GPT-3.5 上的表现优于现有方法，且随着迭代次数增加，性能持续提升。消融实验进一步证实了 RM 和多代理通信的关键作用。

> Large Language Models' (LLM) reasoning can be improved using test-time aggregation strategies, i.e., generating multiple samples and voting among generated samples. While these improve performance, they often reach a saturation point. Refinement offers an alternative by using LLM-generated feedback to improve solution quality. However, refinement introduces 3 key challenges: (1) Excessive refinement: Uniformly refining all instances can over-correct and reduce the overall performance. (2) Inability to localize and address errors: LLMs have a limited ability to self-correct and struggle to identify and correct their own mistakes. (3) Insufficient refinement: Deciding how many iterations of refinement are needed is non-trivial, and stopping too soon could leave errors unaddressed. To tackle these issues, we propose MAgICoRe, which avoids excessive refinement by categorizing problem difficulty as easy or hard, solving easy problems with coarse-grained aggregation and hard ones with fine-grained and iterative multi-agent refinement. To improve error localization, we incorporate external step-wise reward model (RM) scores. Moreover, to ensure effective refinement, we employ a multi-agent loop with three agents: Solver, Reviewer (which generates targeted feedback based on step-wise RM scores), and the Refiner (which incorporates feedback). To ensure sufficient refinement, we re-evaluate updated solutions, iteratively initiating further rounds of refinement. We evaluate MAgICoRe on Llama-3-8B and GPT-3.5 and show its effectiveness across 5 math datasets. Even one iteration of MAgICoRe beats Self-Consistency by 3.4%, Best-of-k by 3.2%, and Self-Refine by 4.0% while using less than half the samples. Unlike iterative refinement with baselines, MAgICoRe continues to improve with more iterations. Finally, our ablations highlight the importance of MAgICoRe's RMs and multi-agent communication.

[Arxiv](https://arxiv.org/abs/2409.12147)