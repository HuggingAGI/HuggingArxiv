# LMMCoDrive：携手大型多模态模型，共创智能驾驶新纪元

发布时间：2024年09月18日

`Agent` `自动驾驶`

> LMMCoDrive: Cooperative Driving with Large Multimodal Model

# 摘要

> 本文针对 Autonomous Mobility-on-Demand (AMoD) 系统中的分散合作调度和运动规划难题，提出了 LMMCoDrive 框架。该框架利用大型多模态模型 (LMM)，在动态城市环境中提升交通效率，并通过鸟瞰图 (BEV) 抽象空间关系，优化 CAVs 轨迹，确保安全。借助 ADMM 的分散优化策略，LMM 在 CAV 调度和合作优化中展现出关键作用。仿真结果证实了其显著效果，为实现高效、安全的 AMoD 系统奠定了基础，有望革新城市交通。代码已公开，详见 https://github.com/henryhcliu/LMMCoDrive。

> To address the intricate challenges of decentralized cooperative scheduling and motion planning in Autonomous Mobility-on-Demand (AMoD) systems, this paper introduces LMMCoDrive, a novel cooperative driving framework that leverages a Large Multimodal Model (LMM) to enhance traffic efficiency in dynamic urban environments. This framework seamlessly integrates scheduling and motion planning processes to ensure the effective operation of Cooperative Autonomous Vehicles (CAVs). The spatial relationship between CAVs and passenger requests is abstracted into a Bird's-Eye View (BEV) to fully exploit the potential of the LMM. Besides, trajectories are cautiously refined for each CAV while ensuring collision avoidance through safety constraints. A decentralized optimization strategy, facilitated by the Alternating Direction Method of Multipliers (ADMM) within the LMM framework, is proposed to drive the graph evolution of CAVs. Simulation results demonstrate the pivotal role and significant impact of LMM in optimizing CAV scheduling and enhancing decentralized cooperative optimization process for each vehicle. This marks a substantial stride towards achieving practical, efficient, and safe AMoD systems that are poised to revolutionize urban transportation. The code is available at https://github.com/henryhcliu/LMMCoDrive.

[Arxiv](https://arxiv.org/abs/2409.11981)