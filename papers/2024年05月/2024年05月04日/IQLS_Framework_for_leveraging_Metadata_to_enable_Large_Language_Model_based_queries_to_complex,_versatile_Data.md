# IQLS：元数据驱动框架，赋能大型语言模型，轻松驾驭复杂多变的数据查询

发布时间：2024年05月04日

`Agent

这篇论文主要描述了一个智能查询和学习系统（IQLS），该系统通过自然语言处理技术简化了数据检索过程，并为大型语言模型支持的智能代理提供了一个操作环境。这个智能代理能够通过上下文感知的决策来迭代过滤数据，并完成用户查询的任务。因此，这篇论文更符合Agent分类，因为它主要关注的是一个智能代理系统的设计和应用。` `数据检索`

> IQLS: Framework for leveraging Metadata to enable Large Language Model based queries to complex, versatile Data

# 摘要

> 随着数据量和复杂性的激增，数据检索变得愈发困难，需要更多的知识和资源。特别是在物流行业，新技术的应用带来了海量的实时互联数据。智能查询和学习系统（IQLS）通过自然语言的使用，简化了数据检索过程，将结构化数据映射到基于元数据和数据模型的框架中。这一框架为大型语言模型支持的智能代理提供了一个操作环境，该代理通过多次小规模的上下文感知决策，而非一次性检索，来迭代过滤数据。数据过滤后，IQLS通过各种接口，如多模式运输信息检索和多约束下的路线规划，帮助代理完成用户查询的任务。在这些接口中，代理能够根据查询参数定义一个动态对象，代表一个能够导航道路网络的驾驶员。道路网络被视为具有属性的图，通过改进的Dijkstra算法，可以在给定约束下找到最佳路线。在整个过程中，用户可以持续与系统互动并指导其操作。IQLS在加拿大物流领域的案例研究中得到了展示，使得地理空间、视觉、表格和文本数据能够通过自然语言进行语义上的轻松查询。

> As the amount and complexity of data grows, retrieving it has become a more difficult task that requires greater knowledge and resources. This is especially true for the logistics industry, where new technologies for data collection provide tremendous amounts of interconnected real-time data. The Intelligent Query and Learning System (IQLS) simplifies the process by allowing natural language use to simplify data retrieval . It maps structured data into a framework based on the available metadata and available data models. This framework creates an environment for an agent powered by a Large Language Model. The agent utilizes the hierarchical nature of the data to filter iteratively by making multiple small context-aware decisions instead of one-shot data retrieval. After the Data filtering, the IQLS enables the agent to fulfill tasks given by the user query through interfaces. These interfaces range from multimodal transportation information retrieval to route planning under multiple constraints. The latter lets the agent define a dynamic object, which is determined based on the query parameters. This object represents a driver capable of navigating a road network. The road network is depicted as a graph with attributes based on the data. Using a modified version of the Dijkstra algorithm, the optimal route under the given constraints can be determined. Throughout the entire process, the user maintains the ability to interact and guide the system. The IQLS is showcased in a case study on the Canadian logistics sector, allowing geospatial, visual, tabular and text data to be easily queried semantically in natural language.

[Arxiv](https://arxiv.org/abs/2405.15792)