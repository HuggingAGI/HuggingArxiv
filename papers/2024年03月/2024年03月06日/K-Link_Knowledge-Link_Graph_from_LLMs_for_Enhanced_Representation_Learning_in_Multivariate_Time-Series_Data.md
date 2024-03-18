# K-Link 方法通过从大型语言模型（LLMs）中提炼出知识链接图，旨在提升多元时间序列数据的表征学习效果。

发布时间：2024年03月06日

`LLM应用`

> K-Link: Knowledge-Link Graph from LLMs for Enhanced Representation Learning in Multivariate Time-Series Data

> 面对多变量时间序列（MTS）数据中蕴含的重要时空关联，诸如传感器间的相互依赖，尽管图神经网络（GNNs）展现出了强大的建模能力，但其性能受限于基于 MTS 数据构建的图结构质量。传统方法仅根据 MTS 信号搭建图形，易受小规模训练数据影响产生偏见且难以精准反映深层次依赖关系。为此，我们创新性地引入名为 K-Link 的框架，借助大型语言模型（LLMs）整合丰富的普适知识来减轻此类偏见问题。通过汲取 LLMS 潜藏的物理规律等知识内涵，我们构建了“知识链接图”，它能捕获传感器间丰富的语义联系和传感器层级知识关联。为了将知识链接图的优势融入 MTS 数据衍生出的图形中，我们设计了一个图对齐模块，实现知识链接图内语义知识向 MTS 图形的有效迁移。如此一来，能够提升图形品质，确保 GNNs 在处理 MTS 数据时实现高效表征学习。大量的实验证明，此方法在各类与 MTS 相关的下游任务上均展现出显著优势。

> Sourced from various sensors and organized chronologically, Multivariate Time-Series (MTS) data involves crucial spatial-temporal dependencies, e.g., correlations among sensors. To capture these dependencies, Graph Neural Networks (GNNs) have emerged as powerful tools, yet their effectiveness is restricted by the quality of graph construction from MTS data. Typically, existing approaches construct graphs solely from MTS signals, which may introduce bias due to a small training dataset and may not accurately represent underlying dependencies. To address this challenge, we propose a novel framework named K-Link, leveraging Large Language Models (LLMs) to encode extensive general knowledge and thereby providing effective solutions to reduce the bias. Leveraging the knowledge embedded in LLMs, such as physical principles, we extract a \textit{Knowledge-Link graph}, capturing vast semantic knowledge of sensors and the linkage of the sensor-level knowledge. To harness the potential of the knowledge-link graph in enhancing the graph derived from MTS data, we propose a graph alignment module, facilitating the transfer of semantic knowledge within the knowledge-link graph into the MTS-derived graph. By doing so, we can improve the graph quality, ensuring effective representation learning with GNNs for MTS data. Extensive experiments demonstrate the efficacy of our approach for superior performance across various MTS-related downstream tasks.

[Arxiv](https://arxiv.org/abs/2403.03645)