# 自然语言规划助力 LLM 代码生成搜索更上一层楼

发布时间：2024年09月05日

`LLM应用` `软件开发` `人工智能`

> Planning In Natural Language Improves LLM Search For Code Generation

# 摘要

> 尽管训练计算的扩展显著提升了大型语言模型的性能，但推理计算的扩展尚未带来同等收益。我们推测，核心问题在于LLM输出的多样性不足，导致模型反复生成相似但错误的答案，搜索效率低下。通过实验，我们发现通过在自然语言中搜索解决问题的候选方案，可以有效缓解这一问题。基于此，我们提出了PLANSEARCH算法，该算法在HumanEval+、MBPP+和LiveCodeBench等基准测试中表现出色。PLANSEARCH首先生成多样化的观察结果，然后利用这些观察构建解决方案计划。与直接搜索代码相比，PLANSEARCH在自然语言中搜索计划，探索了更广泛的潜在解决方案。在Claude 3.5 Sonnet上应用PLANSEARCH，LiveCodeBench的pass@200达到了77.0%，超越了不使用搜索和标准采样的最佳成绩。最后，我们发现，所有模型和基准测试中，搜索带来的性能提升与生成想法的多样性直接相关。

> While scaling training compute has led to remarkable improvements in large language models (LLMs), scaling inference compute has not yet yielded analogous gains. We hypothesize that a core missing component is a lack of diverse LLM outputs, leading to inefficient search due to models repeatedly sampling highly similar, yet incorrect generations. We empirically demonstrate that this lack of diversity can be mitigated by searching over candidate plans for solving a problem in natural language. Based on this insight, we propose PLANSEARCH, a novel search algorithm which shows strong results across HumanEval+, MBPP+, and LiveCodeBench (a contamination-free benchmark for competitive coding). PLANSEARCH generates a diverse set of observations about the problem and then uses these observations to construct plans for solving the problem. By searching over plans in natural language rather than directly over code solutions, PLANSEARCH explores a significantly more diverse range of potential solutions compared to baseline search methods. Using PLANSEARCH on top of Claude 3.5 Sonnet achieves a state-of-the-art pass@200 of 77.0% on LiveCodeBench, outperforming both the best score achieved without search (pass@1 = 41.4%) and using standard repeated sampling (pass@200 = 60.6%). Finally, we show that, across all models, search algorithms, and benchmarks analyzed, we can accurately predict performance gains due to search as a direct function of the diversity over generated ideas.

[Arxiv](https://arxiv.org/abs/2409.03733)