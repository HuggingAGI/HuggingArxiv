# 在 LLM 中，如何平衡合成数据生成策略的成本与效果，是一个关键问题。

发布时间：2024年09月29日

`LLM应用` `人工智能` `数据科学`

> Balancing Cost and Effectiveness of Synthetic Data Generation Strategies for LLMs

# 摘要

> 随着 LLM 的应用场景增多，创建高质量、任务特定的数据集成为模型改进的瓶颈。虽然使用高质量人类数据是解锁模型性能的常见方法，但在许多情况下成本过高。此外，合成或混合数据生成等替代方法的有效性仍不明确，尤其是在资源受限和难以验证的任务中。为此，我们将合成数据生成策略分为三类：答案增强、问题重述和新问题，并研究了在不同约束下训练的 LLM 性能。结果显示，最佳数据生成策略取决于教师查询预算与种子指令集大小的比率。当比率低时，生成新答案最有效；比率增加时，生成新问题更优。我们还发现，在低到中数据体制下，增强方法的选择尤为关键。为此，我们提供了一个实用框架，帮助根据具体情况选择合适的增强方法，并考虑了可扩展性、数据验证和使用不同 LLM 生成数据等因素。

> As large language models (LLMs) are applied to more use cases, creating high quality, task-specific datasets for fine-tuning becomes a bottleneck for model improvement. Using high quality human data has been the most common approach to unlock model performance, but is prohibitively expensive in many scenarios. Several alternative methods have also emerged, such as generating synthetic or hybrid data, but the effectiveness of these approaches remain unclear, especially in resource-constrained scenarios and tasks that are not easily verified. To investigate this, we group various synthetic data generation strategies into three representative categories -- Answer Augmentation, Question Rephrase and New Question -- and study the performance of student LLMs trained under various constraints, namely seed instruction set size and query budget. We demonstrate that these strategies are not equally effective across settings. Notably, the optimal data generation strategy depends strongly on the ratio between the available teacher query budget and the size of the seed instruction set. When this ratio is low, generating new answers to existing questions proves most effective, but as this ratio increases, generating new questions becomes optimal. Across all tasks, we find that choice of augmentation method and other design choices matter substantially more in low to mid data regimes than in high data regimes. We provide a practical framework for selecting the appropriate augmentation method across settings, taking into account additional factors such as the scalability of each method, the importance of verifying synthetic data, and the use of different LLMs for synthetic data generation.

[Arxiv](https://arxiv.org/abs/2409.19759)