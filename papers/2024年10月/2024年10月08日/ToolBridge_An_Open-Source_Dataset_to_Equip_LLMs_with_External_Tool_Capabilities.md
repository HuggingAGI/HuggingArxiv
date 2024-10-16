# ToolBridge：一款开源数据集，旨在赋予大型语言模型（LLM）使用外部工具的能力。

发布时间：2024年10月08日

`LLM应用` `人工智能` `数据科学`

> ToolBridge: An Open-Source Dataset to Equip LLMs with External Tool Capabilities

# 摘要

> 通过结合外部工具，如GPT-4o和Llama 3.1这样的大型语言模型（LLMs）已从简单的对话代理进化为多功能助手。我们相信，这些进步的关键在于训练数据的质量与多样性。然而，当前的LLMs对外部工具集成的数据集和收集方法透明度有限，这促使我们展开研究。本文旨在揭示构建数据集的详细流程，这些数据集使LLMs能有效利用外部工具，并通过ToolBridge项目公开这些信息。ToolBridge采用通用开放数据集作为基础，通过一系列策略筛选出适合插入外部工具API的数据条目。经过监督微调，LLMs能在恰当场景中调用外部工具，显著提升预测准确性，特别是在数据处理、数值计算和事实检索等基础功能上。实验严格控制模型架构与训练配置，专注于数据的影响。结果显示，使用ToolBridge训练的LLMs在标准与自定义评估中均表现优异。所有代码与数据将在https://github.com/CharlesPikachu/ToolBridge开源，推动透明化，助力社区探索提升LLMs外部工具能力的方法。

> Through the integration of external tools, large language models (LLMs) such as GPT-4o and Llama 3.1 significantly expand their functional capabilities, evolving from elementary conversational agents to general-purpose assistants. We argue that the primary drivers of these advancements are the quality and diversity of the training data. However, the existing LLMs with external tool integration provide only limited transparency regarding their datasets and data collection methods, which has led to the initiation of this research. Specifically, in this paper, our objective is to elucidate the detailed process involved in constructing datasets that empower LLMs to effectively learn how to utilize external tools and make this information available to the public through the introduction of ToolBridge. ToolBridge proposes to employ a collection of general open-access datasets as its raw dataset pool and applies a series of strategies to identify appropriate data entries from the pool for external tool API insertions. By supervised fine-tuning on these curated data entries, LLMs can invoke external tools in appropriate contexts to boost their predictive accuracy, particularly for basic functions including data processing, numerical computation, and factual retrieval. Our experiments rigorously isolates model architectures and training configurations, focusing exclusively on the role of data. The experimental results indicate that LLMs trained on ToolBridge demonstrate consistent performance improvements on both standard benchmarks and custom evaluation datasets. All the associated code and data will be open-source at https://github.com/CharlesPikachu/ToolBridge, promoting transparency and facilitating the broader community to explore approaches for equipping LLMs with external tools capabilities.

[Arxiv](https://arxiv.org/abs/2410.10872)