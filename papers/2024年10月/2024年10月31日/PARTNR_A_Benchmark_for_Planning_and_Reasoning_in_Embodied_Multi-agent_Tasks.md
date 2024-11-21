# PARTNR：具身多智能体任务中规划与推理的基准

发布时间：2024年10月31日

`LLM应用` `机器人` `人机协作`

> PARTNR: A Benchmark for Planning and Reasoning in Embodied Multi-agent Tasks

# 摘要

> 我们推出了一个针对人类与机器人协作中的规划及推理任务（PARTNR）的基准，旨在探究家庭活动中的人机协调情况。PARTNR 任务呈现出日常任务的特性，像空间、时间以及异构代理能力的限制。我们运用了借助大型语言模型（LLMs）的半自动任务生成管线，并融入循环中的模拟来进行奠基和验证。PARTNR 是此类基准中规模最大的，包含 10 万个自然语言任务，涉及 60 所房屋和 5819 个独特物件。我们针对 PARTNR 任务对最先进的 LLMs 进行了分析，涵盖规划、感知和技能执行等维度。分析显示 SoTA 模型存在明显局限，比如协调能力差，在任务跟踪和错误恢复方面表现不佳。当 LLMs 与真实人类搭档时，所需步骤是两人协作的 1.5 倍，比单人多 1.1 倍，凸显了这些模型的可提升空间。我们还进一步表明，用规划数据对较小的 LLMs 进行微调，能够取得与大 9 倍的模型相当的性能，而且推理速度快 8.6 倍。总之，PARTNR 凸显了协作具身代理所面临的重大挑战，旨在推动此方向的研究。

> We present a benchmark for Planning And Reasoning Tasks in humaN-Robot collaboration (PARTNR) designed to study human-robot coordination in household activities. PARTNR tasks exhibit characteristics of everyday tasks, such as spatial, temporal, and heterogeneous agent capability constraints. We employ a semi-automated task generation pipeline using Large Language Models (LLMs), incorporating simulation in the loop for grounding and verification. PARTNR stands as the largest benchmark of its kind, comprising 100,000 natural language tasks, spanning 60 houses and 5,819 unique objects. We analyze state-of-the-art LLMs on PARTNR tasks, across the axes of planning, perception and skill execution. The analysis reveals significant limitations in SoTA models, such as poor coordination and failures in task tracking and recovery from errors. When LLMs are paired with real humans, they require 1.5x as many steps as two humans collaborating and 1.1x more steps than a single human, underscoring the potential for improvement in these models. We further show that fine-tuning smaller LLMs with planning data can achieve performance on par with models 9 times larger, while being 8.6x faster at inference. Overall, PARTNR highlights significant challenges facing collaborative embodied agents and aims to drive research in this direction.

[Arxiv](https://arxiv.org/abs/2411.00081)