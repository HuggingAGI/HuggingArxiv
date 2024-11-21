# RL-STaR：关于自学习推理器的强化学习框架的理论剖析

发布时间：2024年10月31日

`LLM理论` `语言模型`

> RL-STaR: Theoretical Analysis of Reinforcement Learning Frameworks for Self-Taught Reasoner

# 摘要

> 大型语言模型（LLMs）在思维链（CoT）提示下，推理能力得以提升，能够逐步解决复杂任务。然而，训练 CoT 能力所需的详细推理数据通常稀缺。自学习推理器（STaR）框架借助强化学习自动生成推理步骤，降低了对人工标注数据的依赖。尽管 STaR 及其变体已取得实践成功，但相关改进缺乏理论依据。本研究为理解强化学习在 CoT 推理和 STaR 中的有效性构建了理论框架，贡献如下：（1）分析策略改进，揭示 LLM 推理通过 STaR 实现迭代提升的原因；（2）给出收敛至最优推理策略的条件；（3）探究 STaR 的稳健性，阐释即便偶尔纳入错误步骤，它仍能改进推理的原理；（4）明确启动有效推理改进所需的预训练模型质量标准。此框架旨在融合实证成果与理论洞察，推动 LLMs 推理的强化学习方法发展。

> The reasoning abilities of large language models (LLMs) have improved with chain-of-thought (CoT) prompting, allowing models to solve complex tasks in a stepwise manner. However, training CoT capabilities requires detailed reasoning data, which is often scarce. The self-taught reasoner (STaR) framework addresses this by using reinforcement learning to automatically generate reasoning steps, reducing reliance on human-labeled data. Although STaR and its variants have demonstrated empirical success, a theoretical foundation explaining these improvements is lacking. This work provides a theoretical framework for understanding the effectiveness of reinforcement learning on CoT reasoning and STaR. Our contributions are: (1) an analysis of policy improvement, showing why LLM reasoning improves iteratively with STaR; (2) conditions for convergence to an optimal reasoning policy; (3) an examination of STaR's robustness, explaining how it can improve reasoning even when incorporating occasional incorrect steps; and (4) criteria for the quality of pre-trained models necessary to initiate effective reasoning improvement. This framework aims to bridge empirical findings with theoretical insights, advancing reinforcement learning approaches for reasoning in LLMs.

[Arxiv](https://arxiv.org/abs/2410.23912)