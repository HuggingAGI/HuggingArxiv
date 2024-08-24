# FLAME：探索在城市环境中利用多模态 LLM 进行智能导航的学习方法

发布时间：2024年08月20日

`Agent` `人工智能` `自动驾驶`

> FLAME: Learning to Navigate with Multimodal LLM in Urban Environments

# 摘要

> 大型语言模型（LLM）虽在视觉-语言导航（VLN）任务中潜力巨大，但实际应用仍遇难题。LLM 虽擅长通用对话，却难以胜任专业导航任务，表现不及专用 VLN 模型。为此，我们推出 FLAME（FLAMingo 架构的具身代理），一款专为城市 VLN 任务设计的多模态 LLM 代理，能高效处理多重观察。我们采用三阶段调优技术，包括街道视图描述的单感知调优、轨迹摘要的多感知调优及 VLN 数据集的端到端训练，以适应导航任务。增强数据集自动生成。实验表明，FLAME 在 Touchdown 数据集上的任务完成率提升 7.3%，超越现有技术。此研究揭示了多模态 LLM（MLLM）在复杂导航任务中的应用潜力，推动了 MLLM 在具身 AI 领域的实际应用进程。项目详情：https://flame-sjtu.github.io

> Large Language Models (LLMs) have demonstrated potential in Vision-and-Language Navigation (VLN) tasks, yet current applications face challenges. While LLMs excel in general conversation scenarios, they struggle with specialized navigation tasks, yielding suboptimal performance compared to specialized VLN models. We introduce FLAME (FLAMingo-Architected Embodied Agent), a novel Multimodal LLM-based agent and architecture designed for urban VLN tasks that efficiently handles multiple observations. Our approach implements a three-phase tuning technique for effective adaptation to navigation tasks, including single perception tuning for street view description, multiple perception tuning for trajectory summarization, and end-to-end training on VLN datasets. The augmented datasets are synthesized automatically. Experimental results demonstrate FLAME's superiority over existing methods, surpassing state-of-the-art methods by a 7.3% increase in task completion rate on Touchdown dataset. This work showcases the potential of Multimodal LLMs (MLLMs) in complex navigation tasks, representing an advancement towards practical applications of MLLMs in embodied AI. Project page: https://flame-sjtu.github.io

[Arxiv](https://arxiv.org/abs/2408.11051)