# PolyRouter：一款集成了多个大型语言模型的查询系统

发布时间：2024年08月22日

`LLM应用` `信息技术` `人工智能`

> PolyRouter: A Multi-LLM Querying System

# 摘要

> 随着 LLM 在多领域的蓬勃发展，众多具备特定领域知识的 LLM 应运而生。这一现象催生了对于高效、优质且经济的 LLM 查询响应技术的迫切需求。然而，目前尚无单一模型能完美解决这一三重困境：有的模型性能卓越但成本高昂，有的则快速廉价但质量欠佳。为此，我们创新性地推出了 PolyRouter，这一非单一化的 LLM 查询系统，它巧妙地将各类 LLM 专家整合至统一查询界面，并智能地将查询导向最适合的专家。实验结果显示，相较于单一专家模型，PolyRouter 不仅提升了高达 40% 的查询效率，还实现了高达 30% 的成本削减，同时确保了模型性能的维持甚至提升。

> With the rapid growth of Large Language Models (LLMs) across various domains, numerous new LLMs have emerged, each possessing domain-specific expertise. This proliferation has highlighted the need for quick, high-quality, and cost-effective LLM query response methods. Yet, no single LLM exists to efficiently balance this trilemma. Some models are powerful but extremely costly, while others are fast and inexpensive but qualitatively inferior. To address this challenge, we present PolyRouter, a non-monolithic LLM querying system that seamlessly integrates various LLM experts into a single query interface and dynamically routes incoming queries to the most high-performant expert based on query's requirements. Through extensive experiments, we demonstrate that when compared to standalone expert models, PolyRouter improves query efficiency by up to 40%, and leads to significant cost reductions of up to 30%, while maintaining or enhancing model performance by up to 10%.

[Arxiv](https://arxiv.org/abs/2408.12320)