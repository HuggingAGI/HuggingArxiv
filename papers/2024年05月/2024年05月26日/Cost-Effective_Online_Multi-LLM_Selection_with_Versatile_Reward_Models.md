# 高效经济的在线多大型语言模型选择策略，结合多功能奖励模型优化性能。

发布时间：2024年05月26日

`LLM应用

理由：这篇论文主要讨论了如何通过一种名为C2MAB-V的多臂老虎机模型来优化大型语言模型（LLMs）的选择与应用，以适应多样化的任务需求并平衡成本与奖励。这种方法涉及到在线模型的部署和优化，以及如何通过特定的机制和技术来解决多LLM选择的问题。因此，这篇论文的内容更偏向于LLM的实际应用，而不是理论研究或Agent的设计，也不涉及RAG（Retrieval-Augmented Generation）的相关技术。` `云计算` `人工智能`

> Cost-Effective Online Multi-LLM Selection with Versatile Reward Models

# 摘要

> 随着大型语言模型（LLMs）技术的飞速进步，多LLM任务的多样性及其定价结构的灵活性变得尤为关键，因为不同LLMs的成本差异显著。为此，我们推出了C2MAB-V，一种高效组合的多臂老虎机模型，配备多功能奖励机制，旨在优化LLM的选择与应用。该在线模型与传统静态方法或不计成本的单一LLM依赖方法截然不同。通过在调度云上部署多款LLMs，并配备一个本地服务器来处理用户查询，C2MAB-V能够在组合搜索空间中智能选择适合各类协作任务的LLMs，并根据不同的奖励模型进行优化。借助我们设计的在线反馈机制和置信界限技术，C2MAB-V巧妙地解决了多LLM选择难题，通过在不同模型间平衡探索与利用，同时兼顾成本与奖励，以适应多样化的任务需求。我们通过以下步骤解决了选择多个LLMs的NP难整数线性规划问题：i) 通过本地服务器将整数问题松弛化，ii) 利用调度云的离散化舍入方案确定最佳LLM组合，以及iii) 基于反馈的持续在线更新。理论分析表明，C2MAB-V对多功能奖励模型提供了严格保证，在某些极端情况下与当前最佳实践相媲美。实证研究显示，C2MAB-V在三个不同应用场景中，成功平衡了九个LLMs的性能与成本效益。

> With the rapid advancement of large language models (LLMs), the diversity of multi-LLM tasks and the variability in their pricing structures have become increasingly important, as costs can vary greatly between different LLMs. To tackle these challenges, we introduce the \textit{C2MAB-V}, a \underline{C}ost-effective \underline{C}ombinatorial \underline{M}ulti-armed \underline{B}andit with \underline{V}ersatile reward models for optimal LLM selection and usage. This online model differs from traditional static approaches or those reliant on a single LLM without cost consideration. With multiple LLMs deployed on a scheduling cloud and a local server dedicated to handling user queries, \textit{C2MAB-V} facilitates the selection of multiple LLMs over a combinatorial search space, specifically tailored for various collaborative task types with different reward models. Based on our designed online feedback mechanism and confidence bound technique, \textit{C2MAB-V} can effectively address the multi-LLM selection challenge by managing the exploration-exploitation trade-off across different models, while also balancing cost and reward for diverse tasks. The NP-hard integer linear programming problem for selecting multiple LLMs with trade-off dilemmas is addressed by: i) decomposing the integer problem into a relaxed form by the local server, ii) utilizing a discretization rounding scheme that provides optimal LLM combinations by the scheduling cloud, and iii) continual online updates based on feedback. Theoretically, we prove that \textit{C2MAB-V} offers strict guarantees over versatile reward models, matching state-of-the-art results for regret and violations in some degenerate cases. Empirically, we show that \textit{C2MAB-V} effectively balances performance and cost-efficiency with nine LLMs for three application scenarios.

![高效经济的在线多大型语言模型选择策略，结合多功能奖励模型优化性能。](../../../paper_images/2405.16587/x1.png)

![高效经济的在线多大型语言模型选择策略，结合多功能奖励模型优化性能。](../../../paper_images/2405.16587/x2.png)

![高效经济的在线多大型语言模型选择策略，结合多功能奖励模型优化性能。](../../../paper_images/2405.16587/x3.png)

![高效经济的在线多大型语言模型选择策略，结合多功能奖励模型优化性能。](../../../paper_images/2405.16587/x4.png)

![高效经济的在线多大型语言模型选择策略，结合多功能奖励模型优化性能。](../../../paper_images/2405.16587/x5.png)

![高效经济的在线多大型语言模型选择策略，结合多功能奖励模型优化性能。](../../../paper_images/2405.16587/x6.png)

![高效经济的在线多大型语言模型选择策略，结合多功能奖励模型优化性能。](../../../paper_images/2405.16587/x7.png)

![高效经济的在线多大型语言模型选择策略，结合多功能奖励模型优化性能。](../../../paper_images/2405.16587/x8.png)

![高效经济的在线多大型语言模型选择策略，结合多功能奖励模型优化性能。](../../../paper_images/2405.16587/x9.png)

![高效经济的在线多大型语言模型选择策略，结合多功能奖励模型优化性能。](../../../paper_images/2405.16587/x10.png)

![高效经济的在线多大型语言模型选择策略，结合多功能奖励模型优化性能。](../../../paper_images/2405.16587/x11.png)

![高效经济的在线多大型语言模型选择策略，结合多功能奖励模型优化性能。](../../../paper_images/2405.16587/x12.png)

![高效经济的在线多大型语言模型选择策略，结合多功能奖励模型优化性能。](../../../paper_images/2405.16587/x13.png)

![高效经济的在线多大型语言模型选择策略，结合多功能奖励模型优化性能。](../../../paper_images/2405.16587/x14.png)

![高效经济的在线多大型语言模型选择策略，结合多功能奖励模型优化性能。](../../../paper_images/2405.16587/x15.png)

![高效经济的在线多大型语言模型选择策略，结合多功能奖励模型优化性能。](../../../paper_images/2405.16587/x16.png)

![高效经济的在线多大型语言模型选择策略，结合多功能奖励模型优化性能。](../../../paper_images/2405.16587/x17.png)

![高效经济的在线多大型语言模型选择策略，结合多功能奖励模型优化性能。](../../../paper_images/2405.16587/x18.png)

![高效经济的在线多大型语言模型选择策略，结合多功能奖励模型优化性能。](../../../paper_images/2405.16587/x19.png)

![高效经济的在线多大型语言模型选择策略，结合多功能奖励模型优化性能。](../../../paper_images/2405.16587/x20.png)

![高效经济的在线多大型语言模型选择策略，结合多功能奖励模型优化性能。](../../../paper_images/2405.16587/x21.png)

![高效经济的在线多大型语言模型选择策略，结合多功能奖励模型优化性能。](../../../paper_images/2405.16587/x22.png)

![高效经济的在线多大型语言模型选择策略，结合多功能奖励模型优化性能。](../../../paper_images/2405.16587/x23.png)

![高效经济的在线多大型语言模型选择策略，结合多功能奖励模型优化性能。](../../../paper_images/2405.16587/x24.png)

[Arxiv](https://arxiv.org/abs/2405.16587)