# 结合大数据与大型语言模型，本体论驱动的森林火灾管理决策支持系统

发布时间：2024年05月18日

`Agent

理由：这篇论文主要探讨了如何利用Apache Spark进行早期森林火灾检测，并结合气象与地理数据提升火灾风险预测。它涉及了开发一个决策支持系统，该系统基于LLMs（大型语言模型）和Spark框架，并通过实时数据流处理来实现针对多种火灾场景的实时警报。这个系统可以被视为一个智能Agent，因为它能够处理环境数据（如气象数据），并基于这些数据做出决策（如火灾风险预测和警报）。因此，这篇论文更符合Agent分类，而不是RAG、LLM应用或LLM理论。` `森林火灾管理` `环境监测`

> Decision support system for Forest fire management using Ontology with Big Data and LLMs

# 摘要

> 森林是生态平衡的关键，但野火——森林损失的主因——带来了巨大风险。火灾天气指数，这一评估野火风险并预测资源需求的工具，显得尤为重要。随着传感器网络在医疗和环境监测领域的应用日益广泛，语义传感器网络正被用来收集风速、温度和湿度等气候数据。然而，如何处理这些数据流以确定火灾天气指数，仍是一大挑战，凸显了有效森林火灾检测的紧迫性。本文探讨了利用Apache Spark进行早期森林火灾检测，并结合气象与地理数据提升火灾风险预测。基于我们在Monesterial自然公园森林火灾管理中开发的SSN本体论和SWRL，我们扩展了SWRL，以改进基于LLMs和Spark框架的决策支持系统。我们通过Spark流实现了针对多种火灾场景的实时警报，并通过本体论指标、查询评估、LLMs精度评分、F1分数和召回率等手段验证了我们的方法。

> Forests are crucial for ecological balance, but wildfires, a major cause of forest loss, pose significant risks. Fire weather indices, which assess wildfire risk and predict resource demands, are vital. With the rise of sensor networks in fields like healthcare and environmental monitoring, semantic sensor networks are increasingly used to gather climatic data such as wind speed, temperature, and humidity. However, processing these data streams to determine fire weather indices presents challenges, underscoring the growing importance of effective forest fire detection. This paper discusses using Apache Spark for early forest fire detection, enhancing fire risk prediction with meteorological and geographical data. Building on our previous development of Semantic Sensor Network (SSN) ontologies and Semantic Web Rules Language (SWRL) for managing forest fires in Monesterial Natural Park, we expanded SWRL to improve a Decision Support System (DSS) using a Large Language Models (LLMs) and Spark framework. We implemented real-time alerts with Spark streaming, tailored to various fire scenarios, and validated our approach using ontology metrics, query-based evaluations, LLMs score precision, F1 score, and recall measures.

[Arxiv](https://arxiv.org/abs/2405.11346)