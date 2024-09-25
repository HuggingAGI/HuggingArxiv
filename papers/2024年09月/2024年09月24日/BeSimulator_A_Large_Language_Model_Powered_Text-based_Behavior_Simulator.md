# BeSimulator：一款由大型语言模型赋能的文本行为模拟器

发布时间：2024年09月24日

`Agent` `机器人` `人工智能`

> BeSimulator: A Large Language Model Powered Text-based Behavior Simulator

# 摘要

> 传统机器人模拟器常因高计算成本和低适应性而受限。为此，我们提出 BeSimulator，一个基于 LLM 的模块化框架，专注于机器人行为逻辑的验证，确保其行动与现实场景高度一致。通过文本虚拟环境和语义模拟，BeSimulator 能跨场景泛化，实现复杂长时模拟。借鉴人类认知，它采用“考虑-决定-捕捉-转移”链式方法，擅长分析行动可行性。此外，代码驱动推理和反射反馈的结合，进一步提升了模拟的可靠性和精度。实验表明，BeSimulator 在行为模拟上比基线提升了 14.7% 至 26.6%。

> Traditional robot simulators focus on physical process modeling and realistic rendering, often suffering from high computational costs, inefficiencies, and limited adaptability. To handle this issue, we propose Behavior Simulation in robotics to emphasize checking the behavior logic of robots and achieving sufficient alignment between the outcome of robot actions and real scenarios. In this paper, we introduce BeSimulator, a modular and novel LLM-powered framework, as an attempt towards behavior simulation in the context of text-based environments. By constructing text-based virtual environments and performing semantic-level simulation, BeSimulator can generalize across scenarios and achieve long-horizon complex simulation. Inspired by human cognition processes, it employs a "consider-decide-capture-transfer" methodology, termed Chain of Behavior Simulation, which excels at analyzing action feasibility and state transitions. Additionally, BeSimulator incorporates code-driven reasoning to enable arithmetic operations and enhance reliability, as well as integrates reflective feedback to refine simulation. Based on our manually constructed behavior-tree-based simulation benchmark BTSIMBENCH, our experiments show a significant performance improvement in behavior simulation compared to baselines, ranging from 14.7% to 26.6%.

[Arxiv](https://arxiv.org/abs/2409.15865)