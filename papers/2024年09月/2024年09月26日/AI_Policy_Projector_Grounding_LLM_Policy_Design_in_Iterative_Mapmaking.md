# AI 政策投影仪：通过迭代地图制作，为 LLM 政策设计奠定基础

发布时间：2024年09月26日

`LLM应用` `人工智能安全` `策略设计`

> AI Policy Projector: Grounding LLM Policy Design in Iterative Mapmaking

# 摘要

> 无论是显式还是隐式的语言模型策略，评估其在无界现实情境中的覆盖范围都颇具挑战。我们借鉴地图制作的理念，开发了一种AI策略设计流程，即使在无法全面覆盖的情况下，也能实现策略的可视化和迭代。借助Policy Projector，策略设计者能全面审视模型输入输出的全景，自定义关键区域（如“暴力”），并运用规则导航这些区域，例如在输出涉及“暴力”和“图形细节”时，自动重写以去除“图形细节”。该工具支持基于LLM分类和引导的互动策略创作，并提供直观的地图可视化，展现策略设计者的构思。在与12位AI安全专家的合作评估中，我们的系统有效助力策略设计者应对超越现有伤害分类框架的模型行为问题。

> Whether a large language model policy is an explicit constitution or an implicit reward model, it is challenging to assess coverage over the unbounded set of real-world situations that a policy must contend with. We introduce an AI policy design process inspired by mapmaking, which has developed tactics for visualizing and iterating on maps even when full coverage is not possible. With Policy Projector, policy designers can survey the landscape of model input-output pairs, define custom regions (e.g., "violence"), and navigate these regions with rules that can be applied to LLM outputs (e.g., if output contains "violence" and "graphic details," then rewrite without "graphic details"). Policy Projector supports interactive policy authoring using LLM classification and steering and a map visualization reflecting the policy designer's work. In an evaluation with 12 AI safety experts, our system helps policy designers to address problematic model behaviors extending beyond an existing, comprehensive harm taxonomy.

[Arxiv](https://arxiv.org/abs/2409.18203)