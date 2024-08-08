# 借助变异理论，通过反事实数据增强优化主动学习过程

发布时间：2024年08月07日

`LLM应用` `人工智能`

> Leveraging Variation Theory in Counterfactual Data Augmentation for Optimized Active Learning

# 摘要

> 主动学习 (AL) 使模型能够从用户反馈中进行互动学习。本文提出了一种基于反事实数据增强的 AL 方法，专注于用户查询数据点的选择，这是提升数据效率的关键。受变异理论启发，我们通过神经符号流水线结合 LLM 和规则模型，合成强调标签间潜在关键相似性和差异的人工数据点，而非仅依赖现有数据点。实验表明，在标注数据稀缺时，我们的方法性能显著提升，且随着数据量增加，生成数据的影响减弱，有效应对 AL 的冷启动问题。这项研究探索了将人类学习理论融入 AL 优化的可能性。

> Active Learning (AL) allows models to learn interactively from user feedback. This paper introduces a counterfactual data augmentation approach to AL, particularly addressing the selection of datapoints for user querying, a pivotal concern in enhancing data efficiency. Our approach is inspired by Variation Theory, a theory of human concept learning that emphasizes the essential features of a concept by focusing on what stays the same and what changes. Instead of just querying with existing datapoints, our approach synthesizes artificial datapoints that highlight potential key similarities and differences among labels using a neuro-symbolic pipeline combining large language models (LLMs) and rule-based models. Through an experiment in the example domain of text classification, we show that our approach achieves significantly higher performance when there are fewer annotated data. As the annotated training data gets larger the impact of the generated data starts to diminish showing its capability to address the cold start problem in AL. This research sheds light on integrating theories of human learning into the optimization of AL.

[Arxiv](https://arxiv.org/abs/2408.03819)