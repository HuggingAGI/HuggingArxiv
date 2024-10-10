# 自注意力模型中的动态亚稳态

发布时间：2024年10月09日

`LLM理论` `人工智能` `机器学习`

> Dynamic metastability in the self-attention model

# 摘要

> 我们探讨了自注意力模型，这一单位球上的相互作用粒子系统，作为 Transformer 的简化模型，后者是大型语言模型成功的关键架构。我们证实了 [GLPR23] 中提出的动态亚稳态现象：粒子虽最终会聚成单一簇，但在指数级长时间内，它们会困于多个簇的配置附近。通过梯度流视角，我们将这一现象与 Otto 和 Reznikoff 的梯度流慢运动框架相联系。此外，我们深入研究了亚稳态后的动力学，发现能量在有限时间内达到峰值，呈现阶梯状轨迹，类似鞍点间的跃迁，这与近期两层神经网络训练动力学的研究相呼应。

> We consider the self-attention model - an interacting particle system on the unit sphere, which serves as a toy model for Transformers, the deep neural network architecture behind the recent successes of large language models. We prove the appearance of dynamic metastability conjectured in [GLPR23] - although particles collapse to a single cluster in infinite time, they remain trapped near a configuration of several clusters for an exponentially long period of time. By leveraging a gradient flow interpretation of the system, we also connect our result to an overarching framework of slow motion of gradient flows proposed by Otto and Reznikoff [OR07] in the context of coarsening and the Allen-Cahn equation. We finally probe the dynamics beyond the exponentially long period of metastability, and illustrate that, under an appropriate time-rescaling, the energy reaches its global maximum in finite time and has a staircase profile, with trajectories manifesting saddle-to-saddle-like behavior, reminiscent of recent works in the analysis of training dynamics via gradient descent for two-layer neural networks.

[Arxiv](https://arxiv.org/abs/2410.06833)