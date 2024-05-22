# 利益共担：在大型语言模型中通过多方利益协调实现决策

发布时间：2024年05月21日

`Agent

理由：这篇论文提出了一种名为“利益相关”（SKIG）的框架，旨在提升大型语言模型（LLMs）在道德推理和伦理决策方面的能力，特别是在多方利益相关者的复杂情境中。这个框架通过模拟多方视角下的决策后果，结合责任感、同理心训练和风险评估来实现其目标。这种对LLMs进行特定任务增强和行为模拟的方法，更符合Agent的定义，即一个能够感知环境并采取行动以达到目标的系统。因此，这篇论文更适合归类为Agent。` `道德推理` `伦理决策`

> Skin-in-the-Game: Decision Making via Multi-Stakeholder Alignment in LLMs

# 摘要

> 大型语言模型（LLMs）在总结、算术推理和问答等任务中表现出色，但在道德推理和伦理决策，尤其是在多方利益相关者的复杂情境中，却遭遇难题。为此，我们提出了“利益相关”（SKIG）框架，旨在通过模拟多方视角下的决策后果，提升LLMs的道德推理能力。SKIG的核心在于模拟行动的责任感，结合同理心训练和风险评估，共同确保其有效性。我们通过在多个道德推理基准上测试SKIG，并进行深入的消融分析，验证了其性能并探究了关键组成部分。

> Large Language Models (LLMs) have shown remarkable capabilities in tasks such as summarization, arithmetic reasoning, and question answering. However, they encounter significant challenges in the domain of moral reasoning and ethical decision-making, especially in complex scenarios with multiple stakeholders. This paper introduces the Skin-in-the-Game (SKIG) framework, aimed at enhancing moral reasoning in LLMs by exploring decisions' consequences from multiple stakeholder perspectives. Central to SKIG's mechanism is simulating accountability for actions, which, alongside empathy exercises and risk assessment, is pivotal to its effectiveness. We validate SKIG's performance across various moral reasoning benchmarks with proprietary and opensource LLMs, and investigate its crucial components through extensive ablation analyses.

[Arxiv](https://arxiv.org/abs/2405.12933)