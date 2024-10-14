# SimpleStrat：以分层策略丰富语言模型生成多样性

发布时间：2024年10月11日

`LLM应用` `人工智能`

> SimpleStrat: Diversifying Language Model Generation with Stratification

# 摘要

> 在 LLM 中生成多样化响应对于规划/搜索和合成数据生成等应用至关重要，因为多样性能够提供每次生成中的不同答案。传统方法通过提高温度来增加多样性，但我们发现这不仅降低了生成质量，还依赖于模型概率与真实答案分布的相似性。为此，我们提出了 \method{}，利用语言模型本身将空间划分为层，并在推理时随机选择层并从中抽样。为衡量多样性，我们创建了 CoverageQA 数据集，并通过 KL 散度评估输出分布与真实答案均匀分布的差异。由于专有模型难以计算每个响应的概率，我们通过召回率来评估。实验表明，SimpleStrat 相比 GPT-4o 召回率提升 0.05，KL 散度平均减少 0.36。

> Generating diverse responses from large language models (LLMs) is crucial for applications such as planning/search and synthetic data generation, where diversity provides distinct answers across generations. Prior approaches rely on increasing temperature to increase diversity. However, contrary to popular belief, we show not only does this approach produce lower quality individual generations as temperature increases, but it depends on model's next-token probabilities being similar to the true distribution of answers. We propose \method{}, an alternative approach that uses the language model itself to partition the space into strata. At inference, a random stratum is selected and a sample drawn from within the strata. To measure diversity, we introduce CoverageQA, a dataset of underspecified questions with multiple equally plausible answers, and assess diversity by measuring KL Divergence between the output distribution and uniform distribution over valid ground truth answers. As computing probability per response/solution for proprietary models is infeasible, we measure recall on ground truth solutions. Our evaluation show using SimpleStrat achieves higher recall by 0.05 compared to GPT-4o and 0.36 average reduction in KL Divergence compared to Llama 3.

[Arxiv](https://arxiv.org/abs/2410.09038)