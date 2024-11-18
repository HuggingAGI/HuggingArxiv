# 用于多维预测的因果时间序列同步

发布时间：2024年11月15日

`其他` `过程工业` `数字孪生`

> Causal Time-Series Synchronization for Multi-Dimensional Forecasting

# 摘要

> 过程工业对数字孪生寄予厚望，这需要能在不同任务和领域通用的建模方法，比如基础模型，这些领域可能存在不同的数据维度和分布变化。尽管在自然语言处理和计算机视觉领域已获成功，但在过程工业的数字孪生场景中，由于多维时间序列数据、滞后的因果依赖、复杂的因果结构以及（外生）变量数量的变化等挑战，利用（自）监督信号对通用模型进行迁移学习仍未得到充分探索。我们提出了一种新颖的通道依赖型预训练策略，借助同步的因果对，将多维时间序列数据分解为因果变量对，以应对这些挑战。我们的方法重点在于：（一）运用数据驱动的方法识别高度滞后的因果关系；（二）同步因果对以生成通道依赖型预训练的训练样本；（三）评估此方法在通道依赖型预测中的有效性。我们的实验结果显示，与传统训练方法相比，在预测精度和泛化能力上有显著提升。

> The process industry's high expectations for Digital Twins require modeling approaches that can generalize across tasks and diverse domains with potentially different data dimensions and distributional shifts i.e., Foundational Models. Despite success in natural language processing and computer vision, transfer learning with (self-) supervised signals for pre-training general-purpose models is largely unexplored in the context of Digital Twins in the process industry due to challenges posed by multi-dimensional time-series data, lagged cause-effect dependencies, complex causal structures, and varying number of (exogenous) variables. We propose a novel channel-dependent pre-training strategy that leverages synchronized cause-effect pairs to overcome these challenges by breaking down the multi-dimensional time-series data into pairs of cause-effect variables. Our approach focuses on: (i) identifying highly lagged causal relationships using data-driven methods, (ii) synchronizing cause-effect pairs to generate training samples for channel-dependent pre-training, and (iii) evaluating the effectiveness of this approach in channel-dependent forecasting. Our experimental results demonstrate significant improvements in forecasting accuracy and generalization capability compared to traditional training methods.

[Arxiv](https://arxiv.org/abs/2411.10152)