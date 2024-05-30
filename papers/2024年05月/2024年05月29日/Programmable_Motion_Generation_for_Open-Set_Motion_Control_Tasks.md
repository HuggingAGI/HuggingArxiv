# 开放集运动控制任务的可编程运动生成

发布时间：2024年05月29日

`Agent

这篇论文主要讨论了在现实世界中制作角色动画时所面临的复杂运动控制问题，并提出了一种新的可编程运动生成范式来解决这一问题。该方法通过优化预训练的运动生成模型的潜在代码，以满足特定的运动控制约束，并能够处理各种未见任务，包括运动动力学、几何约束、物理定律及与环境、物体的交互等。此外，论文还提到了利用大型语言模型实现自动编程，以推动通用AI代理的运动控制技术发展。因此，这篇论文更符合Agent分类，因为它关注的是如何通过AI技术实现复杂的运动控制，这与Agent的行为生成和控制密切相关。` `动画制作` `人工智能`

> Programmable Motion Generation for Open-Set Motion Control Tasks

# 摘要

> 在现实世界中制作角色动画，需应对轨迹、关键帧、交互等多种约束。传统方法常将这些约束视为独立任务，专业化且难以扩展。我们称之为解决封闭集运动控制问题。面对实际运动控制的复杂性，我们提出并尝试解决开放集运动控制问题，其特点是任务集合开放且完全可定制。为此，我们创新性地引入了可编程运动生成范式，将任何运动控制任务分解为原子约束组合，并通过误差函数量化运动序列对这些约束的遵循程度。我们运用预训练的运动生成模型，通过优化潜在代码来最小化误差，使得生成的运动既保留了模型的先验知识，又满足了特定约束。实验证明，我们能针对各种未见任务生成高质量运动，涵盖运动动力学、几何约束、物理定律及与环境、物体的交互等。这一切均在统一框架下完成，无需特定数据或网络设计。在新任务编程中，我们发现了超越原模型的新技能，并借助大型语言模型实现了自动编程。我们期待这项工作能推动通用AI代理的运动控制技术发展。

> Character animation in real-world scenarios necessitates a variety of constraints, such as trajectories, key-frames, interactions, etc. Existing methodologies typically treat single or a finite set of these constraint(s) as separate control tasks. They are often specialized, and the tasks they address are rarely extendable or customizable. We categorize these as solutions to the close-set motion control problem. In response to the complexity of practical motion control, we propose and attempt to solve the open-set motion control problem. This problem is characterized by an open and fully customizable set of motion control tasks. To address this, we introduce a new paradigm, programmable motion generation. In this paradigm, any given motion control task is broken down into a combination of atomic constraints. These constraints are then programmed into an error function that quantifies the degree to which a motion sequence adheres to them. We utilize a pre-trained motion generation model and optimize its latent code to minimize the error function of the generated motion. Consequently, the generated motion not only inherits the prior of the generative model but also satisfies the required constraints. Experiments show that we can generate high-quality motions when addressing a wide range of unseen tasks. These tasks encompass motion control by motion dynamics, geometric constraints, physical laws, interactions with scenes, objects or the character own body parts, etc. All of these are achieved in a unified approach, without the need for ad-hoc paired training data collection or specialized network designs. During the programming of novel tasks, we observed the emergence of new skills beyond those of the prior model. With the assistance of large language models, we also achieved automatic programming. We hope that this work will pave the way for the motion control of general AI agents.

![开放集运动控制任务的可编程运动生成](../../../paper_images/2405.19283/x2.png)

![开放集运动控制任务的可编程运动生成](../../../paper_images/2405.19283/x3.png)

![开放集运动控制任务的可编程运动生成](../../../paper_images/2405.19283/x4.png)

![开放集运动控制任务的可编程运动生成](../../../paper_images/2405.19283/x5.png)

![开放集运动控制任务的可编程运动生成](../../../paper_images/2405.19283/x6.png)

[Arxiv](https://arxiv.org/abs/2405.19283)