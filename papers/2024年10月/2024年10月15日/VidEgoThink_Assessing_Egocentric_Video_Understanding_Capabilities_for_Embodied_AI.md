# VidEgoThink：探索具身 AI 在以自我为中心的视频理解中的潜能

发布时间：2024年10月15日

`LLM应用` `人工智能` `视频分析`

> VidEgoThink: Assessing Egocentric Video Understanding Capabilities for Embodied AI

# 摘要

> 多模态大型语言模型（MLLM）的进步为具身AI带来了新机遇。基于EgoThink，我们推出了VidEgoThink，一个评估自我中心视频理解的综合基准。为连接MLLM与具身AI的低级控制，我们设计了视频问答、层次规划、视觉定位和奖励建模四大任务。通过Ego4D数据集和GPT-4o的多模态能力，我们自动生成数据，并由三位标注者筛选，确保多样性和质量。实验显示，包括GPT-4o在内的所有MLLM在自我中心视频理解任务中表现不佳，表明基础模型在具身AI的第一人称应用中仍需大幅提升。VidEgoThink展现了利用MLLM进行自我中心视觉研究的趋势，旨在实现类似人类的主动观察和互动能力。

> Recent advancements in Multi-modal Large Language Models (MLLMs) have opened new avenues for applications in Embodied AI. Building on previous work, EgoThink, we introduce VidEgoThink, a comprehensive benchmark for evaluating egocentric video understanding capabilities. To bridge the gap between MLLMs and low-level control in Embodied AI, we design four key interrelated tasks: video question-answering, hierarchy planning, visual grounding and reward modeling. To minimize manual annotation costs, we develop an automatic data generation pipeline based on the Ego4D dataset, leveraging the prior knowledge and multimodal capabilities of GPT-4o. Three human annotators then filter the generated data to ensure diversity and quality, resulting in the VidEgoThink benchmark. We conduct extensive experiments with three types of models: API-based MLLMs, open-source image-based MLLMs, and open-source video-based MLLMs. Experimental results indicate that all MLLMs, including GPT-4o, perform poorly across all tasks related to egocentric video understanding. These findings suggest that foundation models still require significant advancements to be effectively applied to first-person scenarios in Embodied AI. In conclusion, VidEgoThink reflects a research trend towards employing MLLMs for egocentric vision, akin to human capabilities, enabling active observation and interaction in the complex real-world environments.

[Arxiv](https://arxiv.org/abs/2410.11623)