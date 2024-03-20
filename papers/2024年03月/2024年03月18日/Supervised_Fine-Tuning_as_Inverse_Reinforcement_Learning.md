# 将监督微调视为逆向强化学习，这一新颖视角揭示了预训练模型在特定任务上微调的潜在机制。通过借鉴强化学习中的逆向方法，我们尝试理解并解析在有监督环境下对大型预训练模型进行调整以优化其在特定下游任务性能背后的“奖励”信号。

发布时间：2024年03月18日

`Agent` `模型对齐`

> Supervised Fine-Tuning as Inverse Reinforcement Learning

> 主流对大型语言模型（LLMs）的对齐方式多依赖于人工或AI反馈及特定类型偏好数据集，而我们的研究对此类数据集的有效性提出疑问，并深入探究了通过专家演示实现更为真实对齐的各种情况。为此，我们设计了一个序列决策框架，借助演示数据集解决LLMs对齐问题。借力于逆向强化学习与模仿学习的理念，我们提出了几种适用于LLMs对齐任务中减少差异性的方法，并揭示了这些方法在大规模覆盖和追求最优模式方面的特性。此外，我们还全面审视了传统监督微调方法的利弊，详尽讨论了各类方法在各自适用场景下的卓越表现。

> The prevailing approach to aligning Large Language Models (LLMs) typically relies on human or AI feedback and assumes access to specific types of preference datasets. In our work, we question the efficacy of such datasets and explore various scenarios where alignment with expert demonstrations proves more realistic. We build a sequential decision-making framework to formulate the problem of aligning LLMs using demonstration datasets. Drawing insights from inverse reinforcement learning and imitation learning, we introduce various approaches for divergence minimization in the LLM alignment tasks. Our analysis highlights the mass-covering and mode-seeking behaviors of these different approaches. Inclusively, we examine the pros and cons of the classical supervised fine-tuning method, elaborating on scenarios where different methods shine.

[Arxiv](https://arxiv.org/abs/2403.12017)