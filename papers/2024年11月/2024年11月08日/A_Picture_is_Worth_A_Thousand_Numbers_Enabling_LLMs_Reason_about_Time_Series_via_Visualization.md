# 一张图片胜过一千个数字：通过可视化使大型语言模型能够对时间序列进行推理

发布时间：2024年11月08日

`LLM应用` `时间序列推理` `语言模型`

> A Picture is Worth A Thousand Numbers: Enabling LLMs Reason about Time Series via Visualization

# 摘要

> 大型语言模型（LLMs）在多个领域都展现出了推理能力，但在时间序列推理（TsR）方面的探索还很不足，而时间序列推理在现实世界中无处不在。在这项工作中，我们提出了 TimerBed，这是第一个用于评估 LLMs 的 TsR 性能的综合测试平台。具体来说，TimerBed 包括具有现实世界任务的分层推理模式、LLMs 和推理策略的全面组合，以及作为比较基准的各种监督模型。我们使用 TimerBed 进行了广泛的实验，测试了多种当前的信念，并验证了 LLMs 在 TsR 中的初步失败，零样本（ZST）的无效性和少样本上下文学习（ICL）的性能下降就是证明。此外，我们确定了一个可能的根本原因：数据的数值建模。为了解决这个问题，我们提出了一个基于提示的解决方案 VL-Time，使用可视化建模数据和语言引导推理。实验结果表明，VL-Time 使多模态 LLMs 能够成为不平凡的 ZST 和强大的时间序列 ICL 推理器，实现了约 140％的平均性能提升和 99％的平均令牌成本降低。

> Large language models (LLMs), with demonstrated reasoning abilities across multiple domains, are largely underexplored for time-series reasoning (TsR), which is ubiquitous in the real world. In this work, we propose TimerBed, the first comprehensive testbed for evaluating LLMs' TsR performance. Specifically, TimerBed includes stratified reasoning patterns with real-world tasks, comprehensive combinations of LLMs and reasoning strategies, and various supervised models as comparison anchors. We perform extensive experiments with TimerBed, test multiple current beliefs, and verify the initial failures of LLMs in TsR, evidenced by the ineffectiveness of zero shot (ZST) and performance degradation of few shot in-context learning (ICL). Further, we identify one possible root cause: the numerical modeling of data. To address this, we propose a prompt-based solution VL-Time, using visualization-modeled data and language-guided reasoning. Experimental results demonstrate that Vl-Time enables multimodal LLMs to be non-trivial ZST and powerful ICL reasoners for time series, achieving about 140% average performance improvement and 99% average token costs reduction.

[Arxiv](https://arxiv.org/abs/2411.06018)