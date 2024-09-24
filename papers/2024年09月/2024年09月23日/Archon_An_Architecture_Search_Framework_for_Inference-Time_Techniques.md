# Archon：专为推理时技术设计的架构搜索框架

发布时间：2024年09月23日

`LLM应用` `人工智能` `软件工程`

> Archon: An Architecture Search Framework for Inference-Time Techniques

# 摘要

> 推理时技术正成为提升大型语言模型（LLM）能力的利器。然而，如何将这些技术与一个或多个LLM结合的最佳实践仍待探索，主要挑战有三：有效分配计算资源、理解技术组合间的相互作用及其对性能的影响、高效搜索模型与技术的组合。为此，我们推出了Archon，一个自动化设计推理时架构的框架。Archon构建了一个涵盖生成集成、多采样、排序、融合、批评、验证和单元测试等方法的可扩展设计空间，并将选择与组合LLM和技术的问题转化为超参数优化。我们引入了自动推理时架构搜索（ITAS）算法，根据目标基准、计算预算和可用LLM，输出优化架构。在MT-Bench、Arena-Hard-Auto、AlpacaEval 2.0、MixEval、MixEval Hard、MATH和CodeContests等广泛基准测试中，Archon设计的架构表现优异，分别在全源和开源模型上，平均提升了14.1和10.3个百分点，超越了GPT-4o和Claude 3.5 Sonnet等强手。我们已在Github公开代码和数据集：https://github.com/ScalingIntelligence/Archon。

> Inference-time techniques are emerging as highly effective tools to increase large language model (LLM) capabilities. However, there is still limited understanding of the best practices for developing systems that combine inference-time techniques with one or more LLMs, with challenges including: (1) effectively allocating inference compute budget, (2) understanding the interactions between different combinations of inference-time techniques and their impact on downstream performance, and 3) efficiently searching over the large space of model choices, inference-time techniques, and their compositions. To address these challenges, we introduce Archon, an automated framework for designing inference-time architectures. Archon defines an extensible design space, encompassing methods such as generation ensembling, multi-sampling, ranking, fusion, critiquing, verification, and unit testing. It then transforms the problem of selecting and combining LLMs and inference-time techniques into a hyperparameter optimization objective. To optimize this objective, we introduce automated Inference-Time Architecture Search (ITAS) algorithms. Given target benchmark(s), an inference compute budget, and available LLMs, ITAS outputs optimized architectures. We evaluate Archon architectures across a wide range of instruction-following and reasoning benchmarks, including MT-Bench, Arena-Hard-Auto, AlpacaEval 2.0, MixEval, MixEval Hard, MATH, and CodeContests. We show that automatically designed inference-time architectures by Archon outperform strong models such as GPT-4o and Claude 3.5 Sonnet on these benchmarks, achieving an average increase of 14.1 and 10.3 percentage points with all-source models and open-source models, respectively. We make our code and datasets available publicly on Github: https://github.com/ScalingIntelligence/Archon.

[Arxiv](https://arxiv.org/abs/2409.15254)