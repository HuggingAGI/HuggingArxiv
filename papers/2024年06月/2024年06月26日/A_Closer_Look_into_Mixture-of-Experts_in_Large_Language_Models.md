# 深入剖析大型语言模型中的专家混合策略

发布时间：2024年06月26日

`LLM理论

这篇论文深入研究了混合专家（MoE）大型语言模型的内部机制，分析了其参数和行为，并提供了关于路由器设计和专家分配的建议。这些研究内容主要关注于大型语言模型（LLM）的理论层面，特别是MoE模型的内部工作原理和性能优化，因此属于LLM理论分类。` `机器学习`

> A Closer Look into Mixture-of-Experts in Large Language Models

# 摘要

> 混合专家（MoE）因其独特性能，在语言任务上备受瞩目。MoE通过稀疏激活参数，在不损计算效率的前提下扩大模型规模，巧妙平衡了性能与成本。但MoE的内在机制尚待深究，其模块化程度亦存疑。本文首次深入MoE大型语言模型，详尽分析了三种MoE模型的参数与行为，揭示了神经元如细粒度专家般运作、路由器偏好输出范数大的专家、专家多样性随层数增加而增长（最后一层除外）等现象。我们为MoE实践者提供了路由器设计与专家分配的建议，期待此研究能启迪MoE及其他模块化架构的未来探索。相关代码已发布于https://github.com/kamanphoebe/Look-into-MoEs。

> Mixture-of-experts (MoE) is gaining increasing attention due to its unique properties and remarkable performance, especially for language tasks. By sparsely activating a subset of parameters for each token, MoE architecture could increase the model size without sacrificing computational efficiency, achieving a better trade-off between performance and training costs. However, the underlying mechanism of MoE still lacks further exploration, and its modularization degree remains questionable. In this paper, we make an initial attempt to understand the inner workings of MoE-based large language models. Concretely, we comprehensively study the parametric and behavioral features of three recent MoE-based models and reveal some intriguing observations, including (1) Neurons act like fine-grained experts. (2) The router of MoE usually selects experts with larger output norms. (3) The expert diversity increases as the layer increases, while the last layer is an outlier. Based on the observations, we also provide suggestions for a broad spectrum of MoE practitioners, such as router design and expert allocation. We hope this work could shed light on future research on the MoE framework and other modular architectures. Code is available at https://github.com/kamanphoebe/Look-into-MoEs.

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x1.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x2.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x3.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x4.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x5.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x6.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x7.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x8.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x9.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x10.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x11.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x12.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x13.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x14.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x15.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x16.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x17.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x18.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x19.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x20.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x21.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x22.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x23.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x24.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x25.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x26.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x27.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x28.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x29.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x30.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x31.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x32.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x33.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x34.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x35.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x36.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x37.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x38.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x39.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x40.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x41.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x42.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x43.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x44.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x45.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x46.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x47.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x48.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x49.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/layer_60.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x50.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/layer_7.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/layer_7.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x51.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/layer_25.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/layer_25.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x52.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/layer_40.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/layer_40.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x53.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x54.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x55.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x56.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x57.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x58.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x59.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x60.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x61.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x62.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x63.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x64.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x65.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x66.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x67.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x68.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x69.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x70.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x71.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x72.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x73.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x74.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x75.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x76.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x77.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x78.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x79.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x80.png)

![深入剖析大型语言模型中的专家混合策略](../../../paper_images/2406.18219/x81.png)

[Arxiv](https://arxiv.org/abs/2406.18219)