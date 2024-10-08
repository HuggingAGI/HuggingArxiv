# 无人机网络中的集成感知与通信，通过基于大型语言模型的多目标优化实现。

发布时间：2024年10月07日

`LLM应用` `无人机`

> Large Language Model Based Multi-Objective Optimization for Integrated Sensing and Communications in UAV Networks

# 摘要

> 本文探讨了集成感知与通信（ISAC）系统的无人机网络，其中多架无人机同时感知地面用户位置并提供雷达通信服务。为平衡通信与感知（C&S），我们设计了一个多目标优化问题（MOP），旨在最大化网络总效用及地面用户的定位精度（CRB），从而优化无人机的部署与功率控制。受大型语言模型（LLM）在预测与推理中的潜力启发，我们提出了一种基于LLM的分解多目标进化算法（LEDMA），以应对高度非凸的MOP。首先，我们将MOP分解为一系列子问题；其次，将LLM作为黑箱搜索算子，结合MOP特制的提示工程，融入MOEA框架，同步解决子问题。数值结果显示，LEDMA能清晰权衡C&S，并在Pareto前沿与收敛性上超越基线MOEA。

> This letter investigates an unmanned aerial vehicle (UAV) network with integrated sensing and communication (ISAC) systems, where multiple UAVs simultaneously sense the locations of ground users and provide communication services with radars. To find the trade-off between communication and sensing (C\&S) in the system, we formulate a multi-objective optimization problem (MOP) to maximize the total network utility and the localization Cramér-Rao bounds (CRB) of ground users, which jointly optimizes the deployment and power control of UAVs. Inspired by the huge potential of large language models (LLM) for prediction and inference, we propose an LLM-enabled decomposition-based multi-objective evolutionary algorithm (LEDMA) for solving the highly non-convex MOP. We first adopt a decomposition-based scheme to decompose the MOP into a series of optimization sub-problems. We second integrate LLMs as black-box search operators with MOP-specifically designed prompt engineering into the framework of MOEA to solve optimization sub-problems simultaneously. Numerical results demonstrate that the proposed LEDMA can find the clear trade-off between C\&S and outperforms baseline MOEAs in terms of obtained Pareto fronts and convergence.

[Arxiv](https://arxiv.org/abs/2410.05062)