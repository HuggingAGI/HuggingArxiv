# LogicGame：一项针对大型语言模型基于规则推理能力的评估基准

发布时间：2024年08月28日

`LLM应用` `人工智能` `游戏开发`

> LogicGame: Benchmarking Rule-Based Reasoning Abilities of Large Language Models

# 摘要

> 大型语言模型（LLM）在解决复杂问题方面展现出卓越能力。然而，将这些模型评估为高效的规则执行者和规划者仍是一个未充分探索的领域。为此，我们引入了LogicGame，一个创新基准，旨在全面评估LLM的规则理解、执行和规划能力。与传统基准不同，LogicGame通过多样化的游戏场景，要求模型理解和应用预设规则来解决问题。这些场景设计精巧，通过仅依赖预设规则来区分逻辑推理与简单知识应用，从而实现对规则推理能力的纯粹评估。评估不仅关注最终结果，还包括中间步骤，这些步骤具有确定性且可自动验证，确保了评估的全面性。LogicGame通过设置不同难度的游戏场景，从基础规则应用到复杂推理链，精确评估模型在规则理解和多步骤执行方面的表现。通过使用LogicGame，我们测试了多种LLM，揭示了它们在基于规则的逻辑推理能力上的显著不足。

> Large Language Models (LLMs) have demonstrated notable capabilities across various tasks, showcasing complex problem-solving abilities. Understanding and executing complex rules, along with multi-step planning, are fundamental to logical reasoning and critical for practical LLM agents and decision-making systems. However, evaluating LLMs as effective rule-based executors and planners remains underexplored. In this paper, we introduce LogicGame, a novel benchmark designed to evaluate the comprehensive rule understanding, execution, and planning capabilities of LLMs. Unlike traditional benchmarks, LogicGame provides diverse games that contain a series of rules with an initial state, requiring models to comprehend and apply predefined regulations to solve problems. We create simulated scenarios in which models execute or plan operations to achieve specific outcomes. These game scenarios are specifically designed to distinguish logical reasoning from mere knowledge by relying exclusively on predefined rules. This separation allows for a pure assessment of rule-based reasoning capabilities. The evaluation considers not only final outcomes but also intermediate steps, providing a comprehensive assessment of model performance. Moreover, these intermediate steps are deterministic and can be automatically verified. LogicGame defines game scenarios with varying difficulty levels, from simple rule applications to complex reasoning chains, in order to offer a precise evaluation of model performance on rule understanding and multi-step execution. Utilizing LogicGame, we test various LLMs and identify notable shortcomings in their rule-based logical reasoning abilities.

[Arxiv](https://arxiv.org/abs/2408.15778)