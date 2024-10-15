# 通过多样化的提示代理扩展搜索空间：一种高效的采样方法，助力 LLM 在数学推理中的表现。

发布时间：2024年10月13日

`LLM理论` `人工智能`

> Expanding Search Space with Diverse Prompting Agents: An Efficient Sampling Approach for LLM Mathematical Reasoning

# 摘要

> LLM 在数学推理等复杂任务中表现出色，但传统方法局限于单一提示策略，限制了多样化策略的探索。本研究通过实验分析不同提示方法，发现每种方法探索的搜索空间各异，且问题越复杂，差异越明显。我们采用高效采样，综合多种方法的样本，不仅扩大了搜索范围，还以更少的运行次数提升了性能。特别是在 MATH-hard 子集中，搜索空间最大化，运行次数减少约 43%。这些发现凸显了整合多样化策略对提升 LLM 推理能力的重要性。

> Large Language Models (LLMs) have exhibited remarkable capabilities in many complex tasks including mathematical reasoning. However, traditional approaches heavily rely on ensuring self-consistency within single prompting method, which limits the exploration of diverse problem-solving strategies. This study addresses these limitations by performing an experimental analysis of distinct prompting methods within the domain of mathematical reasoning. Our findings demonstrate that each method explores a distinct search space, and this differentiation becomes more evident with increasing problem complexity. To leverage this phenomenon, we applied efficient sampling process that uniformly combines samples from these diverse methods, which not only expands the maximum search space but achieves higher performance with fewer runs compared to single methods. Especially, within the subset of difficult questions of MATH dataset named MATH-hard, The maximum search space was achieved while utilizing approximately 43% fewer runs than single methods on average. These findings highlight the importance of integrating diverse problem-solving strategies to enhance the reasoning abilities of LLMs.

[Arxiv](https://arxiv.org/abs/2410.09780)