# XG-NID：结合异构图神经网络与大型语言模型，实现双模态网络入侵检测

发布时间：2024年08月26日

`LLM应用` `网络安全` `网络流量分析`

> XG-NID: Dual-Modality Network Intrusion Detection using a Heterogeneous Graph Neural Network and Large Language Model

# 摘要

> 在快速发展的网络安全领域，实时入侵检测中流级与包级信息的整合仍是一个研究空白。本文推出的“XG-NID”框架，据我们所知，是首个在异构图结构中融合这两类数据的创新尝试，为网络流量分析提供了全面视角。通过结合图级分类的异构图神经网络（GNN），XG-NID不仅实现了实时推理，还精准捕捉了流与包数据间的复杂关联。与依赖历史数据的传统GNN方法不同，XG-NID专为应对网络流量的异构性设计，构建了强有力的实时防御体系。此外，该框架还整合了大型语言模型（LLM），生成详尽且易懂的解释，并提出补救建议，确保输出见解既实用又易于理解。我们还引入了基于时间的新流特征，进一步提升了模型的上下文感知和解释能力。为便于实际应用，我们开发了开源工具“GNN4ID”，能将原始网络流量转换为提议的异构图结构，无缝整合流与包级数据。经全面定量比较，XG-NID在多类分类中以97%的F1分数领先，超越了现有基线和最先进方法，为网络入侵检测系统树立了新标杆，实现了数据融合、可解释性与实时性的全面提升。

> In the rapidly evolving field of cybersecurity, the integration of flow-level and packet-level information for real-time intrusion detection remains a largely untapped area of research. This paper introduces "XG-NID," a novel framework that, to the best of our knowledge, is the first to fuse flow-level and packet-level data within a heterogeneous graph structure, offering a comprehensive analysis of network traffic. Leveraging a heterogeneous graph neural network (GNN) with graph-level classification, XG-NID uniquely enables real-time inference while effectively capturing the intricate relationships between flow and packet payload data. Unlike traditional GNN-based methodologies that predominantly analyze historical data, XG-NID is designed to accommodate the heterogeneous nature of network traffic, providing a robust and real-time defense mechanism. Our framework extends beyond mere classification; it integrates Large Language Models (LLMs) to generate detailed, human-readable explanations and suggest potential remedial actions, ensuring that the insights produced are both actionable and comprehensible. Additionally, we introduce a new set of flow features based on temporal information, further enhancing the contextual and explainable inferences provided by our model. To facilitate practical application and accessibility, we developed "GNN4ID," an open-source tool that enables the extraction and transformation of raw network traffic into the proposed heterogeneous graph structure, seamlessly integrating flow and packet-level data. Our comprehensive quantitative comparative analysis demonstrates that XG-NID achieves an F1 score of 97\% in multi-class classification, outperforming existing baseline and state-of-the-art methods. This sets a new standard in Network Intrusion Detection Systems by combining innovative data fusion with enhanced interpretability and real-time capabilities.

[Arxiv](https://arxiv.org/abs/2408.16021)