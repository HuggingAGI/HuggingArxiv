# DistRL：专为设备控制代理设计的异步分布式强化学习框架

发布时间：2024年10月18日

`Agent` `移动设备` `人工智能`

> DistRL: An Asynchronous Distributed Reinforcement Learning Framework for On-Device Control Agents

# 摘要

> 在移动设备上，控制代理负责满足用户需求，实现无缝交互。集成多模态大型语言模型 (MLLM) 后，这些代理能更好地理解和执行复杂命令，提升用户体验。然而，由于数据有限和在线训练效率低，MLLM 的设备控制微调面临挑战。本文提出 DistRL 框架，通过集中训练和分散数据采集，提高在线 RL 微调效率。该框架还采用定制 RL 算法，平衡探索与数据利用，确保稳定训练。实验显示，DistRL 平均提升 3 倍训练效率，数据收集速度快 2.4 倍。训练后，DistRL 在 Android 任务上成功率提升 20%，显著优于现有方法。这些成果表明，DistRL 是高效可扩展的解决方案，显著提升设备控制任务的训练效率和性能。

> On-device control agents, especially on mobile devices, are responsible for operating mobile devices to fulfill users' requests, enabling seamless and intuitive interactions. Integrating Multimodal Large Language Models (MLLMs) into these agents enhances their ability to understand and execute complex commands, thereby improving user experience. However, fine-tuning MLLMs for on-device control presents significant challenges due to limited data availability and inefficient online training processes. This paper introduces DistRL, a novel framework designed to enhance the efficiency of online RL fine-tuning for mobile device control agents. DistRL employs centralized training and decentralized data acquisition to ensure efficient fine-tuning in the context of dynamic online interactions. Additionally, the framework is backed by our tailor-made RL algorithm, which effectively balances exploration with the prioritized utilization of collected data to ensure stable and robust training. Our experiments show that, on average, DistRL delivers a 3X improvement in training efficiency and enables training data collection 2.4X faster than the leading synchronous multi-machine methods. Notably, after training, DistRL achieves a 20% relative improvement in success rate compared to state-of-the-art methods on general Android tasks from an open benchmark, significantly outperforming existing approaches while maintaining the same training time. These results validate DistRL as a scalable and efficient solution, offering substantial improvements in both training efficiency and agent performance for real-world, in-the-wild device control tasks.

[Arxiv](https://arxiv.org/abs/2410.14803)