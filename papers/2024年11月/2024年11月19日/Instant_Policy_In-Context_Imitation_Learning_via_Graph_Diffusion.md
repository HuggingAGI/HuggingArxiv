# 即时策略：借助图扩散的上下文内模仿学习

发布时间：2024年11月19日

`LLM应用` `机器人` `机器学习`

> Instant Policy: In-Context Imitation Learning via Graph Diffusion

# 摘要

> 大型转换器的上下文学习能力令人瞩目，在此基础上，上下文模仿学习（ICIL）为机器人领域带来了极具潜力的机遇。我们推出了即时策略，仅需一两次演示就能即刻学习新任务（无需再训练），它通过两个关键部分来实现 ICIL。其一，通过图形表示引入归纳偏差，并将 ICIL 建模为带有学习扩散过程的图形生成问题，从而能够对演示、观察和动作进行结构化推理。其二，我们证明这样的模型能够利用伪演示（在模拟中生成的任意轨迹）进行训练，这些伪演示就像一个几乎无限的训练数据池。模拟和真实实验均表明，即时策略能够让机器人迅速学会各类日常任务。我们还展示了它如何成为跨实体和零样本转移到语言定义任务的基石。相关代码和视频可在 https://www.robot-learning.uk/instant-policy 获取。

> Following the impressive capabilities of in-context learning with large transformers, In-Context Imitation Learning (ICIL) is a promising opportunity for robotics. We introduce Instant Policy, which learns new tasks instantly (without further training) from just one or two demonstrations, achieving ICIL through two key components. First, we introduce inductive biases through a graph representation and model ICIL as a graph generation problem with a learned diffusion process, enabling structured reasoning over demonstrations, observations, and actions. Second, we show that such a model can be trained using pseudo-demonstrations - arbitrary trajectories generated in simulation - as a virtually infinite pool of training data. Simulated and real experiments show that Instant Policy enables rapid learning of various everyday robot tasks. We also show how it can serve as a foundation for cross-embodiment and zero-shot transfer to language-defined tasks. Code and videos are available at https://www.robot-learning.uk/instant-policy.

[Arxiv](https://arxiv.org/abs/2411.12633)