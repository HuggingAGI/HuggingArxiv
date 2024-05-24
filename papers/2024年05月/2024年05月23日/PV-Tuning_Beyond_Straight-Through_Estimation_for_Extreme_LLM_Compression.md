# PV-Tuning：突破传统直接估计法，引领极端大型语言模型压缩新篇章

发布时间：2024年05月23日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）的极致压缩技术，特别是在每参数1-2位的目标上，以及量化感知微调策略的应用。这些内容涉及LLM的理论研究和模型优化，而不是具体的应用案例或Agent的行为研究。因此，它更适合归类于LLM理论。` `模型压缩` `机器学习`

> PV-Tuning: Beyond Straight-Through Estimation for Extreme LLM Compression

# 摘要

> 在追求大型语言模型（LLMs）的极致压缩，即每参数1-2位的目标上，研究兴趣日益浓厚，这使得模型能在资源有限的设备上高效运行。尽管现有研究聚焦于提升一次性量化技术和权重表示，但纯训练后方法在精度与位宽的权衡上已显收益递减。先进的量化方法如QuIP#和AQLM通过在有限校准数据上微调压缩参数来优化性能，但这些方法常依赖直通估计器（STE），其效果在此情境下尚不明朗。本研究对STE在极端LLM压缩中的应用提出质疑，并系统探讨了量化感知微调策略。我们提出的PV-Tuning框架，不依赖特定表示，不仅整合并提升了现有微调策略，还在特定条件下确保了收敛性。实际应用中，PV-Tuning在1-2位向量量化上超越了以往技术，特别是在Llama和Mistral等高性能模型上。通过PV-Tuning，我们首次为Llama 2系列模型实现了每参数2位的Pareto最优量化。

> There has been significant interest in "extreme" compression of large language models (LLMs), i.e., to 1-2 bits per parameter, which allows such models to be executed efficiently on resource-constrained devices. Existing work focused on improved one-shot quantization techniques and weight representations; yet, purely post-training approaches are reaching diminishing returns in terms of the accuracy-vs-bit-width trade-off. State-of-the-art quantization methods such as QuIP# and AQLM include fine-tuning (part of) the compressed parameters over a limited amount of calibration data; however, such fine-tuning techniques over compressed weights often make exclusive use of straight-through estimators (STE), whose performance is not well-understood in this setting. In this work, we question the use of STE for extreme LLM compression, showing that it can be sub-optimal, and perform a systematic study of quantization-aware fine-tuning strategies for LLMs. We propose PV-Tuning - a representation-agnostic framework that generalizes and improves upon existing fine-tuning strategies, and provides convergence guarantees in restricted cases. On the practical side, when used for 1-2 bit vector quantization, PV-Tuning outperforms prior techniques for highly-performant models such as Llama and Mistral. Using PV-Tuning, we achieve the first Pareto-optimal quantization for Llama 2 family models at 2 bits per parameter.

[Arxiv](https://arxiv.org/abs/2405.14852)