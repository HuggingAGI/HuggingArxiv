# 基于 LLM 数据合成与策略适应的鲁棒强化学习，助力自动驾驶技术发展

发布时间：2024年10月16日

`Agent` `自动驾驶` `人工智能`

> Robust RL with LLM-Driven Data Synthesis and Policy Adaptation for Autonomous Driving

# 摘要

> 将大型语言模型 (LLM) 融入自动驾驶系统，展现了卓越的常识和推理能力，弥补了纯数据驱动方法的不足。然而，当前基于 LLM 的系统在推理速度和实时环境交互方面仍显不足。本文提出 RAPID 框架，通过利用 LLM 生成的数据和在线适应，训练出高效且鲁棒的强化学习 (RL) 代理。RAPID 包含三大创新：1) 利用 LLM 代理的离线数据，快速提炼专家知识至 RL 策略；2) 在 RL 中引入鲁棒提炼，确保性能与鲁棒性并存；3) 采用混合策略方法，通过策略适配器优化决策。实验证明，RAPID 能高效整合 LLM 知识，适应性强且鲁棒。代码和模型将在论文接受后公开。

> The integration of Large Language Models (LLMs) into autonomous driving systems demonstrates strong common sense and reasoning abilities, effectively addressing the pitfalls of purely data-driven methods. Current LLM-based agents require lengthy inference times and face challenges in interacting with real-time autonomous driving environments. A key open question is whether we can effectively leverage the knowledge from LLMs to train an efficient and robust Reinforcement Learning (RL) agent. This paper introduces RAPID, a novel \underline{\textbf{R}}obust \underline{\textbf{A}}daptive \underline{\textbf{P}}olicy \underline{\textbf{I}}nfusion and \underline{\textbf{D}}istillation framework, which trains specialized mix-of-policy RL agents using data synthesized by an LLM-based driving agent and online adaptation. RAPID features three key designs: 1) utilization of offline data collected from an LLM agent to distil expert knowledge into RL policies for faster real-time inference; 2) introduction of robust distillation in RL to inherit both performance and robustness from LLM-based teacher; and 3) employment of a mix-of-policy approach for joint decision decoding with a policy adapter. Through fine-tuning via online environment interaction, RAPID reduces the forgetting of LLM knowledge while maintaining adaptability to different tasks. Extensive experiments demonstrate RAPID's capability to effectively integrate LLM knowledge into scaled-down RL policies in an efficient, adaptable, and robust way. Code and checkpoints will be made publicly available upon acceptance.

[Arxiv](https://arxiv.org/abs/2410.12568)