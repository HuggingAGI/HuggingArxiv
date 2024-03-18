# ToolNet 利用工具图这一桥梁，巧妙地将大型语言模型与海量工具紧密相连。

发布时间：2024年02月28日

`LLM应用`

> ToolNet: Connecting Large Language Models with Massive Tools via Tool Graph

> 虽然LLMs在众多任务中表现出色，但在有效利用大量外部工具方面却存在明显短板。现有上下文学习方式仅将工具以纯文本列表形式呈现给LLMs，由其逐步骤生成工具调用来解决问题，这一做法忽略了工具间的内在关联，过度依赖LLMs进行推理，导致其难以应对非定制的大规模工具库，从而在实际应用场景下遭遇巨大瓶颈。为此，本文提出了一种名为ToolNet的即插即用框架，该框架能够在适度增加令牌消耗的前提下，将支持的工具数量扩容至数千个级别。ToolNet巧妙地将工具构建成一个有向图结构，节点代表工具，加权边则描绘了工具间的过渡关系。LLM从起始工具节点出发，通过循环选取后继节点在图中寻路，直至完成任务。广泛的实验证明，ToolNet在复杂的多跳工具学习数据集中展现出卓越性能，同时具备抵抗工具失效的强大韧性。

> While achieving remarkable progress in a broad range of tasks, large language models (LLMs) remain significantly limited in properly using massive external tools. Existing in-context learning approaches simply format tools into a list of plain text descriptions and input them to LLMs, from which, LLMs generate a sequence of tool calls to solve problems step by step. Such a paradigm ignores the intrinsic dependency between tools and offloads all reasoning loads to LLMs, making them restricted to a limited number of specifically designed tools. It thus remains challenging for LLMs to operate on a library of massive tools, casting a great limitation when confronted with real-world scenarios. This paper proposes ToolNet, a plug-and-play framework that scales up the number of tools to thousands with a moderate increase in token consumption. ToolNet organizes tools into a directed graph. Each node represents a tool, and weighted edges denote tool transition. Starting from an initial tool node, an LLM navigates in the graph by iteratively choosing the next one from its successors until the task is resolved. Extensive experiments show that ToolNet can achieve impressive results in challenging multi-hop tool learning datasets and is resilient to tool failures.

[Arxiv](https://arxiv.org/abs/2403.00839)