# 探究大型语言模型在捕捉与理解运动轨迹方面的表现

发布时间：2024年08月30日

`LLM应用` `地理信息系统` `人工智能`

> Evaluating the Effectiveness of Large Language Models in Representing and Understanding Movement Trajectories

# 摘要

> 本研究探索了AI基础模型在表示运动轨迹方面的能力，利用GPT-J对轨迹进行编码，并评估其在数据分析中的有效性。实验显示，尽管GPT-J嵌入能较好地保留轨迹距离，但在数值恢复和空间邻居检索上仍有挑战。同时，LLM在理解轨迹的时空依赖性及位置预测上表现出色。研究指出，未来需进一步优化模型，以更精准地捕捉地理空间数据的复杂性，并结合领域知识，推动GeoAI应用的发展。

> This research focuses on assessing the ability of AI foundation models in representing the trajectories of movements. We utilize one of the large language models (LLMs) (i.e., GPT-J) to encode the string format of trajectories and then evaluate the effectiveness of the LLM-based representation for trajectory data analysis. The experiments demonstrate that while the LLM-based embeddings can preserve certain trajectory distance metrics (i.e., the correlation coefficients exceed 0.74 between the Cosine distance derived from GPT-J embeddings and the Hausdorff and Dynamic Time Warping distances on raw trajectories), challenges remain in restoring numeric values and retrieving spatial neighbors in movement trajectory analytics. In addition, the LLMs can understand the spatiotemporal dependency contained in trajectories and have good accuracy in location prediction tasks. This research highlights the need for improvement in terms of capturing the nuances and complexities of the underlying geospatial data and integrating domain knowledge to support various GeoAI applications using LLMs.

[Arxiv](https://arxiv.org/abs/2409.00335)