# 利用LLM进行知识剪枝，优化边缘设备上的时间序列数据分析

发布时间：2024年06月12日

`LLM应用

这篇论文主要探讨了如何通过知识剪枝（KP）方法优化大型语言模型（LLMs）在时间序列数据处理中的应用，特别是在资源受限环境下的性能提升。论文提出了一种新型的学习方法，通过剪除冗余知识并将相关知识提炼至目标模型，以降低模型大小和计算成本。这种方法在边缘计算设备上的两个基本任务中展示了显著的性能提升。因此，这篇论文属于LLM应用类别，因为它关注的是LLMs在特定应用场景下的优化和实际应用效果。` `时间序列分析` `边缘计算`

> LLM-based Knowledge Pruning for Time Series Data Analytics on Edge-computing Devices

# 摘要

> 时间序列数据的规模和多样性限制了神经网络的性能，常导致过拟合。而大型语言模型（LLMs）在多个领域展现出卓越的泛化能力。尽管基于LLMs的时间序列处理方法层出不穷，但它们在资源受限环境中因高计算需求而受限。为此，我们提出了知识剪枝（KP），一种新型的时间序列学习方法。KP认为，对于特定任务，LLMs所学的大部分知识是冗余的，仅有“相关知识”有用。KP通过剪除冗余知识并将相关知识提炼至目标模型，显著降低了模型大小和计算成本，且在训练和测试中无需加载整个LLM，进一步减轻了计算负担。实验证明，KP在边缘计算设备上的两个基本任务中，通过八个不同环境和网络的测试，有效学习了相关知识，显著提升了性能，回归任务平均提升19.7%，分类任务最高提升13.7%，达到了业界领先水平。

> Limited by the scale and diversity of time series data, the neural networks trained on time series data often overfit and show unsatisfacotry performances. In comparison, large language models (LLMs) recently exhibit impressive generalization in diverse fields. Although massive LLM based approaches are proposed for time series tasks, these methods require to load the whole LLM in both training and reference. This high computational demands limit practical applications in resource-constrained settings, like edge-computing and IoT devices. To address this issue, we propose Knowledge Pruning (KP), a novel paradigm for time series learning in this paper. For a specific downstream task, we argue that the world knowledge learned by LLMs is much redundant and only the related knowledge termed as "pertinent knowledge" is useful. Unlike other methods, our KP targets to prune the redundant knowledge and only distill the pertinent knowledge into the target model. This reduces model size and computational costs significantly. Additionally, different from existing LLM based approaches, our KP does not require to load the LLM in the process of training and testing, further easing computational burdens. With our proposed KP, a lightweight network can effectively learn the pertinent knowledge, achieving satisfactory performances with a low computation cost. To verify the effectiveness of our KP, two fundamental tasks on edge-computing devices are investigated in our experiments, where eight diverse environments or benchmarks with different networks are used to verify the generalization of our KP. Through experiments, our KP demonstrates effective learning of pertinent knowledge, achieving notable performance improvements in regression (19.7% on average) and classification (up to 13.7%) tasks, showcasing state-of-the-art results.

![利用LLM进行知识剪枝，优化边缘设备上的时间序列数据分析](../../../paper_images/2406.08765/diagram.png)

![利用LLM进行知识剪枝，优化边缘设备上的时间序列数据分析](../../../paper_images/2406.08765/pipeline5.png)

![利用LLM进行知识剪枝，优化边缘设备上的时间序列数据分析](../../../paper_images/2406.08765/analysis_rulv.png)

![利用LLM进行知识剪枝，优化边缘设备上的时间序列数据分析](../../../paper_images/2406.08765/analysis_harv.jpg)

[Arxiv](https://arxiv.org/abs/2406.08765)