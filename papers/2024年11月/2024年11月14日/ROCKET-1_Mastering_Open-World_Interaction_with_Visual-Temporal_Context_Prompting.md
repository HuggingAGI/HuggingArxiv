# ROCKET-1：凭借视觉-时间上下文提示掌控开放世界的交互

发布时间：2024年11月14日

`Agent` `计算机视觉` `具身决策`

> ROCKET-1: Mastering Open-World Interaction with Visual-Temporal Context Prompting

# 摘要

> 视觉语言模型（VLMs）在多模态任务方面表现卓越，但要将其应用于开放世界环境中的具身决策却面临挑战。关键在于填补低级观察中的离散实体与有效规划所需抽象概念之间的鸿沟。常见办法是构建分层代理，让 VLMs 充当高级推理器，把任务拆解为可执行的子任务，通常用语言来明确。然而，语言难以传递详尽的空间信息。我们提出了视觉-时间上下文提示，这是 VLMs 与策略模型之间的一种全新通信协议。此协议借助过去观察中的对象分割来引导策略与环境的交互。通过这种方式，我们训练了 ROCKET-1，这是一种基于串联的视觉观察和分割掩码来预测动作的低级策略，并得到了 SAM-2 实时对象跟踪的支持。我们的方法激发了 VLMs 的潜能，使其能够应对需要空间推理的复杂任务。在《我的世界》中的实验显示，我们的方法让代理能够达成此前无法实现的任务，在开放世界交互性能上有 76%的绝对提升。代码和演示现可在项目页面获取：https://craftjarvis.github.io/ROCKET-1。

> Vision-language models (VLMs) have excelled in multimodal tasks, but adapting them to embodied decision-making in open-world environments presents challenges. One critical issue is bridging the gap between discrete entities in low-level observations and the abstract concepts required for effective planning. A common solution is building hierarchical agents, where VLMs serve as high-level reasoners that break down tasks into executable sub-tasks, typically specified using language. However, language suffers from the inability to communicate detailed spatial information. We propose visual-temporal context prompting, a novel communication protocol between VLMs and policy models. This protocol leverages object segmentation from past observations to guide policy-environment interactions. Using this approach, we train ROCKET-1, a low-level policy that predicts actions based on concatenated visual observations and segmentation masks, supported by real-time object tracking from SAM-2. Our method unlocks the potential of VLMs, enabling them to tackle complex tasks that demand spatial reasoning. Experiments in Minecraft show that our approach enables agents to achieve previously unattainable tasks, with a $\mathbf{76}\%$ absolute improvement in open-world interaction performance. Codes and demos are now available on the project page: https://craftjarvis.github.io/ROCKET-1.

[Arxiv](https://arxiv.org/abs/2410.17856)