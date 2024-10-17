# 利用 Pointwise V-Usable Information 进行多任务学习中的任务分组识别

发布时间：2024年10月16日

`LLM应用`

> Identifying Task Groupings for Multi-Task Learning Using Pointwise V-Usable Information

# 摘要

> 多任务学习的成败关键在于任务分组。简单地将所有或随机任务组合在一起，可能导致负迁移，使多任务模型表现不如单任务模型。尽管已有许多研究致力于识别任务分组和测量任务相关性，但如何从众多潜在组合中找出最佳分组，仍是一大挑战。我们提出了一种基于点态 V-可用信息 (PVI) 的任务相关性指标，PVI 用于估算数据集在给定模型下的信息量。我们假设，PVI 估计值无显著差异的任务，其相似度足以从联合学习中获益。我们在 15 个 NLP 数据集（涵盖通用、生物医学和临床领域）上进行了全面实验，评估了该指标的任务分组效果。结果表明，通过将 PVI 相似的任务分组，联合学习者在参数较少的情况下，表现与单学习者、现有基线方法及大型语言模型（如 Llama 2 和 GPT-4）相当，且在各领域表现稳定。

> The success of multi-task learning can depend heavily on which tasks are grouped together. Naively grouping all tasks or a random set of tasks can result in negative transfer, with the multi-task models performing worse than single-task models. Though many efforts have been made to identify task groupings and to measure the relatedness among different tasks, it remains a challenging research topic to define a metric to identify the best task grouping out of a pool of many potential task combinations. We propose a metric of task relatedness based on task difficulty measured by pointwise V-usable information (PVI). PVI is a recently proposed metric to estimate how much usable information a dataset contains given a model. We hypothesize that tasks with not statistically different PVI estimates are similar enough to benefit from the joint learning process. We conduct comprehensive experiments to evaluate the feasibility of this metric for task grouping on 15 NLP datasets in the general, biomedical, and clinical domains. We compare the results of the joint learners against single learners, existing baseline methods, and recent large language models, including Llama 2 and GPT-4. The results show that by grouping tasks with similar PVI estimates, the joint learners yielded competitive results with fewer total parameters, with consistent performance across domains.

[Arxiv](https://arxiv.org/abs/2410.12774)