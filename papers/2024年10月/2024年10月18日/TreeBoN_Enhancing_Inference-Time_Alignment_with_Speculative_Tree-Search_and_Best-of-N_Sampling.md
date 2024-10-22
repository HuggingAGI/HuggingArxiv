# TreeBoN：借助推测性树搜索与最佳 N 采样，提升推理时的对齐效果

发布时间：2024年10月18日

`LLM应用` `人工智能`

> TreeBoN: Enhancing Inference-Time Alignment with Speculative Tree-Search and Best-of-N Sampling

# 摘要

> 推理时对齐无需额外训练或微调，即可提升大型语言模型的性能，但需在计算效率与高质量输出间找到平衡。Best-of-N (BoN) 采样虽简单有效，但计算成本高。为此，我们提出 TreeBoN，将推测性树搜索融入 BoN 采样，通过迭代分支与修剪低质响应，降低计算开销并保持高输出质量。TreeBoN 还利用直接偏好优化 (DPO) 的令牌级奖励，指导树扩展与低质路径修剪。实验表明，TreeBoN 在 AlpacaFarm、UltraFeedback 等数据集上表现优异，尤其在 192 和 384 令牌长度下胜率达 65%，超越标准 BoN。此外，TreeBoN 在更长响应中胜率约 60%，彰显其可扩展性与对齐效果。

> Inference-time alignment enhances the performance of large language models without requiring additional training or fine-tuning but presents challenges due to balancing computational efficiency with high-quality output. Best-of-N (BoN) sampling, as a simple yet powerful approach, generates multiple responses and selects the best one, achieving improved performance but with a high computational cost. We propose TreeBoN, a novel framework that integrates a speculative tree-search strategy into Best-of-N (BoN) Sampling. TreeBoN maintains a set of parent nodes, iteratively branching and pruning low-quality responses, thereby reducing computational overhead while maintaining high output quality. Our approach also leverages token-level rewards from Direct Preference Optimization (DPO) to guide tree expansion and prune low-quality paths. We evaluate TreeBoN using AlpacaFarm, UltraFeedback, GSM8K, HH-RLHF, and TutorEval datasets, demonstrating consistent improvements. Specifically, TreeBoN achieves a 65% win rate at maximum lengths of 192 and 384 tokens, outperforming standard BoN with the same computational cost. Furthermore, TreeBoN achieves around a 60% win rate across longer responses, showcasing its scalability and alignment efficacy.

[Arxiv](https://arxiv.org/abs/2410.16033)