# OWLed：用于高效自动驾驶框架的离群值加权分层剪枝

发布时间：2024年11月12日

`LLM应用` `自动驾驶` `模型压缩`

> OWLed: Outlier-weighed Layerwise Pruning for Efficient Autonomous Driving Framework

# 摘要

> 大型语言模型（LLMs）集成到自动驾驶系统中为环境理解和决策提供了有希望的增强。然而，在车辆本地部署 LLMs 的巨大计算需求使得这种方法对于实际的汽车应用不可行。为了应对这一挑战，我们引入了 OWLed，即用于高效自动驾驶框架的异常值加权分层剪枝，它利用异常值加权分层稀疏性进行模型压缩。我们的方法根据异常值特征的分布为不同的层分配不均匀的稀疏率，在无需微调的情况下显著减小了模型大小。为了确保压缩模型能很好地适应自动驾驶任务，我们将驾驶环境数据纳入校准和剪枝过程。我们的实证研究表明，编码器组件比 LLM 对剪枝更敏感，突出了其在系统中的关键作用。实验结果表明，OWLed 在感知、动作预测和语言理解方面优于现有方法，同时大幅降低了计算要求。这些发现强调了将先进的剪枝技术与 LLMs 相结合以开发能够处理复杂场景的高效和强大的自动驾驶系统的潜力。代码将公开可用。

> The integration of Large Language Models (LLMs) into autonomous driving systems offers promising enhancements in environmental understanding and decision-making. However, the substantial computational demands of deploying LLMs locally on vehicles render this approach unfeasible for real-world automotive applications. To address this challenge, we introduce OWLed, the Outlier-Weighed Layerwise Pruning for Efficient Autonomous Driving Framework that leverages outlier-weighted layerwise sparsity for model compression. Our method assigns non-uniform sparsity ratios to different layers based on the distribution of outlier features, significantly reducing the model size without the need for fine-tuning. To ensure the compressed model adapts well to autonomous driving tasks, we incorporate driving environment data into both the calibration and pruning processes. Our empirical studies reveal that the encoder component is more sensitive to pruning than the LLM, highlighting its critical role in the system. Experimental results demonstrate that OWLed outperforms existing methods in perception, action prediction, and language understanding while substantially lowering computational requirements. These findings underscore the potential of combining advanced pruning techniques with LLMs to develop efficient and robust autonomous driving systems capable of handling complex scenarios. Code will be made publicly available.

[Arxiv](https://arxiv.org/abs/2411.07711)