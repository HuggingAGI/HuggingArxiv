# Zebra：专为解决参数化偏微分方程而设计的上下文学习与生成预训练技术

发布时间：2024年10月04日

`LLM应用` `科学计算` `人工智能`

> Zebra: In-Context and Generative Pretraining for Solving Parametric PDEs

# 摘要

> 解决时间依赖的参数偏微分方程 (PDEs) 极具挑战，因为模型需适应参数变化，如系数、强迫项和边界条件。数据驱动的神经求解器要么依赖于从 PDE 参数分布中采样的数据进行训练，以期模型能推广到新实例，要么依赖基于梯度的适应和元学习，从观察中隐式编码动态，但这通常增加了推理复杂性。受大型语言模型 (LLMs) 的 in-context learning 能力启发，我们推出了 Zebra，一种创新的生成自回归变换器，专为解决参数 PDEs 而设计，无需在推理时进行梯度适应。通过在预训练和推理中利用 in-context 信息，Zebra 通过条件输入序列动态适应新任务，这些输入序列包含上下文轨迹或先前状态。这种方法使 Zebra 能灵活处理任意大小的上下文输入，并通过采样多个解轨迹支持不确定性量化。我们在多种挑战性 PDE 场景中评估了 Zebra，展示了其卓越的适应性、鲁棒性和性能。

> Solving time-dependent parametric partial differential equations (PDEs) is challenging, as models must adapt to variations in parameters such as coefficients, forcing terms, and boundary conditions. Data-driven neural solvers either train on data sampled from the PDE parameters distribution in the hope that the model generalizes to new instances or rely on gradient-based adaptation and meta-learning to implicitly encode the dynamics from observations. This often comes with increased inference complexity. Inspired by the in-context learning capabilities of large language models (LLMs), we introduce Zebra, a novel generative auto-regressive transformer designed to solve parametric PDEs without requiring gradient adaptation at inference. By leveraging in-context information during both pre-training and inference, Zebra dynamically adapts to new tasks by conditioning on input sequences that incorporate context trajectories or preceding states. This approach enables Zebra to flexibly handle arbitrarily sized context inputs and supports uncertainty quantification through the sampling of multiple solution trajectories. We evaluate Zebra across a variety of challenging PDE scenarios, demonstrating its adaptability, robustness, and superior performance compared to existing approaches.

[Arxiv](https://arxiv.org/abs/2410.03437)