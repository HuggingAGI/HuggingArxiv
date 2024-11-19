# 用于网络物理系统异常检测的 LLM 辅助物理不变量提取

发布时间：2024年11月16日

`RAG` `网络安全`

> LLM-assisted Physical Invariant Extraction for Cyber-Physical Systems Anomaly Detection

# 摘要

> 现代工业基础设施高度依赖信息物理系统（CPS），但此类系统易受网络攻击，可能引发灾难性后果。为降低风险，基于物理不变量的异常检测方法应运而生。然而，这些方法往往需要特定领域的专业知识来人工定义不变量，导致成本高且难以拓展。为突破这一限制，我们提出一种从 CPS 测试平台提取物理不变量以用于异常检测的新方法。我们发现，CPS 设计文档通常包含物理过程的语义丰富描述，能够勾勒出系统组件间的相互关联动态。借助最新生成式 AI 模型的内置物理和工程知识，我们致力于将这一传统的人工过程自动化，提升可扩展性并降低成本。此项工作重点在于针对 CPS 文档设计并优化一个配备定制提示系统的检索增强生成（RAG）工作流，从而能从复杂的多模态内容中精准提取语义信息并推断物理不变量。随后，我们并非直接将推断出的不变量用于异常检测，而是引入一种创新的基于统计的学习方法，将这些不变量融入训练数据集。该方法解决了诸如幻觉和概念漂移等问题，增强了模型的可靠性。我们在包含 86 个数据点和 58 个攻击案例的真实公共 CPS 安全数据集上对我们的方法进行了评估。结果显示，我们的方法达到了 0.923 的高精度，能准确检测异常，同时将误报降至最低。

> Modern industrial infrastructures rely heavily on Cyber-Physical Systems (CPS), but these are vulnerable to cyber-attacks with potentially catastrophic effects. To reduce these risks, anomaly detection methods based on physical invariants have been developed. However, these methods often require domain-specific expertise to manually define invariants, making them costly and difficult to scale. To address this limitation, we propose a novel approach to extract physical invariants from CPS testbeds for anomaly detection. Our insight is that CPS design documentation often contains semantically rich descriptions of physical procedures, which can profile inter-correlated dynamics among system components. Leveraging the built-in physics and engineering knowledge of recent generative AI models, we aim to automate this traditionally manual process, improving scalability and reducing costs. This work focuses on designing and optimizing a Retrieval-Augmented-Generation (RAG) workflow with a customized prompting system tailored for CPS documentation, enabling accurate extraction of semantic information and inference of physical invariants from complex, multimodal content. Then, rather than directly applying the inferred invariants for anomaly detection, we introduce an innovative statistics-based learning approach that integrates these invariants into the training dataset. This method addresses limitations such as hallucination and concept drift, enhancing the reliability of the model. We evaluate our approach on real-world public CPS security dataset which contains 86 data points and 58 attacking cases. The results show that our approach achieves a high precision of 0.923, accurately detecting anomalies while minimizing false alarms.

[Arxiv](https://arxiv.org/abs/2411.10918)