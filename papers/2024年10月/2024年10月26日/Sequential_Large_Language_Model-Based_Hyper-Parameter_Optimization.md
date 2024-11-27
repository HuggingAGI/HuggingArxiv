# 基于顺序大型语言模型的超参数优化

发布时间：2024年10月26日

`LLM应用` `超参数优化` `基准测试`

> Sequential Large Language Model-Based Hyper-Parameter Optimization

# 摘要

> 本研究推出了 SLLMBO 这一创新框架，它借助大型语言模型（LLMs）来开展超参数优化（HPO），融合了动态搜索空间适应性、强化的参数景观开发，以及一种新颖的混合式 LLM-树结构 Parzen 估计器（LLM-TPE）采样器。针对近期完全基于 LLM 的方法和传统贝叶斯优化（BO）的不足，SLLMBO 实现了更稳健的优化。此次全面的基准测试评估了众多 LLMs，如 GPT-3.5-turbo、GPT-4o、Claude-Sonnet-3.5 以及 Gemini-1.5-flash，将先前的工作范围拓展到 GPT-3.5 和 GPT-4 之外，使 SLLMBO 成为首个针对多种 LLMs 进行 HPO 基准测试的框架。通过整合 LLMs 在参数初始化方面的既有优势、本研究展现的开发能力以及 TPE 的探索能力，LLM-TPE 采样器达成了探索与开发的平衡，降低了 API 成本，减少了过早提前停止的情况，从而实现更有效的参数搜索。在分类和回归的 14 个表格任务中，LLM-TPE 采样器胜过完全基于 LLM 的方法，在 9 个任务中比 BO 方法表现更优。在预算受限场景下测试提前停止，进一步彰显了其出色的性能，表明基于 LLM 的方法通常在更多迭代下能获取最佳效果。此项工作为未来探索开源 LLMs、LLM 结果在 HPO 中的可重复性，以及在复杂数据集（如图像分类、分割和机器翻译）上对 SLLMBO 进行基准测试的研究奠定了基石。

> This study introduces SLLMBO, an innovative framework that leverages Large Language Models (LLMs) for hyperparameter optimization (HPO), incorporating dynamic search space adaptability, enhanced parameter landscape exploitation, and a hybrid, novel LLM-Tree-structured Parzen Estimator (LLM-TPE) sampler. By addressing limitations in recent fully LLM-based methods and traditional Bayesian Optimization (BO), SLLMBO achieves more robust optimization. This comprehensive benchmarking evaluates multiple LLMs, including GPT-3.5-turbo, GPT-4o, Claude-Sonnet-3.5, and Gemini-1.5-flash, extending prior work beyond GPT-3.5 and GPT-4 and establishing SLLMBO as the first framework to benchmark a diverse set of LLMs for HPO. By integrating LLMs' established strengths in parameter initialization with the exploitation abilities demonstrated in this study, alongside TPE's exploration capabilities, the LLM-TPE sampler achieves a balanced exploration-exploitation trade-off, reduces API costs, and mitigates premature early stoppings for more effective parameter searches. Across 14 tabular tasks in classification and regression, the LLM-TPE sampler outperformed fully LLM-based methods and achieved superior results over BO methods in 9 tasks. Testing early stopping in budget-constrained scenarios further demonstrated competitive performance, indicating that LLM-based methods generally benefit from extended iterations for optimal results. This work lays the foundation for future research exploring open-source LLMs, reproducibility of LLM results in HPO, and benchmarking SLLMBO on complex datasets, such as image classification, segmentation, and machine translation.

[Arxiv](https://arxiv.org/abs/2410.20302)