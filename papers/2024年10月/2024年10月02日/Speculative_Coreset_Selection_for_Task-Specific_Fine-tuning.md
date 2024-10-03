# 任务特定微调中的推测性核心集选择

发布时间：2024年10月02日

`LLM应用` `人工智能` `机器学习`

> Speculative Coreset Selection for Task-Specific Fine-tuning

# 摘要

> 任务特定微调对 LLM 部署至关重要，但耗费大量计算资源和时间。现有方法虽提出核心集选择以提高数据效率，但仍有局限：1) 高剪枝率下忽略宝贵样本，影响核心集性能；2) 核心集选择过程耗时，需微调和评估目标 LLM。本文介绍 STAFF，一种推测性核心集选择方法。STAFF 利用同系列小模型高效估算数据分数，并在目标 LLM 上验证，确保重要区域得到更多选择预算，同时覆盖简单区域。实验表明，STAFF 在三个 LLM 和三个下游任务中，将 SOTA 方法性能提升高达 54.3%，选择开销减少高达 70.5%。此外，低剪枝率（20%）下 STAFF 选择的核心集甚至优于完整数据集的微调性能。

> Task-specific fine-tuning is essential for the deployment of large language models (LLMs), but it requires significant computational resources and time. Existing solutions have proposed coreset selection methods to improve data efficiency and reduce model training overhead, but they still have limitations: 1) Overlooking valuable samples at high pruning rates, which degrades the coreset's performance. 2) Requiring high time overhead during coreset selection to fine-tune and evaluate the target LLM. In this paper, we introduce STAFF, a speculative coreset selection method. STAFF leverages a small model from the same family as the target LLM to efficiently estimate data scores and then verifies the scores on the target LLM to accurately identify and allocate more selection budget to important regions while maintaining coverage of easy regions. We evaluate STAFF on three LLMs and three downstream tasks and show that STAFF improves the performance of SOTA methods by up to 54.3% and reduces selection overhead by up to 70.5% at different pruning rates. Furthermore, we observe that the coreset selected by STAFF at low pruning rates (i.e., 20%) can even obtain better fine-tuning performance than the full dataset.

[Arxiv](https://arxiv.org/abs/2410.01296)