# TS-TCD：利用大型语言模型进行时序预测的三重跨模态知识蒸馏

发布时间：2024年09月23日

`LLM应用` `时间序列分析` `机器学习`

> TS-TCD: Triplet-Level Cross-Modal Distillation for Time-Series Forecasting Using Large Language Models

# 摘要

> 近年来，LLM 在时间序列分析中展现了强大的潜力，但现有方法在模态对齐上常显不足。为此，我们推出了 TS-TCD 框架，通过三层跨模态知识蒸馏机制，系统整合了动态自适应门控、逐层对比学习和最优传输驱动的输出对齐。实验证明，TS-TCD 在基准数据集上表现卓越，无论是准确性还是鲁棒性，均超越了传统方法。

> In recent years, large language models (LLMs) have shown great potential in time-series analysis by capturing complex dependencies and improving predictive performance. However, existing approaches often struggle with modality alignment, leading to suboptimal results. To address these challenges, we present a novel framework, TS-TCD, which introduces a comprehensive three-tiered cross-modal knowledge distillation mechanism. Unlike prior work that focuses on isolated alignment techniques, our framework systematically integrates: 1) Dynamic Adaptive Gating for Input Encoding and Alignment}, ensuring coherent alignment between time-series tokens and QR-decomposed textual embeddings; 2) Layer-Wise Contrastive Learning}, aligning intermediate representations across modalities to reduce feature-level discrepancies; and 3) Optimal Transport-Driven Output Alignment}, which ensures consistent output predictions through fine-grained cross-modal alignment. Extensive experiments on benchmark time-series datasets demonstrate that TS-TCD achieves state-of-the-art results, outperforming traditional methods in both accuracy and robustness.

[Arxiv](https://arxiv.org/abs/2409.14978)