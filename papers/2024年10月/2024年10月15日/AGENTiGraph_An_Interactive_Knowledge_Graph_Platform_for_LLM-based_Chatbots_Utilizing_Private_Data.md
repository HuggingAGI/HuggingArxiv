# AGENTiGraph：专为基于 LLM 的聊天机器人设计的交互式知识图谱平台，充分利用私有数据。

发布时间：2024年10月15日

`Agent` `知识管理`

> AGENTiGraph: An Interactive Knowledge Graph Platform for LLM-based Chatbots Utilizing Private Data

# 摘要

> 大型语言模型 (LLM) 虽在多领域表现出色，但仍面临幻觉、推理能力有限和事实不一致等挑战，尤其是在处理复杂问答任务时。尽管知识图谱 (KGs) 能缓解这些问题，但 LLM 与 KGs 的整合研究尚不充分，尤其是用户访问和 KG 灵活性方面。为此，我们推出了 AGENTiGraph，一个通过自然语言交互进行知识管理的平台，集成了知识提取、整合和实时可视化。AGENTiGraph 采用多代理架构，动态解析用户意图、管理任务并整合新知识，确保适应不断变化的需求和数据环境。实验表明，AGENTiGraph 在知识图谱交互中表现优异，尤其在复杂任务中，显著超越了最先进的零-shot 基线，任务分类准确率达 95.12%，任务执行成功率达 90.45%。用户研究也证实了其在实际应用中的有效性。此外，我们将 AGENTiGraph 扩展至立法和医疗领域，构建了能处理复杂法律和医疗查询的专用 KGs，展示了其广泛的应用潜力。

> Large Language Models~(LLMs) have demonstrated capabilities across various applications but face challenges such as hallucination, limited reasoning abilities, and factual inconsistencies, especially when tackling complex, domain-specific tasks like question answering~(QA). While Knowledge Graphs~(KGs) have been shown to help mitigate these issues, research on the integration of LLMs with background KGs remains limited. In particular, user accessibility and the flexibility of the underlying KG have not been thoroughly explored. We introduce AGENTiGraph (Adaptive Generative ENgine for Task-based Interaction and Graphical Representation), a platform for knowledge management through natural language interaction. It integrates knowledge extraction, integration, and real-time visualization. AGENTiGraph employs a multi-agent architecture to dynamically interpret user intents, manage tasks, and integrate new knowledge, ensuring adaptability to evolving user requirements and data contexts. Our approach demonstrates superior performance in knowledge graph interactions, particularly for complex domain-specific tasks. Experimental results on a dataset of 3,500 test cases show AGENTiGraph significantly outperforms state-of-the-art zero-shot baselines, achieving 95.12\% accuracy in task classification and 90.45\% success rate in task execution. User studies corroborate its effectiveness in real-world scenarios. To showcase versatility, we extended AGENTiGraph to legislation and healthcare domains, constructing specialized KGs capable of answering complex queries in legal and medical contexts.

[Arxiv](https://arxiv.org/abs/2410.11531)