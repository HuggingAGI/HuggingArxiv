# 为了提供鲁棒的 Top-k 推荐，我们需对大型语言模型进行既高效又负责任的调整。

发布时间：2024年05月01日

`分类：LLM应用

这篇论文讨论了如何将大型语言模型（LLMs）应用于推荐系统，以提高对特定用户群体的适应性和鲁棒性。它提出了一个混合任务分配框架，结合了LLMs和传统推荐系统的优势，通过智能分配任务，实现LLMs的高效和负责任的应用。这篇论文关注的是LLMs在实际应用中的性能和成本效益，以及如何通过上下文学习和任务分配来提高推荐系统的鲁棒性。因此，它应该被归类为LLM应用。` `推荐系统` `用户行为分析`

> Efficient and Responsible Adaptation of Large Language Models for Robust Top-k Recommendations

# 摘要

> 传统推荐系统往往追求全面提升训练样本的性能指标，却难以满足用户多样性的需求。这种性能差异可能削弱模型对特定用户群体的鲁棒性。尽管最新研究通过大型语言模型（LLMs）在推荐领域的应用取得了进展，但面对数百万用户的长查询，LLMs的性能和成本效益、处理速度及推理延迟仍面临挑战。为此，我们提出了一个混合任务分配框架，整合了LLMs和传统推荐系统的优势。该框架采用双阶段策略，旨在增强对不同用户群体的适应性，通过智能分配任务，实现LLMs的高效和负责任的应用。我们首先识别出那些在推荐系统中排名表现不佳的弱势和非活跃用户，然后采用上下文学习方法，将每位用户的交互历史作为独立的排名任务，交由LLM处理。我们通过整合多种推荐算法和两款LLMs（开源和闭源）来测试这一框架，并在三个现实世界的数据集上取得了显著成效：弱势用户数量显著减少，推荐系统对子群体的鲁棒性提升了约12%，整体性能得到增强，而成本却没有不合理地增加。

> Conventional recommendation systems (RSs) are typically optimized to enhance performance metrics uniformly across all training samples.
  This makes it hard for data-driven RSs to cater to a diverse set of users due to the varying properties of these users. The performance disparity among various populations can harm the model's robustness with respect to sub-populations. While recent works have shown promising results in adapting large language models (LLMs) for recommendation to address hard samples, long user queries from millions of users can degrade the performance of LLMs and elevate costs, processing times and inference latency. This challenges the practical applicability of LLMs for recommendations. To address this, we propose a hybrid task allocation framework that utilizes the capabilities of both LLMs and traditional RSs. By adopting a two-phase approach to improve robustness to sub-populations, we promote a strategic assignment of tasks for efficient and responsible adaptation of LLMs. Our strategy works by first identifying the weak and inactive users that receive a suboptimal ranking performance by RSs. Next, we use an in-context learning approach for such users, wherein each user interaction history is contextualized as a distinct ranking task and given to an LLM. We test our hybrid framework by incorporating various recommendation algorithms -- collaborative filtering and learning-to-rank recommendation models -- and two LLMs -- both open and close-sourced. Our results on three real-world datasets show a significant reduction in weak users and improved robustness of RSs to sub-populations $(\approx12\%)$ and overall performance without disproportionately escalating costs.

[Arxiv](https://arxiv.org/abs/2405.00824)