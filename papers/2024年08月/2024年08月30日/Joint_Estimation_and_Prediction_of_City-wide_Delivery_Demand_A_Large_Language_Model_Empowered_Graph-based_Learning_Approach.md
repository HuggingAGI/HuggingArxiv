# 本研究提出了一种基于大型语言模型的图学习方法，用于联合估计和预测城市范围内的配送需求。

发布时间：2024年08月30日

`LLM应用` `电子商务`

> Joint Estimation and Prediction of City-wide Delivery Demand: A Large Language Model Empowered Graph-based Learning Approach

# 摘要

> 随着电子商务和城市化的蓬勃发展，城市配送操作面临前所未有的挑战，配送需求的数量和复杂性急剧上升。为此，我们采用数据驱动的预测方法，特别是机器学习技术，来应对这一挑战。我们特别关注城市范围内配送需求的联合估计和预测，这一问题尚未得到充分研究。我们将此问题转化为一个基于图的空间时间学习任务，通过构建消息传递神经网络模型来捕捉区域间需求模式的交互。同时，我们利用大型语言模型的最新技术，从非结构化位置数据中提取地理空间知识，并融入需求预测模型。此外，我们设计了一个端到端的归纳训练方案，以提升模型的跨城市应用能力。实证研究表明，我们的模型在处理复杂配送任务时，显著超越了现有技术水平。

> The proliferation of e-commerce and urbanization has significantly intensified delivery operations in urban areas, boosting the volume and complexity of delivery demand. Data-driven predictive methods, especially those utilizing machine learning techniques, have emerged to handle these complexities in urban delivery demand management problems. One particularly pressing problem that has not yet been sufficiently studied is the joint estimation and prediction of city-wide delivery demand. To this end, we formulate this problem as a graph-based spatiotemporal learning task. First, a message-passing neural network model is formalized to capture the interaction between demand patterns of associated regions. Second, by exploiting recent advances in large language models, we extract general geospatial knowledge encodings from the unstructured locational data and integrate them into the demand predictor. Last, to encourage the cross-city transferability of the model, an inductive training scheme is developed in an end-to-end routine. Extensive empirical results on two real-world delivery datasets, including eight cities in China and the US, demonstrate that our model significantly outperforms state-of-the-art baselines in these challenging tasks.

[Arxiv](https://arxiv.org/abs/2408.17258)