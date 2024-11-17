# 无需领域知识即可实现高保真的蜂窝网络控制平面流量生成

发布时间：2024年11月11日

`其他` `移动网络` `机器学习`

> High-Fidelity Cellular Network Control-Plane Traffic Generation without Domain Knowledge

# 摘要

> 随着移动核心网络（MCN）架构的迅速演进，大规模的控制平面流量（CPT）跟踪对于研发界研究 MCN 设计和性能优化极为关键。现有的控制平面流量生成器 SMM 高度依赖领域知识，随着领域的发展需要重新设计。在本项工作中，我们探究了借助生成式机器学习模型开发高保真 MCN 控制平面流量生成器的可行性。我们明确了合成高保真 CPT 的关键挑战，涵盖通用（针对数据平面）的要求，例如多模态特征关系，以及独特要求，比如有状态语义和长期（一天中的时段）数据变化。我们指出，在数据平面流量方面表现出色的最先进的基于生成对抗网络（GAN）的方法无法满足 CPT 的这些保真要求，于是开发了基于 Transformer 的模型 CPT-GPT，它能够精准捕捉每个流量流（同一 UE 的控制事件）中样本之间的复杂依存关系，无需 GAN。我们对 CPT-GPT 在大规模控制平面流量跟踪上的评估显示：（1）它不依赖领域知识，合成的控制平面流量保真度与 SMM 相当；（2）与现有的基于 GAN 的方法相比，它使违反有状态语义的流的比例降低了两个数量级，流的停留时间分布的最大 y 距离减少了 16.0％，推导新的每小时模型的迁移学习时间缩短了 3.36 倍。

> With rapid evolution of mobile core network (MCN) architectures, large-scale control-plane traffic (CPT) traces are critical to studying MCN design and performance optimization by the R&D community. The prior-art control-plane traffic generator SMM heavily relies on domain knowledge which requires re-design as the domain evolves. In this work, we study the feasibility of developing a high-fidelity MCN control plane traffic generator by leveraging generative ML models. We identify key challenges in synthesizing high-fidelity CPT including generic (to data-plane) requirements such as multimodality feature relationships and unique requirements such as stateful semantics and long-term (time-of-day) data variations. We show state-of-the-art, generative adversarial network (GAN)-based approaches shown to work well for data-plane traffic cannot meet these fidelity requirements of CPT, and develop a transformer-based model, CPT-GPT, that accurately captures complex dependencies among the samples in each traffic stream (control events by the same UE) without the need for GAN. Our evaluation of CPT-GPT on a large-scale control-plane traffic trace shows that (1) it does not rely on domain knowledge yet synthesizes control-plane traffic with comparable fidelity as SMM; (2) compared to the prior-art GAN-based approach, it reduces the fraction of streams that violate stateful semantics by two orders of magnitude, the max y-distance of sojourn time distributions of streams by 16.0%, and the transfer learning time in deriving new hourly models by 3.36x.

[Arxiv](https://arxiv.org/abs/2411.07345)