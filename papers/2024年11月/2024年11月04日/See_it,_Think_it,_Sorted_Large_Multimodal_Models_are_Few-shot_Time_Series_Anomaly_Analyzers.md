# 看到它，想到它，解决它：大型多模态模型是少样本时间序列异常分析器

发布时间：2024年11月04日

`LLM应用` `网络服务` `时间序列异常检测`

> See it, Think it, Sorted: Large Multimodal Models are Few-shot Time Series Anomaly Analyzers

# 摘要

> 时间序列异常检测（TSAD）由于各领域时间序列数据的快速增长而变得越来越重要。例如，网络服务数据中的异常可能预示着系统故障或服务器故障等严重事件，因此需要及时检测和响应。然而，大多数现有的 TSAD 方法严重依赖手动特征工程或需要大量有标签的训练数据，同时可解释性也有限。为了应对这些挑战，我们引入了一个开创性的框架，称为时间序列异常多模态分析器（TAMA），它利用大型多模态模型（LMM）的能力来增强时间序列数据中异常的检测和解释。通过将时间序列转换为 LMM 能够有效处理的视觉格式，TAMA 利用少样本的上下文学习能力来减少对大量有标签数据集的依赖。我们的方法通过在多个真实世界数据集上进行严格的实验得到验证，其中 TAMA 在 TSAD 任务中始终优于最先进的方法。此外，TAMA 提供了丰富的、基于自然语言的语义分析，为检测到的异常的性质提供了更深入的见解。此外，我们贡献了首批包含异常检测标签、异常类型标签和上下文描述的开源数据集之一，促进了这一关键领域的更广泛探索和进步。最终，TAMA 不仅在异常检测方面表现出色，还为理解异常的根本原因提供了全面的方法，通过创新的方法和见解推动了 TSAD 的发展。

> Time series anomaly detection (TSAD) is becoming increasingly vital due to the rapid growth of time series data across various sectors. Anomalies in web service data, for example, can signal critical incidents such as system failures or server malfunctions, necessitating timely detection and response. However, most existing TSAD methodologies rely heavily on manual feature engineering or require extensive labeled training data, while also offering limited interpretability. To address these challenges, we introduce a pioneering framework called the Time Series Anomaly Multimodal Analyzer (TAMA), which leverages the power of Large Multimodal Models (LMMs) to enhance both the detection and interpretation of anomalies in time series data. By converting time series into visual formats that LMMs can efficiently process, TAMA leverages few-shot in-context learning capabilities to reduce dependence on extensive labeled datasets. Our methodology is validated through rigorous experimentation on multiple real-world datasets, where TAMA consistently outperforms state-of-the-art methods in TSAD tasks. Additionally, TAMA provides rich, natural language-based semantic analysis, offering deeper insights into the nature of detected anomalies. Furthermore, we contribute one of the first open-source datasets that includes anomaly detection labels, anomaly type labels, and contextual description, facilitating broader exploration and advancement within this critical field. Ultimately, TAMA not only excels in anomaly detection but also provides a comprehensive approach for understanding the underlying causes of anomalies, pushing TSAD forward through innovative methodologies and insights.

[Arxiv](https://arxiv.org/abs/2411.02465)