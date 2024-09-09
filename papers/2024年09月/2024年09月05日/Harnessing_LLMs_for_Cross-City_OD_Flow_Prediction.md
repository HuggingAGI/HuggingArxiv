# 借助 LLM 之力，预测跨城市 OD 流量

发布时间：2024年09月05日

`LLM应用` `城市规划` `交通管理`

> Harnessing LLMs for Cross-City OD Flow Prediction

# 摘要

> 理解和预测起源-目的地 (OD) 流量对城市规划和交通管理至关重要。传统的 OD 预测模型虽然在单一城市内有效，但跨城市应用时，由于交通条件、城市布局和社会经济因素的差异，常常面临局限。本文通过使用大型语言模型 (LLM)，引入了一种新的跨城市 OD 流量预测方法。我们利用 LLM 的高级语义理解和上下文学习能力，弥合了不同城市之间的差距，提供了一个强大且适应性强的解决方案，可以实现从一个城市到另一个城市的准确 OD 流量预测。我们的新框架包括四个主要步骤：从源城市收集 OD 训练数据集，指令调整 LLM，预测目标城市中的目的地 POI，以及识别与预测目的地 POI 最匹配的位置。我们还引入了一种新的损失函数，整合了 POI 语义和行程距离。通过从人类移动和 POI 数据中提取高质量的语义特征，模型能够理解城市空间内的空间和功能关系，并捕捉个人与各种 POI 之间的互动。广泛的实验结果表明，我们的方法在跨城市 OD 流量预测方面优于最先进的基于学习的方法。

> Understanding and predicting Origin-Destination (OD) flows is crucial for urban planning and transportation management. Traditional OD prediction models, while effective within single cities, often face limitations when applied across different cities due to varied traffic conditions, urban layouts, and socio-economic factors. In this paper, by employing Large Language Models (LLMs), we introduce a new method for cross-city OD flow prediction. Our approach leverages the advanced semantic understanding and contextual learning capabilities of LLMs to bridge the gap between cities with different characteristics, providing a robust and adaptable solution for accurate OD flow prediction that can be transferred from one city to another. Our novel framework involves four major components: collecting OD training datasets from a source city, instruction-tuning the LLMs, predicting destination POIs in a target city, and identifying the locations that best match the predicted destination POIs. We introduce a new loss function that integrates POI semantics and trip distance during training. By extracting high-quality semantic features from human mobility and POI data, the model understands spatial and functional relationships within urban spaces and captures interactions between individuals and various POIs. Extensive experimental results demonstrate the superiority of our approach over the state-of-the-art learning-based methods in cross-city OD flow prediction.

[Arxiv](https://arxiv.org/abs/2409.03937)