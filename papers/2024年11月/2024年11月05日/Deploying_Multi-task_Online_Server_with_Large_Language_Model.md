# 部署具有大型语言模型的多任务在线服务器

发布时间：2024年11月05日

`LLM应用` `语言模型` `多任务学习`

> Deploying Multi-task Online Server with Large Language Model

# 摘要

> 在行业中，大量任务被在线部署。传统方法通常通过各自的网络分别处理每个任务，这导致开发和扩展模型的成本过高，特别是在大型语言模型的背景下。尽管多任务方法可以通过参数共享节省成本，但它们在现实应用中往往难以超越单任务方法。为了应对这些挑战，我们为大型语言模型提出了一个三阶段的多任务学习框架。它包括任务过滤，然后在高资源任务上进行微调，最后在所有任务上进行微调。我们在单任务和多任务设置中进行了全面的实验。我们的方法，在不同的基准上举例说明，表明它能够实现与单任务方法相当的性能，同时减少高达 90.9％的开销。

> In the industry, numerous tasks are deployed online. Traditional approaches often tackle each task separately by its own network, which leads to excessive costs for developing and scaling models, especially in the context of large language models. Although multi-task methods can save costs through parameter sharing, they often struggle to outperform single-task methods in real-world applications. To tackle these challenges, we present a three-stage multi-task learning framework for large language models. It involves task filtering, followed by fine-tuning on high-resource tasks, and finally fine-tuning on all tasks. We conducted comprehensive experiments in single-task and multi-task settings. Our approach, exemplified on different benchmarks, demonstrates that it is able to achieve performance comparable to the single-task method while reducing up to 90.9\% of its overhead.

[Arxiv](https://arxiv.org/abs/2411.03644)