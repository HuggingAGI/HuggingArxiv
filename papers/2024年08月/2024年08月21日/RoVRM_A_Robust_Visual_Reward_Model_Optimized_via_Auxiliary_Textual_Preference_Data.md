# RoVRM：借助辅助文本偏好数据，优化而成的鲁棒视觉奖励模型

发布时间：2024年08月21日

`LLM应用` `人工智能` `计算机视觉`

> RoVRM: A Robust Visual Reward Model Optimized via Auxiliary Textual Preference Data

# 摘要

> 大型视觉-语言模型 (LVLMs) 往往难以与人类偏好保持一致，导致内容生成时缺乏必要的视觉背景，产生误导信息（即幻觉现象）。为解决这一难题，我们探索了利用人类偏好对齐技术，如最佳-n采样和强化学习，但这些方法受限于视觉偏好数据的匮乏，这限制了视觉奖励模型 (VRM) 的训练。为此，我们提出了一种鲁健的视觉奖励模型 (RoVRM)，它通过三阶段渐进式训练和基于最优传输的偏好数据精选，有效利用了辅助文本偏好数据，从而在视觉偏好数据稀缺的情况下实现了对 LVLMs 的人类偏好对齐的改进。我们在 LLaVA-1.5-7B 和 -13B 模型支持的视觉-语言任务上验证了 RoVRM 的性能，结果显示其持续超越传统 VRMs。同时，我们的训练方法在直接偏好优化等排名对齐技术上也展现出一致的性能提升。

> Large vision-language models (LVLMs) often fail to align with human preferences, leading to issues like generating misleading content without proper visual context (also known as hallucination). A promising solution to this problem is using human-preference alignment techniques, such as best-of-n sampling and reinforcement learning. However, these techniques face the difficulty arising from the scarcity of visual preference data, which is required to train a visual reward model (VRM). In this work, we continue the line of research. We present a Robust Visual Reward Model (RoVRM) which improves human-preference alignment for LVLMs. RoVRM leverages auxiliary textual preference data through a three-phase progressive training and optimal transport-based preference data selection to effectively mitigate the scarcity of visual preference data. We experiment with RoVRM on the commonly used vision-language tasks based on the LLaVA-1.5-7B and -13B models. Experimental results demonstrate that RoVRM consistently outperforms traditional VRMs. Furthermore, our three-phase progressive training and preference data selection approaches can yield consistent performance gains over ranking-based alignment techniques, such as direct preference optimization.

[Arxiv](https://arxiv.org/abs/2408.12109)