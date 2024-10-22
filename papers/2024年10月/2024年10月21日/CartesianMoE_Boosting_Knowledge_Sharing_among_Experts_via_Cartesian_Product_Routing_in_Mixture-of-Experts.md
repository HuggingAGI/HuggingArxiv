# CartesianMoE：通过专家混合模型中的笛卡尔积路由，增强专家间的知识共享

发布时间：2024年10月21日

`LLM理论` `人工智能`

> CartesianMoE: Boosting Knowledge Sharing among Experts via Cartesian Product Routing in Mixture-of-Experts

# 摘要

> 近期，大型语言模型（LLM）因其卓越的下游任务表现备受瞩目。然而，扩展这些模型虽能提升性能，却也大幅增加了计算负担。Mixture-of-Experts（MoE）模型通过在不显著增加成本的情况下扩大模型规模，解决了这一难题。但MoE在专家间知识共享上存在挑战，使其性能对路由精度颇为敏感。为此，过往研究通过引入共享专家，以“加法”方式整合输出。本文受集体矩阵分解启发，提出CartesianMoE，以“乘法”方式更高效地实现专家间知识共享。实验证明，CartesianMoE在困惑度和下游任务性能上均超越了以往MoE模型，并展现出更强的路由鲁棒性。

> Large language models (LLM) have been attracting much attention from the community recently, due to their remarkable performance in all kinds of downstream tasks. According to the well-known scaling law, scaling up a dense LLM enhances its capabilities, but also significantly increases the computational complexity. Mixture-of-Experts (MoE) models address that by allowing the model size to grow without substantially raising training or inference costs. Yet MoE models face challenges regarding knowledge sharing among experts, making their performance somehow sensitive to routing accuracy. To tackle that, previous works introduced shared experts and combined their outputs with those of the top $K$ routed experts in an ``addition'' manner. In this paper, inspired by collective matrix factorization to learn shared knowledge among data, we propose CartesianMoE, which implements more effective knowledge sharing among experts in more like a ``multiplication'' manner. Extensive experimental results indicate that CartesianMoE outperforms previous MoE models for building LLMs, in terms of both perplexity and downstream task performance. And we also find that CartesianMoE achieves better expert routing robustness.

[Arxiv](https://arxiv.org/abs/2410.16077)