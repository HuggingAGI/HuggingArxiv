# 基于专家混合模型的融合策略，助力高效逼近帕累托集

发布时间：2024年06月14日

`LLM理论

理由：这篇论文主要探讨了大型深度神经网络的多目标优化问题，并提出了一种基于专家混合（MoE）的模型融合方法来近似大型神经网络的Pareto前沿。这种方法涉及对大型模型的理论分析和优化，属于对大型语言模型（LLM）的理论研究，因此归类为LLM理论。论文中虽然提到了CLIP-ViT和GPT-2等具体模型，但其核心贡献在于提出和验证了一种新的优化方法，而不是直接应用于特定的LLM应用场景，因此不适合归类为LLM应用。同时，论文内容与Agent或RAG的概念不直接相关，因此也不归类为Agent或RAG。` `多任务学习`

> Towards Efficient Pareto Set Approximation via Mixture of Experts Based Model Fusion

# 摘要

> 解决大型深度神经网络的多目标优化问题充满挑战，主要是因为损失景观的复杂性和高昂的计算成本。通过近似大型模型的Pareto前沿，我们能够进行多任务学习和权衡分析。现有的Pareto集学习算法，如进化算法和标量化算法，要么计算成本高，要么无法有效捕捉目标间的权衡。受模型合并技术的启发，我们提出了一种基于专家混合（MoE）的模型融合方法，该方法既实用又可扩展。我们的MoE模块通过组合专业模型的权重，有效捕捉了多目标间的权衡，并近似了大型神经网络的整个Pareto集。在推理阶段，MoE模块无需额外计算成本。我们在CLIP-ViT和GPT-2等大型模型上进行的实验表明，我们的方法能高效近似整个Pareto前沿，且在内存使用和可扩展性方面优于其他算法。

> Solving multi-objective optimization problems for large deep neural networks is a challenging task due to the complexity of the loss landscape and the expensive computational cost of training and evaluating models. Efficient Pareto front approximation of large models enables multi-objective optimization for various tasks such as multi-task learning and trade-off analysis. Existing algorithms for learning Pareto set, including (1) evolutionary, hypernetworks, and hypervolume-maximization methods, are computationally expensive and have restricted scalability to large models; (2) Scalarization algorithms, where a separate model is trained for each objective ray, which is inefficient for learning the entire Pareto set and fails to capture the objective trade-offs effectively. Inspired by the recent success of model merging, we propose a practical and scalable approach to Pareto set learning problem via mixture of experts (MoE) based model fusion. By ensembling the weights of specialized single-task models, the MoE module can effectively capture the trade-offs between multiple objectives and closely approximate the entire Pareto set of large neural networks. Once the routers are learned and a preference vector is set, the MoE module can be unloaded, thus no additional computational cost is introduced during inference. We conduct extensive experiments on vision and language tasks using large-scale models such as CLIP-ViT and GPT-2. The experimental results demonstrate that our method efficiently approximates the entire Pareto front of large models. Using only hundreds of trainable parameters of the MoE routers, our method even has lower memory usage compared to linear scalarization and algorithms that learn a single Pareto optimal solution, and are scalable to both the number of objectives and the size of the model.

![基于专家混合模型的融合策略，助力高效逼近帕累托集](../../../paper_images/2406.09770/x1.png)

![基于专家混合模型的融合策略，助力高效逼近帕累托集](../../../paper_images/2406.09770/x2.png)

![基于专家混合模型的融合策略，助力高效逼近帕累托集](../../../paper_images/2406.09770/x3.png)

![基于专家混合模型的融合策略，助力高效逼近帕累托集](../../../paper_images/2406.09770/x4.png)

![基于专家混合模型的融合策略，助力高效逼近帕累托集](../../../paper_images/2406.09770/x5.png)

![基于专家混合模型的融合策略，助力高效逼近帕累托集](../../../paper_images/2406.09770/x6.png)

![基于专家混合模型的融合策略，助力高效逼近帕累托集](../../../paper_images/2406.09770/x7.png)

![基于专家混合模型的融合策略，助力高效逼近帕累托集](../../../paper_images/2406.09770/x8.png)

![基于专家混合模型的融合策略，助力高效逼近帕累托集](../../../paper_images/2406.09770/x9.png)

[Arxiv](https://arxiv.org/abs/2406.09770)