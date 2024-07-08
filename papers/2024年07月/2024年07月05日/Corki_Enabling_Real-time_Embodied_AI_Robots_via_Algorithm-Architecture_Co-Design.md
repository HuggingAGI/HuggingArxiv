# Corki：借助算法与架构的协同设计，赋能实时具身AI机器人。

发布时间：2024年07月05日

`LLM应用` `机器人` `人工智能`

> Corki: Enabling Real-time Embodied AI Robots via Algorithm-Architecture Co-Design

# 摘要

> 具身AI机器人有望彻底改变我们的生活和生产方式。在利用大型语言模型控制机器人的前沿领域，持续进步的关键在于高效计算基底。当前的计算系统仅考虑算法开发者需求，将机器人动作分割为离散帧，导致高延迟和高能耗。本文介绍的Corki框架，通过算法与架构的协同设计，实现实时机器人控制。Corki创新地解耦了LLM推理、机器人控制和数据通信，预测未来轨迹而非单帧动作，大幅降低LLM推理频率达8倍，提速3.6倍，成功率提升17.3%。代码已公开，便于复现。https://github.com/hyy0613/Corki

> Embodied AI robots have the potential to fundamentally improve the way human beings live and manufacture. Continued progress in the burgeoning field of using large language models to control robots depends critically on an efficient computing substrate. In particular, today's computing systems for embodied AI robots are designed purely based on the interest of algorithm developers, where robot actions are divided into a discrete frame-basis. Such an execution pipeline creates high latency and energy consumption. This paper proposes Corki, an algorithm-architecture co-design framework for real-time embodied AI robot control. Our idea is to decouple LLM inference, robotic control and data communication in the embodied AI robots compute pipeline. Instead of predicting action for one single frame, Corki predicts the trajectory for the near future to reduce the frequency of LLM inference. The algorithm is coupled with a hardware that accelerates transforming trajectory into actual torque signals used to control robots and an execution pipeline that parallels data communication with computation. Corki largely reduces LLM inference frequency by up to 8.0x, resulting in up to 3.6x speed up. The success rate improvement can be up to 17.3%. Code is provided for re-implementation. https://github.com/hyy0613/Corki

![Corki：借助算法与架构的协同设计，赋能实时具身AI机器人。](../../../paper_images/2407.04292/x1.png)

![Corki：借助算法与架构的协同设计，赋能实时具身AI机器人。](../../../paper_images/2407.04292/x2.png)

![Corki：借助算法与架构的协同设计，赋能实时具身AI机器人。](../../../paper_images/2407.04292/x3.png)

![Corki：借助算法与架构的协同设计，赋能实时具身AI机器人。](../../../paper_images/2407.04292/x4.png)

![Corki：借助算法与架构的协同设计，赋能实时具身AI机器人。](../../../paper_images/2407.04292/x5.png)

![Corki：借助算法与架构的协同设计，赋能实时具身AI机器人。](../../../paper_images/2407.04292/x6.png)

![Corki：借助算法与架构的协同设计，赋能实时具身AI机器人。](../../../paper_images/2407.04292/x7.png)

![Corki：借助算法与架构的协同设计，赋能实时具身AI机器人。](../../../paper_images/2407.04292/x8.png)

![Corki：借助算法与架构的协同设计，赋能实时具身AI机器人。](../../../paper_images/2407.04292/x9.png)

![Corki：借助算法与架构的协同设计，赋能实时具身AI机器人。](../../../paper_images/2407.04292/x10.png)

![Corki：借助算法与架构的协同设计，赋能实时具身AI机器人。](../../../paper_images/2407.04292/x11.png)

![Corki：借助算法与架构的协同设计，赋能实时具身AI机器人。](../../../paper_images/2407.04292/x12.png)

![Corki：借助算法与架构的协同设计，赋能实时具身AI机器人。](../../../paper_images/2407.04292/x13.png)

![Corki：借助算法与架构的协同设计，赋能实时具身AI机器人。](../../../paper_images/2407.04292/x14.png)

![Corki：借助算法与架构的协同设计，赋能实时具身AI机器人。](../../../paper_images/2407.04292/x15.png)

![Corki：借助算法与架构的协同设计，赋能实时具身AI机器人。](../../../paper_images/2407.04292/x16.png)

![Corki：借助算法与架构的协同设计，赋能实时具身AI机器人。](../../../paper_images/2407.04292/x17.png)

![Corki：借助算法与架构的协同设计，赋能实时具身AI机器人。](../../../paper_images/2407.04292/x18.png)

![Corki：借助算法与架构的协同设计，赋能实时具身AI机器人。](../../../paper_images/2407.04292/x19.png)

![Corki：借助算法与架构的协同设计，赋能实时具身AI机器人。](../../../paper_images/2407.04292/x20.png)

[Arxiv](https://arxiv.org/abs/2407.04292)