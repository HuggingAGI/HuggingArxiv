# 通过协同 LLM 智能体与知识图谱来实现 LBSN 中的社会经济预测

发布时间：2024年10月29日

`LLM应用` `社会经济` `位置服务`

> Synergizing LLM Agents and Knowledge Graph for Socioeconomic Prediction in LBSN

# 摘要

> 基于位置的社交网络（LBSNs）发展迅速，给社会带来显著变化，使得利用 LBSN 数据进行社会经济预测（如区域人口和商业活动预估）的研究颇受欢迎。现有的研究设计了各类图形来对异构的 LBSN 数据建模，并进一步运用图表示学习方法做社会经济预测。然而，这些方法高度依赖启发式思路和专业知识从各类数据中提取任务相关知识，对特定任务而言或许并非最优选择。另外，它们常常忽视不同指标间的内在联系，限制了预测的精准度。受大型语言模型（LLMs）在常识推理、嵌入和多智能体协作方面出色能力的启发，在本项工作中，我们将 LLM 智能体与知识图协同用于社会经济预测。我们先是构建一个基于位置的知识图（LBKG）来整合多源 LBSN 数据。接着，借助 LLM 智能体的推理能力，为每种社会经济预测任务在 LBKG 中识别相关元路径，并设计语义引导的注意力模块用于与元路径的知识融合。此外，引入跨任务通信机制，通过在 LLM 智能体和 KG 层面实现跨任务知识共享来进一步提升性能。一方面，不同任务的 LLM 智能体协作生成更丰富全面的元路径；另一方面，将不同任务的嵌入自适应合并，以实现更优的社会经济预测。在两个数据集上的实验表明 LLM 与 KG 协同设计的有效性，为社会经济预测任务间的信息共享提供了思路。

> The fast development of location-based social networks (LBSNs) has led to significant changes in society, resulting in popular studies of using LBSN data for socioeconomic prediction, e.g., regional population and commercial activity estimation. Existing studies design various graphs to model heterogeneous LBSN data, and further apply graph representation learning methods for socioeconomic prediction. However, these approaches heavily rely on heuristic ideas and expertise to extract task-relevant knowledge from diverse data, which may not be optimal for specific tasks. Additionally, they tend to overlook the inherent relationships between different indicators, limiting the prediction accuracy. Motivated by the remarkable abilities of large language models (LLMs) in commonsense reasoning, embedding, and multi-agent collaboration, in this work, we synergize LLM agents and knowledge graph for socioeconomic prediction. We first construct a location-based knowledge graph (LBKG) to integrate multi-sourced LBSN data. Then we leverage the reasoning power of LLM agent to identify relevant meta-paths in the LBKG for each type of socioeconomic prediction task, and design a semantic-guided attention module for knowledge fusion with meta-paths. Moreover, we introduce a cross-task communication mechanism to further enhance performance by enabling knowledge sharing across tasks at both LLM agent and KG levels. On the one hand, the LLM agents for different tasks collaborate to generate more diverse and comprehensive meta-paths. On the other hand, the embeddings from different tasks are adaptively merged for better socioeconomic prediction. Experiments on two datasets demonstrate the effectiveness of the synergistic design between LLM and KG, providing insights for information sharing across socioeconomic prediction tasks.

[Arxiv](https://arxiv.org/abs/2411.00028)