# 最安全者生存：通过交错多目标进化，迈向安全提示优化

发布时间：2024年10月12日

`LLM应用` `人工智能`

> Survival of the Safest: Towards Secure Prompt Optimization through Interleaved Multi-Objective Evolution

# 摘要

> 大型语言模型 (LLM) 虽展示出卓越能力，但其提示优化长期侧重性能，忽视了安全与保障。为此，我们推出“最安全生存” (SoS) 框架，创新性地同时提升 LLM 的性能与安全性。SoS 采用交错多目标进化策略，融合语义、反馈与交叉突变，高效探索提示空间。相较于计算密集的 Pareto 前沿法，SoS 提供可扩展方案，加速高维复杂搜索空间的优化，且计算需求低。我们的方法灵活加权目标，生成优化候选池，使用户能精准选择符合其性能与安全需求的提示。跨基准数据集的实验验证了 SoS 在性能与安全双提升上的显著效果，超越单一目标方法。这一突破性进展，为在多样工业应用中部署高性能且安全的 LLM 系统铺平了道路。

> Large language models (LLMs) have demonstrated remarkable capabilities; however, the optimization of their prompts has historically prioritized performance metrics at the expense of crucial safety and security considerations. To overcome this shortcoming, we introduce "Survival of the Safest" (SoS), an innovative multi-objective prompt optimization framework that enhances both performance and security in LLMs simultaneously. SoS utilizes an interleaved multi-objective evolution strategy, integrating semantic, feedback, and crossover mutations to effectively traverse the prompt landscape. Differing from the computationally demanding Pareto front methods, SoS provides a scalable solution that expedites optimization in complex, high-dimensional discrete search spaces while keeping computational demands low. Our approach accommodates flexible weighting of objectives and generates a pool of optimized candidates, empowering users to select prompts that optimally meet their specific performance and security needs. Experimental evaluations across diverse benchmark datasets affirm SoS's efficacy in delivering high performance and notably enhancing safety and security compared to single-objective methods. This advancement marks a significant stride towards the deployment of LLM systems that are both high-performing and secure across varied industrial applications

[Arxiv](https://arxiv.org/abs/2410.09652)