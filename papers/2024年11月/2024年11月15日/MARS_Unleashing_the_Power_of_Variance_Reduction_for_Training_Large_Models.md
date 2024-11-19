# MARS：释放方差减少用于训练大型模型的强大力量

发布时间：2024年11月15日

`LLM应用` `人工智能`

> MARS: Unleashing the Power of Variance Reduction for Training Large Models

# 摘要

> 训练深度神经网络，尤其是近来的大型模型，都需要高效且可扩展的优化器。诸如 Adam、AdamW 及其变体之类的自适应梯度算法一直是关键所在。尽管过去十年里出现了众多旨在加速凸和非凸环境下随机优化的方差缩减算法，但在训练深度神经网络或大型语言模型时，方差缩减并未广泛成功。所以，在现代人工智能中，它仍是不太受青睐的方法。在本文中，为释放方差缩减在大型模型高效训练中的威力，我们提出了一个统一的优化框架——MARS（让方差缩减大放异彩），它通过缩放的随机递归动量技术将预处理梯度方法与方差缩减相融合。在这个框架内，我们分别引入了基于 AdamW、Lion 和 Shampoo 进行预处理梯度更新的三个 MARS 实例。我们还建立了我们的算法与现有优化器之间的联系。训练 GPT-2 模型的实验结果显示，MARS 始终大幅优于 AdamW。

> Training deep neural networks--and more recently, large models--demands efficient and scalable optimizers. Adaptive gradient algorithms like Adam, AdamW, and their variants have been central to this task. Despite the development of numerous variance reduction algorithms in the past decade aimed at accelerating stochastic optimization in both convex and nonconvex settings, variance reduction has not found widespread success in training deep neural networks or large language models. Consequently, it has remained a less favored approach in modern AI. In this paper, to unleash the power of variance reduction for efficient training of large models, we propose a unified optimization framework, MARS (Make vAriance Reduction Shine), which reconciles preconditioned gradient methods with variance reduction via a scaled stochastic recursive momentum technique. Within our framework, we introduce three instances of MARS that leverage preconditioned gradient updates based on AdamW, Lion, and Shampoo, respectively. We also draw a connection between our algorithms and existing optimizers. Experimental results on training GPT-2 models indicate that MARS consistently outperforms AdamW by a large margin.

[Arxiv](https://arxiv.org/abs/2411.10438)