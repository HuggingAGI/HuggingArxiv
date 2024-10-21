# Toolshed：借助先进的 RAG-Tool 融合与工具知识库，扩展工具化代理的能力

发布时间：2024年10月18日

`Agent` `软件开发` `数据库管理`

> Toolshed: Scale Tool-Equipped Agents with Advanced RAG-Tool Fusion and Tool Knowledge Bases

# 摘要

> 配备工具的代理（LLM）在安全数据库交互和多代理代码开发等复杂任务上取得了显著进展。然而，扩展工具容量以超越代理推理或模型限制仍是一大挑战。为此，我们引入了工具箱知识库，一个专门设计用于存储增强工具表示并优化工具选择的向量数据库。同时，我们提出了高级RAG-工具融合，这是一种无需模型微调的先进检索增强生成技术集合，涵盖预检索、检索中和检索后阶段。在预检索阶段，工具文档通过关键信息增强并存储；检索中阶段则通过查询规划和转换提升检索准确性；检索后阶段则对检索结果进行细化并实现自我反思。通过调整代理可访问的工具总数和工具选择阈值，我们有效平衡了检索准确性、代理性能和令牌成本。实验结果显示，我们的方法在ToolE单工具、ToolE多工具和Seal-Tools基准数据集上分别实现了显著的性能提升（Recall@5）。

> Recent advancements in tool-equipped Agents (LLMs) have enabled complex tasks like secure database interactions and multi-agent code development. However, scaling tool capacity beyond agent reasoning or model limits remains a challenge. In this paper, we address these challenges by introducing Toolshed Knowledge Bases, a tool knowledge base (vector database) designed to store enhanced tool representations and optimize tool selection for large-scale tool-equipped Agents. Additionally, we propose Advanced RAG-Tool Fusion, a novel ensemble of tool-applied advanced retrieval-augmented generation (RAG) techniques across the pre-retrieval, intra-retrieval, and post-retrieval phases, without requiring model fine-tuning. During pre-retrieval, tool documents are enhanced with key information and stored in the Toolshed Knowledge Base. Intra-retrieval focuses on query planning and transformation to increase retrieval accuracy. Post-retrieval refines the retrieved tool documents and enables self-reflection. Furthermore, by varying both the total number of tools (tool-M) an Agent has access to and the tool selection threshold (top-k), we address trade-offs between retrieval accuracy, agent performance, and token cost. Our approach achieves 46%, 56%, and 47% absolute improvements on the ToolE single-tool, ToolE multi-tool and Seal-Tools benchmark datasets, respectively (Recall@5).

[Arxiv](https://arxiv.org/abs/2410.14594)