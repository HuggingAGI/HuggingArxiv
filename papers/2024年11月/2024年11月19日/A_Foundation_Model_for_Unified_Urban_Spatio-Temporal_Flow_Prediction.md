# 一个用于统一城市时空流预测的基础模型

发布时间：2024年11月19日

`其他` `城市规划`

> A Foundation Model for Unified Urban Spatio-Temporal Flow Prediction

# 摘要

> 城市的时空流预测，涵盖交通流和人群流，对于优化城市基础设施、管理交通及应对紧急情况意义重大。传统方法依靠的是针对基于网格的数据（把城市视作均匀的单元格）或基于图的数据（将城市建模为节点和边组成的网络）定制的单独模型。在本文中，我们构建了 UniFlow，这是用于一般城市流预测的基础模型，统一了基于网格和基于图的数据。我们先是设计了一种多视图时空修补机制，把不同数据规范为统一的顺序格式，接着引入时空转换器架构，以捕捉复杂的相关性和动态。为利用不同数据类型间共享的时空模式并推动有效的交叉学习，我们提出了时空记忆检索增强（ST-MRA）。通过创建结构化的记忆模块来存储共享的时空模式，ST-MRA 借助自适应记忆检索来增强预测。大量实验表明，UniFlow 在基于网格和基于图的流预测中都胜过现有模型，在数据有限的场景下表现尤为出色，彰显出其卓越的性能和广泛的适用性。数据集和代码实现已在 https://github.com/YuanYuan98/UniFlow 发布。

> Urban spatio-temporal flow prediction, encompassing traffic flows and crowd flows, is crucial for optimizing city infrastructure and managing traffic and emergency responses. Traditional approaches have relied on separate models tailored to either grid-based data, representing cities as uniform cells, or graph-based data, modeling cities as networks of nodes and edges. In this paper, we build UniFlow, a foundational model for general urban flow prediction that unifies both grid-based and graphbased data. We first design a multi-view spatio-temporal patching mechanism to standardize different data into a consistent sequential format and then introduce a spatio-temporal transformer architecture to capture complex correlations and dynamics. To leverage shared spatio-temporal patterns across different data types and facilitate effective cross-learning, we propose SpatioTemporal Memory Retrieval Augmentation (ST-MRA). By creating structured memory modules to store shared spatio-temporal patterns, ST-MRA enhances predictions through adaptive memory retrieval. Extensive experiments demonstrate that UniFlow outperforms existing models in both grid-based and graph-based flow prediction, excelling particularly in scenarios with limited data availability, showcasing its superior performance and broad applicability. The datasets and code implementation have been released on https://github.com/YuanYuan98/UniFlow.

[Arxiv](https://arxiv.org/abs/2411.12972)