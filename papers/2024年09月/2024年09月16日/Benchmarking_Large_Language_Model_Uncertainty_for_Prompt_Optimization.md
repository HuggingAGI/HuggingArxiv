# 评估大型语言模型的不确定性，助力提示优化

发布时间：2024年09月16日

`LLM理论` `人工智能`

> Benchmarking Large Language Model Uncertainty for Prompt Optimization

# 摘要

> 尽管 LLM 的提示优化算法在多步骤推理中表现优异，但置信度估计仍显不足。本文推出一个基准数据集，聚焦于答案、正确性、偶然性和认知不确定性等置信度指标的评估。通过分析 GPT-3.5-Turbo 和 Meta-Llama-3.1-8B-Instruct 等模型，我们发现现有指标更偏向于反映输出置信度和多样性的答案不确定性，而非正确性不确定性。这凸显了改进指标的必要性，这些指标需具备优化目标意识，以更精准地引导提示优化。相关代码和数据集已公开，详见 https://github.com/0Frett/PO-Uncertainty-Benchmarking。

> Prompt optimization algorithms for Large Language Models (LLMs) excel in multi-step reasoning but still lack effective uncertainty estimation. This paper introduces a benchmark dataset to evaluate uncertainty metrics, focusing on Answer, Correctness, Aleatoric, and Epistemic Uncertainty. Through analysis of models like GPT-3.5-Turbo and Meta-Llama-3.1-8B-Instruct, we show that current metrics align more with Answer Uncertainty, which reflects output confidence and diversity, rather than Correctness Uncertainty, highlighting the need for improved metrics that are optimization-objective-aware to better guide prompt optimization. Our code and dataset are available at https://github.com/0Frett/PO-Uncertainty-Benchmarking.

[Arxiv](https://arxiv.org/abs/2409.10044)