# IQLS框架：借助元数据，让大型语言模型轻松驾驭复杂多变的数据查询

发布时间：2024年05月04日

`Agent

理由：这篇论文主要描述了一个智能查询与学习系统（IQLS），该系统通过自然语言处理技术简化了数据检索过程，并为大型语言模型支持的智能代理提供了一个操作环境。代理在这个环境中通过上下文感知的决策进行数据过滤，并能够完成用户查询指定的任务，如路线规划等。这个系统强调了代理在处理复杂数据检索任务中的作用，因此更适合归类为Agent。` `数据检索`

> IQLS: Framework for leveraging Metadata to enable Large Language Model based queries to complex, versatile Data

# 摘要

> 随着数据量与复杂性的激增，数据检索变得愈发困难，需要更多的知识和资源。特别是在物流行业，新技术收集的大量实时互联数据使得这一挑战更为突出。智能查询与学习系统（IQLS）通过自然语言的使用，简化了数据检索过程，将结构化数据映射到基于元数据和数据模型的框架中。这一框架为大型语言模型支持的智能代理提供了一个操作环境。代理利用数据的层次结构，通过一系列上下文感知的微小决策进行迭代过滤，而非一次性检索。经过数据过滤，IQLS 使代理能够通过各种接口完成用户查询指定的任务，从多模式运输信息检索到多重约束下的路线规划。后者允许代理根据查询参数定义一个动态对象，代表一个能够导航道路网络的驾驶员。道路网络以基于数据的属性图形式呈现。通过改进的 Dijkstra 算法，可在给定约束下确定最佳路线。在整个过程中，用户始终能够与系统互动并指导其操作。IQLS 在加拿大物流领域的案例研究中展示了其能力，使得地理空间、视觉、表格和文本数据能够通过自然语言轻松进行语义查询。

> As the amount and complexity of data grows, retrieving it has become a more difficult task that requires greater knowledge and resources. This is especially true for the logistics industry, where new technologies for data collection provide tremendous amounts of interconnected real-time data. The Intelligent Query and Learning System (IQLS) simplifies the process by allowing natural language use to simplify data retrieval . It maps structured data into a framework based on the available metadata and available data models. This framework creates an environment for an agent powered by a Large Language Model. The agent utilizes the hierarchical nature of the data to filter iteratively by making multiple small context-aware decisions instead of one-shot data retrieval. After the Data filtering, the IQLS enables the agent to fulfill tasks given by the user query through interfaces. These interfaces range from multimodal transportation information retrieval to route planning under multiple constraints. The latter lets the agent define a dynamic object, which is determined based on the query parameters. This object represents a driver capable of navigating a road network. The road network is depicted as a graph with attributes based on the data. Using a modified version of the Dijkstra algorithm, the optimal route under the given constraints can be determined. Throughout the entire process, the user maintains the ability to interact and guide the system. The IQLS is showcased in a case study on the Canadian logistics sector, allowing geospatial, visual, tabular and text data to be easily queried semantically in natural language.

[Arxiv](https://arxiv.org/abs/2405.15792)