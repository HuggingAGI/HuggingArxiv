# 推动智能体系统发展：基于新指标和数据集的动态任务分解、工具集成与评估

发布时间：2024年10月29日

`Agent` `智能体系统` `自动化`

> Advancing Agentic Systems: Dynamic Task Decomposition, Tool Integration and Evaluation using Novel Metrics and Dataset

# 摘要

> 大型语言模型（LLMs）的进步正在掀起自主智能体系统发展的变革，其通过实现动态、能感知上下文的任务分解以及自动工具选择得以实现。这些复杂的系统在各行业展现出巨大的自动化潜能，能处理复杂任务、与外部系统互动以增进知识，并独立执行操作。本文在推动此领域发展方面有三项主要贡献：
  - 高级智能体框架：这是一个能处理多跳查询、生成并执行任务图、挑选合适工具且适应实时变化的系统。
  - 新颖的评估指标：引入节点 F1 分数、结构相似性指数（SSI）和工具 F1 分数，以对智能体系统进行全面评估。
  - 专用数据集：开发基于 AsyncHow 的数据集，用于剖析不同任务复杂程度下的智能体行为。
  我们的发现表明，异步和动态的任务图分解极大地增强了系统的响应能力和可扩展性，尤其对于复杂的多步骤任务而言。详细分析显示，结构和节点级别的指标对顺序任务至关重要，而与工具相关的指标对并行任务更关键。具体来说，结构相似性指数（SSI）是顺序任务性能的最重要预测因子，工具 F1 分数对并行任务不可或缺。这些见解凸显了需要平衡的评估方法，以捕捉智能体系统的结构和操作维度。此外，我们的评估框架经实证分析和统计测试验证，为提升动态环境中智能体系统的适应性和可靠性提供了宝贵的见解。

> Advancements in Large Language Models (LLMs) are revolutionizing the development of autonomous agentic systems by enabling dynamic, context-aware task decomposition and automated tool selection. These sophisticated systems possess significant automation potential across various industries, managing complex tasks, interacting with external systems to enhance knowledge, and executing actions independently. This paper presents three primary contributions to advance this field:
  - Advanced Agentic Framework: A system that handles multi-hop queries, generates and executes task graphs, selects appropriate tools, and adapts to real-time changes.
  - Novel Evaluation Metrics: Introduction of Node F1 Score, Structural Similarity Index (SSI), and Tool F1 Score to comprehensively assess agentic systems.
  - Specialized Dataset: Development of an AsyncHow-based dataset for analyzing agent behavior across different task complexities.
  Our findings reveal that asynchronous and dynamic task graph decomposition significantly enhances system responsiveness and scalability, particularly for complex, multi-step tasks. Detailed analysis shows that structural and node-level metrics are crucial for sequential tasks, while tool-related metrics are more important for parallel tasks. Specifically, the Structural Similarity Index (SSI) is the most significant predictor of performance in sequential tasks, and the Tool F1 Score is essential for parallel tasks. These insights highlight the need for balanced evaluation methods that capture both structural and operational dimensions of agentic systems. Additionally, our evaluation framework, validated through empirical analysis and statistical testing, provides valuable insights for improving the adaptability and reliability of agentic systems in dynamic environments.

[Arxiv](https://arxiv.org/abs/2410.22457)