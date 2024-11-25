# SRSA：一种适用于现实世界人机交互的高性价比策略-路由器搜索代理

发布时间：2024年11月21日

`Agent` `搜索代理` `人机交互`

> SRSA: A Cost-Efficient Strategy-Router Search Agent for Real-world Human-Machine Interactions

# 摘要

> 近来，大型语言模型（LLMs）展现出令人瞩目的新兴能力且备受青睐，基于 LLM 的搜索代理研究如雨后春笋般涌现。在实际场景中，用户常向聊天机器人输入情境化且高度个性化的查询，这给 LLM 捕捉情境并生成恰当答案带来挑战。然而，先前诸多研究并未特别着眼于真实的人机对话场景，还因迫使所有查询遵循相同代理流程，而忽视了响应质量与计算成本间的重要平衡。为填补这些空白，我们提出策略路由器搜索代理（SRSA），将不同查询导向合适的搜索策略，实现细粒度串行搜索，以相对较低成本获取高质量结果。为评估我们的工作，我们引入新数据集——情境查询增强数据集（CQED），包含情境查询，以模拟真实日常的人机交互。借助基于 LLM 的自动评估指标，我们从信息性、完整性、新颖性和可操作性等方面评估了 SRSA 的性能。总之，SRSA 提供了一种方法，解决了冗长情境化查询因简单串行搜索导致答案退化的问题，能有效高效解析复杂用户查询，且在不微调 LLM 的情况下生成更全面丰富的响应。

> Recently, as Large Language Models (LLMs) have shown impressive emerging capabilities and gained widespread popularity, research on LLM-based search agents has proliferated. In real-world situations, users often input contextual and highly personalized queries to chatbots, challenging LLMs to capture context and generate appropriate answers. However, much of the prior research has not focused specifically on authentic human-machine dialogue scenarios. It also ignores the important balance between response quality and computational cost by forcing all queries to follow the same agent process. To address these gaps, we propose a Strategy-Router Search Agent (SRSA), routing different queries to appropriate search strategies and enabling fine-grained serial searches to obtain high-quality results at a relatively low cost. To evaluate our work, we introduce a new dataset, Contextual Query Enhancement Dataset (CQED), comprising contextual queries to simulate authentic and daily interactions between humans and chatbots. Using LLM-based automatic evaluation metrics, we assessed SRSA's performance in terms of informativeness, completeness, novelty, and actionability. To conclude, SRSA provides an approach that resolves the issue of simple serial searches leading to degenerate answers for lengthy and contextual queries, effectively and efficiently parses complex user queries, and generates more comprehensive and informative responses without fine-tuning an LLM.

[Arxiv](https://arxiv.org/abs/2411.14574)