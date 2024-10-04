# DivScene：通过多样场景与对象，评估 LVLMs 在对象导航中的表现

发布时间：2024年10月03日

`Agent` `机器人` `自动驾驶`

> DivScene: Benchmarking LVLMs for Object Navigation with Diverse Scenes and Objects

# 摘要

> 在未知环境中导航物体对现实应用中的具身代理至关重要。尽管技术进步显著，但以往研究多聚焦于有限场景和目标。本文探讨了在多样场景中导航至不同目标的新任务，并推出了包含4,614个场景的DivScene数据集。通过模仿学习微调大型视觉语言模型（LVLM），我们构建了端到端代理NatVLM，并引入CoT解释轨迹提升性能。实验表明，无需人类监督，基于LVLM的代理在BFS规划的最短路径上表现优异，成功率超越GPT-4o 20%以上，且展现出强大的泛化能力。

> Object navigation in unknown environments is crucial for deploying embodied agents in real-world applications. While we have witnessed huge progress due to large-scale scene datasets, faster simulators, and stronger models, previous studies mainly focus on limited scene types and target objects. In this paper, we study a new task of navigating to diverse target objects in a large number of scene types. To benchmark the problem, we present a large-scale scene dataset, DivScene, which contains 4,614 scenes across 81 different types. With the dataset, we build an end-to-end embodied agent, NatVLM, by fine-tuning a Large Vision Language Model (LVLM) through imitation learning. The LVLM is trained to take previous observations from the environment and generate the next actions. We also introduce CoT explanation traces of the action prediction for better performance when tuning LVLMs. Our extensive experiments find that we can build a performant LVLM-based agent through imitation learning on the shortest paths constructed by a BFS planner without any human supervision. Our agent achieves a success rate that surpasses GPT-4o by over 20%. Meanwhile, we carry out various analyses showing the generalization ability of our agent.

[Arxiv](https://arxiv.org/abs/2410.02730)