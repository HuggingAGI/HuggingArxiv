# MultiKG：用于攻击技术的高质量知识图谱表示的多源威胁情报聚合

发布时间：2024年11月13日

`LLM应用` `网络安全` `知识图谱`

> MultiKG: Multi-Source Threat Intelligence Aggregation for High-Quality Knowledge Graph Representation of Attack Techniques

# 摘要

> 攻击技术知识图谱的构建旨在将各种类型的攻击知识转化为结构化表示，以实现更有效的攻击过程建模。现有的方法通常依赖于文本数据，如网络威胁情报（CTI）报告，这些数据往往是粗粒度和非结构化的，导致知识图谱不完整和不准确。为了解决这些问题，我们通过将审计日志和静态代码分析与 CTI 报告一起纳入，扩展了攻击知识源，为构建攻击技术知识图谱提供更细粒度的数据。
  我们提出了 MultiKG，这是一个完全自动化的框架，它集成了多个威胁知识源。MultiKG 分别处理来自 CTI 报告、动态日志和静态代码的数据，然后将它们合并到一个统一的攻击知识图谱中。通过系统设计和利用大型语言模型（LLM），MultiKG 自动对这些来源的攻击图进行分析、构建和合并，生成细粒度、多源的攻击知识图谱。
  我们实现了 MultiKG，并使用来自 CTI 报告的 1,015 种真实攻击技术和 9,006 个攻击情报条目对其进行了评估。结果表明，MultiKG 有效地从各种来源提取攻击知识图谱，并将它们聚合为准确、全面的表示。通过案例研究，我们证明了我们的方法直接有益于攻击重建和检测等安全任务。

> The construction of attack technique knowledge graphs aims to transform various types of attack knowledge into structured representations for more effective attack procedure modeling. Existing methods typically rely on textual data, such as Cyber Threat Intelligence (CTI) reports, which are often coarse-grained and unstructured, resulting in incomplete and inaccurate knowledge graphs. To address these issues, we expand attack knowledge sources by incorporating audit logs and static code analysis alongside CTI reports, providing finer-grained data for constructing attack technique knowledge graphs.
  We propose MultiKG, a fully automated framework that integrates multiple threat knowledge sources. MultiKG processes data from CTI reports, dynamic logs, and static code separately, then merges them into a unified attack knowledge graph. Through system design and the utilization of the Large Language Model (LLM), MultiKG automates the analysis, construction, and merging of attack graphs across these sources, producing a fine-grained, multi-source attack knowledge graph.
  We implemented MultiKG and evaluated it using 1,015 real attack techniques and 9,006 attack intelligence entries from CTI reports. Results show that MultiKG effectively extracts attack knowledge graphs from diverse sources and aggregates them into accurate, comprehensive representations. Through case studies, we demonstrate that our approach directly benefits security tasks such as attack reconstruction and detection.

[Arxiv](https://arxiv.org/abs/2411.08359)