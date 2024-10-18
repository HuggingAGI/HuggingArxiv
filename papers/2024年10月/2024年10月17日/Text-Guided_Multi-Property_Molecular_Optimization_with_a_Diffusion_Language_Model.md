# 借助扩散语言模型，实现文本引导的多属性分子优化

发布时间：2024年10月17日

`LLM应用` `药物发现`

> Text-Guided Multi-Property Molecular Optimization with a Diffusion Language Model

# 摘要

> 分子优化 (MO) 是药物发现的关键环节，旨在将生成的分子优化以满足工业需求。现有方法主要依赖外部属性预测器进行迭代优化，但在广阔的化学空间中学习所有分子样本几乎不可能，导致预测过程中引入误差和噪声。为此，我们提出了一种基于 transformer 的扩散语言模型 (TransDLM) 的文本引导多属性分子优化方法。TransDLM 利用标准化化学命名法隐式嵌入属性要求，防止扩散过程中的错误传播。在详细文本描述的指导下，TransDLM 优化分子，保留核心结构并确保相似性。此外，TransDLM 能同时处理多个分子，非常适合通过分布式计算进行大规模优化。实验表明，我们的方法在分子结构相似性和化学属性优化方面超越了现有技术。代码已公开，详见：https://anonymous.4open.science/r/TransDLM-A901。

> Molecular optimization (MO) is a crucial stage in drug discovery in which task-oriented generated molecules are optimized to meet practical industrial requirements. Existing mainstream MO approaches primarily utilize external property predictors to guide iterative property optimization. However, learning all molecular samples in the vast chemical space is unrealistic for predictors. As a result, errors and noise are inevitably introduced during property prediction due to the nature of approximation. This leads to discrepancy accumulation, generalization reduction and suboptimal molecular candidates. In this paper, we propose a text-guided multi-property molecular optimization method utilizing transformer-based diffusion language model (TransDLM). TransDLM leverages standardized chemical nomenclature as semantic representations of molecules and implicitly embeds property requirements into textual descriptions, thereby preventing error propagation during diffusion process. Guided by physically and chemically detailed textual descriptions, TransDLM samples and optimizes encoded source molecules, retaining core scaffolds of source molecules and ensuring structural similarities. Moreover, TransDLM enables simultaneous sampling of multiple molecules, making it ideal for scalable, efficient large-scale optimization through distributed computation on web platforms. Furthermore, our approach surpasses state-of-the-art methods in optimizing molecular structural similarity and enhancing chemical properties on the benchmark dataset. The code is available at: https://anonymous.4open.science/r/TransDLM-A901.

[Arxiv](https://arxiv.org/abs/2410.13597)