# TSINR：借助隐式神经表示来捕获时间连续性，以实现时间序列异常检测

发布时间：2024年11月18日

`LLM应用` `时间序列` `异常检测`

> TSINR: Capturing Temporal Continuity via Implicit Neural Representations for Time Series Anomaly Detection

# 摘要

> 时间序列异常检测旨在找出数据中的异常模式或系统行为的偏离情况。基于重建的方法在该任务中占据主流，它们通过无监督学习获取逐点表示。然而，训练数据中未标注的异常点可能致使这些基于重建的方法学习和重建异常数据，进而带来捕捉正常模式的难题。在本文中，我们提出了一种基于隐式神经表示（INR）重建的时间序列异常检测方法，叫做 TSINR，以应对此挑战。由于频谱偏差的特性，TSINR 能优先处理低频信号，在高频异常数据上表现欠佳。具体来说，我们采用 INR 将时间序列数据参数化为连续函数，并运用基于变压器的架构来预测给定数据的 INR。由此，所提出的 TSINR 方法具备捕捉时间连续性的优点，因而对不连续的异常数据更为敏感。此外，我们还进一步设计了一种新颖的 INR 连续函数形式来学习通道间和通道内的信息，并借助预训练的大型语言模型来放大异常中的强烈波动。大量实验表明，与其他先进的基于重建的方法相比，TSINR 在单变量和多变量时间序列异常检测基准上均取得了出色的整体性能。我们的代码可供使用。

> Time series anomaly detection aims to identify unusual patterns in data or deviations from systems' expected behavior. The reconstruction-based methods are the mainstream in this task, which learn point-wise representation via unsupervised learning. However, the unlabeled anomaly points in training data may cause these reconstruction-based methods to learn and reconstruct anomalous data, resulting in the challenge of capturing normal patterns. In this paper, we propose a time series anomaly detection method based on implicit neural representation (INR) reconstruction, named TSINR, to address this challenge. Due to the property of spectral bias, TSINR enables prioritizing low-frequency signals and exhibiting poorer performance on high-frequency abnormal data. Specifically, we adopt INR to parameterize time series data as a continuous function and employ a transformer-based architecture to predict the INR of given data. As a result, the proposed TSINR method achieves the advantage of capturing the temporal continuity and thus is more sensitive to discontinuous anomaly data. In addition, we further design a novel form of INR continuous function to learn inter- and intra-channel information, and leverage a pre-trained large language model to amplify the intense fluctuations in anomalies. Extensive experiments demonstrate that TSINR achieves superior overall performance on both univariate and multivariate time series anomaly detection benchmarks compared to other state-of-the-art reconstruction-based methods. Our codes are available.

[Arxiv](https://arxiv.org/abs/2411.11641)