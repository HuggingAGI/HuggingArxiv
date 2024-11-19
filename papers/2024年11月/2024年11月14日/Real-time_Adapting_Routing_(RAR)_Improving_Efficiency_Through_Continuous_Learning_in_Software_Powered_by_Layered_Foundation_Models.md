# 实时自适应路由（RAR）：借助分层基础模型驱动的软件中的持续学习来提升效率

发布时间：2024年11月14日

`LLM应用` `模型评估`

> Real-time Adapting Routing (RAR): Improving Efficiency Through Continuous Learning in Software Powered by Layered Foundation Models

# 摘要

> 为平衡基础模型（如大型语言模型（LLMs））驱动的软件的质量与推理成本，人们常选择训练一个路由模型，把请求导向不同规模和能力的 FMs。现有的路由模型依靠从精心整理的数据中学习最优路由决策，更新时需要复杂计算，且未考虑较弱 FMs 的潜在演进。本文中，我们提出实时自适应路由（RAR），这是一种在运用引导式上下文学习增强较弱 FM 能力的同时，持续适配 FM 路由决策的方法，旨在降低对更强、更昂贵 FMs 的依赖。我们在热门的 MMLU 基准的不同子集上对该方法进行评估。久而久之，我们的方法向计算成本高的模型发送的请求减少了 50.2%，同时保持了约 90.5%的总体响应质量。另外，较强模型生成的指南展现出域内泛化，相比具有独立较弱 FM 的同等方法，带来了更优的响应质量。

> To balance the quality and inference cost of a Foundation Model (FM, such as large language models (LLMs)) powered software, people often opt to train a routing model that routes requests to FMs with different sizes and capabilities. Existing routing models rely on learning the optimal routing decision from carefully curated data, require complex computations to be updated, and do not consider the potential evolution of weaker FMs. In this paper, we propose Real-time Adaptive Routing (RAR), an approach to continuously adapt FM routing decisions while using guided in-context learning to enhance the capabilities of weaker FM. The goal is to reduce reliance on stronger, more expensive FMs. We evaluate our approach on different subsets of the popular MMLU benchmark. Over time, our approach routes 50.2% fewer requests to computationally expensive models while maintaining around 90.5% of the general response quality. In addition, the guides generated from stronger models have shown intra-domain generalization and led to a better quality of responses compared to an equivalent approach with a standalone weaker FM.

[Arxiv](https://arxiv.org/abs/2411.09837)