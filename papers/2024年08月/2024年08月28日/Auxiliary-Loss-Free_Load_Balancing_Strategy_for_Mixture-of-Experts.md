# 无辅助损失的专家混合负载均衡策略

发布时间：2024年08月28日

`LLM理论` `人工智能` `机器学习`

> Auxiliary-Loss-Free Load Balancing Strategy for Mixture-of-Experts

# 摘要

> 在Mixture-of-Experts（MoE）模型中，专家负载不平衡可能导致路由崩溃或计算开销增加。传统方法通过辅助损失来促进负载平衡，但过大的辅助损失会干扰训练，影响模型性能。为此，我们提出了一种无辅助损失的负载平衡策略——无损失平衡。该策略在top-K路由决策前，对每个专家的路由分数施加动态更新的专家级偏差，从而确保专家负载的均衡分布。由于不产生干扰梯度，无损失平衡不仅提升了模型性能的上限，还在实验中展现了优于传统策略的性能和负载平衡效果。我们在高达3B参数的MoE模型上进行了验证，这些模型在多达200B令牌上训练，实验结果证实了无损失平衡的优势。

> For Mixture-of-Experts (MoE) models, an unbalanced expert load will lead to routing collapse or increased computational overhead. Existing methods commonly employ an auxiliary loss to encourage load balance, but a large auxiliary loss will introduce non-negligible interference gradients into training and thus impair the model performance. In order to control load balance while not producing undesired gradients during training, we propose Loss-Free Balancing, featured by an auxiliary-loss-free load balancing strategy. To be specific, before the top-K routing decision, Loss-Free Balancing will first apply an expert-wise bias to the routing scores of each expert. By dynamically updating the bias of each expert according to its recent load, Loss-Free Balancing can consistently maintain a balanced distribution of expert load. In addition, since Loss-Free Balancing does not produce any interference gradients, it also elevates the upper bound of model performance gained from MoE training. We validate the performance of Loss-Free Balancing on MoE models with up to 3B parameters trained on up to 200B tokens. Experimental results show that Loss-Free Balancing achieves both better performance and better load balance compared with traditional auxiliary-loss-controlled load balancing strategies.

[Arxiv](https://arxiv.org/abs/2408.15664)