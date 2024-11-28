# LLM-ABBA：借由符号近似来理解时间序列

发布时间：2024年11月27日

`LLM应用` `时间序列`

> LLM-ABBA: Understand time series via symbolic approximation

# 摘要

> 大型语言模型（LLMs）在时间序列领域的成功已在过往研究中得以证实。借助符号化的时间序列表示，能够有效填补 LLMs 与时间序列之间的鸿沟。然而，余下的难题在于借助符号或 LLMs 的现有标记来挖掘隐藏在时间序列中的语义信息，同时依据时间序列的隐含信息调整 LLMs 的嵌入空间。名为自适应布朗桥基符号聚合（ABBA）的符号时间序列近似（STSA）方法，在运用 LLMs 的现有标记按照幅度和周期对时间序列模式进行建模从而保留显著的时间序列特征方面，成效卓著。
    在本文中，我们引入了一种名为 LLM-ABBA 的方法，它将 ABBA 融入大型语言模型，用于各类下游时间序列任务。通过对时间序列进行符号化处理，LLM-ABBA 在 UCR 以及三个医疗时间序列分类任务中，相较于近期的最先进水平（SOTA）表现优异。同时，ABBA 中引入了固定多边形链技巧，以在预测任务中避免明显的偏差，显著减轻了从符号转换为数值过程中因符号误用而产生的累积误差的影响。在时间序列回归任务中，LLM-ABBA 在时间序列外在回归（TSER）基准测试中达到了新的 SOTA 水平。与近期的 SOTA 时间序列预测结果相比，LLM-ABBA 也展现出了颇具竞争力的预测能力。我们认为这一框架还能够无缝拓展至其他时间序列任务。

> The success of large language models (LLMs) for time series has been demonstrated in previous work. Utilizing a symbolic time series representation, one can efficiently bridge the gap between LLMs and time series. However, the remaining challenge is to exploit the semantic information hidden in time series by using symbols or existing tokens of LLMs, while aligning the embedding space of LLMs according to the hidden information of time series. The symbolic time series approximation (STSA) method called adaptive Brownian bridge-based symbolic aggregation (ABBA) shows outstanding efficacy in preserving salient time series features by modeling time series patterns in terms of amplitude and period while using existing tokens of LLMs.
  In this paper, we introduce a method, called LLM-ABBA, that integrates ABBA into large language models for various downstream time series tasks. By symbolizing time series, LLM-ABBA compares favorably to the recent state-of-the-art (SOTA) in UCR and three medical time series classification tasks. Meanwhile, a fixed-polygonal chain trick in ABBA is introduced to \kc{avoid obvious drifting} during prediction tasks by significantly mitigating the effects of cumulative error arising from misused symbols during the transition from symbols to numerical values. In time series regression tasks, LLM-ABBA achieves the new SOTA on Time Series Extrinsic Regression (TSER) benchmarks. LLM-ABBA also shows competitive prediction capability compared to recent SOTA time series prediction results. We believe this framework can also seamlessly extend to other time series tasks.

[Arxiv](https://arxiv.org/abs/2411.18506)