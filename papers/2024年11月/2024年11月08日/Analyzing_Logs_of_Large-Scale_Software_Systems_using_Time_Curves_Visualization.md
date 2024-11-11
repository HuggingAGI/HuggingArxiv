# 使用时间曲线可视化来分析大型软件系统的日志

发布时间：2024年11月08日

`LLM应用` `日志分析`

> Analyzing Logs of Large-Scale Software Systems using Time Curves Visualization

# 摘要

> 日志对于分析大规模软件系统至关重要，能提供有关系统健康、性能、安全威胁、潜在错误等方面的见解。然而，它们的混乱性质——以巨大的数量、缺乏标准和多变性为特征——使得手动分析变得复杂。聚类算法的使用可以通过将日志分组为较少的模板集来提供帮助，但这样做会丢失时间和关系上下文。相反，大型语言模型（LLM）可以提供有意义的解释，但难以有效地处理大量集合。此外，这两种方法的表示技术通常仅限于纯文本或传统图表，特别是在处理大规模系统时。在本文中，我们通过使用时间曲线将聚类和 LLM 总结与事件检测和多维缩放相结合，以产生一个整体的管道，能够对大量软件系统日志集合进行高效和自动的总结。我们方法的核心是提出一种半度量距离，有效地测量事件之间的相似性，从而实现有意义的表示。我们表明，我们的方法可以在没有先验知识的情况下解释从不同应用程序收集的日志的主要事件。我们还展示了该方法如何通过重叠多个投影用于检测并行和分布式系统中的一般趋势以及异常值。因此，我们期望在分析和解决全系统问题、识别性能瓶颈和安全风险、调试应用程序等方面所需的时间显著减少。

> Logs are crucial for analyzing large-scale software systems, offering insights into system health, performance, security threats, potential bugs, etc. However, their chaotic nature$unicode{x2013}$characterized by sheer volume, lack of standards, and variability$unicode{x2013}$makes manual analysis complex. The use of clustering algorithms can assist by grouping logs into a smaller set of templates, but lose the temporal and relational context in doing so. On the contrary, Large Language Models (LLMs) can provide meaningful explanations but struggle with processing large collections efficiently. Moreover, representation techniques for both approaches are typically limited to either plain text or traditional charting, especially when dealing with large-scale systems. In this paper, we combine clustering and LLM summarization with event detection and Multidimensional Scaling through the use of Time Curves to produce a holistic pipeline that enables efficient and automatic summarization of vast collections of software system logs. The core of our approach is the proposal of a semimetric distance that effectively measures similarity between events, thus enabling a meaningful representation. We show that our method can explain the main events of logs collected from different applications without prior knowledge. We also show how the approach can be used to detect general trends as well as outliers in parallel and distributed systems by overlapping multiple projections. As a result, we expect a significant reduction of the time required to analyze and resolve system-wide issues, identify performance bottlenecks and security risks, debug applications, etc.

[Arxiv](https://arxiv.org/abs/2411.05533)