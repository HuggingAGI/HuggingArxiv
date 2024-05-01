# DiffuseLoco：利用离线数据集的扩散技术，实现实时腿部运动控制

发布时间：2024年04月30日

`Agent` `机器人技术` `计算机视觉`

> DiffuseLoco: Real-Time Legged Locomotion Control with Diffusion from Offline Datasets

# 摘要

> 本研究提出了 DiffuseLoco，这是一个创新的框架，旨在通过离线数据集训练多技能扩散策略，实现真实世界机器人的多样化技能实时控制。这一进展在计算机视觉、自然语言处理和机器人操作等离线学习领域取得了显著成果。然而，对于腿部机器人，尤其是集成多种技能的单一策略，传统的在线强化学习方法面临重大挑战。DiffuseLoco 通过扩散模型直接从多模态数据集中学习，为动态系统的实时控制提供了定制化设计，如递减视野控制和延迟输入，能够执行多种运动技能，实现零样本迁移至四足机器人，并支持在边缘计算设备上部署。此外，DiffuseLoco 能够灵活转换技能，并对环境变化表现出强大的适应性。在现实世界的广泛测试中，DiffuseLoco 在稳定性和速度跟踪方面超越了传统强化学习和非扩散式行为克隆方法。通过全面的消融研究，验证了其设计选择的有效性。这项工作为基于学习的大型腿部运动控制器的发展，通过扩展大型、富有表现力的模型和多样化的离线数据集，提供了新的思路。

> This work introduces DiffuseLoco, a framework for training multi-skill diffusion-based policies for dynamic legged locomotion from offline datasets, enabling real-time control of diverse skills on robots in the real world. Offline learning at scale has led to breakthroughs in computer vision, natural language processing, and robotic manipulation domains. However, scaling up learning for legged robot locomotion, especially with multiple skills in a single policy, presents significant challenges for prior online reinforcement learning methods. To address this challenge, we propose a novel, scalable framework that leverages diffusion models to directly learn from offline multimodal datasets with a diverse set of locomotion skills. With design choices tailored for real-time control in dynamical systems, including receding horizon control and delayed inputs, DiffuseLoco is capable of reproducing multimodality in performing various locomotion skills, zero-shot transfer to real quadrupedal robots, and it can be deployed on edge computing devices. Furthermore, DiffuseLoco demonstrates free transitions between skills and robustness against environmental variations. Through extensive benchmarking in real-world experiments, DiffuseLoco exhibits better stability and velocity tracking performance compared to prior reinforcement learning and non-diffusion-based behavior cloning baselines. The design choices are validated via comprehensive ablation studies. This work opens new possibilities for scaling up learning-based legged locomotion controllers through the scaling of large, expressive models and diverse offline datasets.

[Arxiv](https://arxiv.org/abs/2404.19264)