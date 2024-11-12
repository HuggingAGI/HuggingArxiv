# 在偏好优化中学习损失景观

发布时间：2024年11月10日

`LLM应用` `优化算法` `实证研究`

> Learning Loss Landscapes in Preference Optimization

# 摘要

> 我们提出了一项实证研究，调查偏好数据集的特定属性，如混合质量或噪声数据，如何影响偏好优化（PO）算法的性能。我们在 MuJoCo 环境中进行的实验揭示了几种情况，在这些情况下，最先进的 PO 方法的性能显著下降。为了解决这个问题，我们引入了一个基于镜像下降的新 PO 框架，对于镜像映射的特定选择，它可以恢复像直接偏好优化（DPO）和赔率比偏好优化（ORPO）这样的现有方法。在这个框架内，我们采用进化策略来发现能够处理已识别的问题场景的新损失函数。这些新的损失函数在几个任务中比 DPO 和 ORPO 带来了显著的性能改进。此外，我们通过将发现的损失函数应用于使用混合质量数据微调大型语言模型来展示我们方法的泛化能力，在这方面它们优于 ORPO。

> We present an empirical study investigating how specific properties of preference datasets, such as mixed-quality or noisy data, affect the performance of Preference Optimization (PO) algorithms. Our experiments, conducted in MuJoCo environments, reveal several scenarios where state-of-the-art PO methods experience significant drops in performance. To address this issue, we introduce a novel PO framework based on mirror descent, which can recover existing methods like Direct Preference Optimization (DPO) and Odds-Ratio Preference Optimization (ORPO) for specific choices of the mirror map. Within this framework, we employ evolutionary strategies to discover new loss functions capable of handling the identified problematic scenarios. These new loss functions lead to significant performance improvements over DPO and ORPO across several tasks. Additionally, we demonstrate the generalization capability of our approach by applying the discovered loss functions to fine-tuning large language models using mixed-quality data, where they outperform ORPO.

[Arxiv](https://arxiv.org/abs/2411.06568)