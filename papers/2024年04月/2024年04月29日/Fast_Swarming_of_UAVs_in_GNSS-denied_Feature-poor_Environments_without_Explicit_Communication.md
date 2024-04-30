# 在缺乏全球导航卫星系统信号且特征稀缺的环境中，无人机能够实现无需明确通信的快速集群飞行。

发布时间：2024年04月29日

`Agent` `无人机` `机器人`

> Fast Swarming of UAVs in GNSS-denied Feature-poor Environments without Explicit Communication

# 摘要

> 本文提出了一种分散式无人机群体飞行的新方法，适用于缺乏特征的环境中，无需外部定位和通信。我们设计了一种新型的无人机邻近区域模型，以增强无人机之间的相互感知和群体状态的反馈控制，有效减少了快速集体运动中常见的无人机间振荡。此外，我们还引入了一种改进的多机器人状态估计（MRSE）策略，以提升仅依赖机载定位的可靠性。尽管MRSE和邻近区域模型可能需要无人机间的信息交流，但我们开发了一种无需通信的群体框架，通过估算通信状态来降低对大型群体通信网络的依赖。该方案已通过一系列复杂的实际实验得到验证，展示了其在多变条件下的卓越性能，包括一项以无人机拦截为模拟目标的任务，其群体速度达到了单个无人机硬件平台的物理极限。

> A decentralized swarm approach for the fast cooperative flight of Unmanned Aerial Vehicles (UAVs) in feature-poor environments without any external localization and communication is introduced in this paper.
  A novel model of a UAV neighborhood is proposed to achieve robust onboard mutual perception and flocking state feedback control, which is designed to decrease the inter-agent oscillations common in standard reactive swarm models employed in fast collective motion.
  The novel swarming methodology is supplemented with an enhanced Multi-Robot State Estimation (MRSE) strategy to increase the reliability of the purely onboard localization, which may be unreliable in real environments.
  Although MRSE and the neighborhood model may rely on information exchange between agents, we introduce a communication-less version of the swarming framework based on estimating communicated states to decrease dependence on the often unreliable communication networks of large swarms.
  The proposed solution has been verified by a set of complex real-world experiments to demonstrate its overall capability in different conditions, including a UAV interception-motivated task with a group velocity reaching the physical limits of the individual hardware platforms.

[Arxiv](https://arxiv.org/abs/2404.18729)