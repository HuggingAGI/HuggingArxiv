# QARM：快手的定量对齐式多模态推荐

发布时间：2024年11月18日

`LLM应用` `多模态`

> QARM: Quantitative Alignment Multi-Modal Recommendation at Kuaishou

# 摘要

> 近年来，随着多模态大模型的显著演进，众多推荐领域的研究者都察觉到了多模态信息在用户兴趣建模方面的巨大潜力。在业界，一种被广泛采用的建模架构是级联范式：（1）先预训练一个多模态模型，为下游服务提供全能型的表示；（2）下游的推荐模型把多模态表示当作额外输入，以契合真实的用户-项目行为。虽然这种范式成效显著，但是仍有两个问题制约着模型性能：（1）表示不匹配：预训练的多模态模型通常由经典的 NLP/CV 任务监管，而推荐模型则由真实的用户-项目交互监管。如此一来，这两种截然不同的任务目标相互分离，其表示缺乏一致性；（2）表示未学习：生成的多模态表示往往存储在缓存中，作为推荐模型的额外固定输入，无法通过推荐模型的梯度进行更新，对下游训练不利。受这两个下游任务使用中的难题挑战所启发，我们引入了一个量化的多模态框架，为不同的下游模型定制专门且可训练的多模态信息。

> In recent years, with the significant evolution of multi-modal large models, many recommender researchers realized the potential of multi-modal information for user interest modeling. In industry, a wide-used modeling architecture is a cascading paradigm: (1) first pre-training a multi-modal model to provide omnipotent representations for downstream services; (2) The downstream recommendation model takes the multi-modal representation as additional input to fit real user-item behaviours. Although such paradigm achieves remarkable improvements, however, there still exist two problems that limit model performance: (1) Representation Unmatching: The pre-trained multi-modal model is always supervised by the classic NLP/CV tasks, while the recommendation models are supervised by real user-item interaction. As a result, the two fundamentally different tasks' goals were relatively separate, and there was a lack of consistent objective on their representations; (2) Representation Unlearning: The generated multi-modal representations are always stored in cache store and serve as extra fixed input of recommendation model, thus could not be updated by recommendation model gradient, further unfriendly for downstream training. Inspired by the two difficulties challenges in downstream tasks usage, we introduce a quantitative multi-modal framework to customize the specialized and trainable multi-modal information for different downstream models.

[Arxiv](https://arxiv.org/abs/2411.11739)