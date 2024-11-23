# CaStL：借助 LLM 翻译，将约束作为规范应用于长时程任务与运动规划

发布时间：2024年10月29日

`LLM应用` `运动规划`

> CaStL: Constraints as Specifications through LLM Translation for Long-Horizon Task and Motion Planning

# 摘要

> 大型语言模型（LLMs）在长时程任务和运动规划（TAMP）领域表现出色，能把清晰明了的自然语言问题转化为像规划领域定义语言（PDDL）这样的正式规范。但现实中的问题通常比较模糊，还包含众多复杂的约束。本文中，我们推出了通过大型语言模型将约束作为规范（CaStL）这一框架，它能在多个阶段从自然语言中识别出像目标条件、动作排序和动作阻塞之类的约束。CaStL 把这些约束转化为 PDDL 和 Python 脚本，再用定制的 PDDL 求解器来求解。经过在三个 PDDL 领域的测试，CaStL 在复杂场景中极大地提升了对自然语言规范中约束的处理能力和规划成功率。

> Large Language Models (LLMs) have demonstrated remarkable ability in long-horizon Task and Motion Planning (TAMP) by translating clear and straightforward natural language problems into formal specifications such as the Planning Domain Definition Language (PDDL). However, real-world problems are often ambiguous and involve many complex constraints. In this paper, we introduce Constraints as Specifications through LLMs (CaStL), a framework that identifies constraints such as goal conditions, action ordering, and action blocking from natural language in multiple stages. CaStL translates these constraints into PDDL and Python scripts, which are solved using an custom PDDL solver. Tested across three PDDL domains, CaStL significantly improves constraint handling and planning success rates from natural language specification in complex scenarios.

[Arxiv](https://arxiv.org/abs/2410.22225)