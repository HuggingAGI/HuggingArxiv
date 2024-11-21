# EmbodiedRAG：为实现高效且可扩展的机器人任务规划而进行的动态 3D 场景图检索

发布时间：2024年10月31日

`RAG` `机器人` `具身领域`

> EmbodiedRAG: Dynamic 3D Scene Graph Retrieval for Efficient and Scalable Robot Task Planning

# 摘要

> 近期，大型语言模型（LLMs）的进步为机器人在真实、开放的世界环境中的规划带来了令人欣喜的进展。3D 场景图（3DSGs）因其紧凑且语义丰富，为基于 LLM 的规划器提供了颇具前景的环境表征。然而，随着机器人所处环境规模的扩大（如跟踪的实体数量增多）以及场景图信息复杂度的提升（如维护更多属性），由于 LLM 存在输入令牌数量的限制和注意力偏差，直接将 3DSG 提供给基于 LLM 的规划器很快就变得不切实际。受检索增强生成（RAG）方法在为 LLM 问答检索相关文档块方面的成功所启发，我们为具身领域调整了这一范式。具体而言，我们提出了一个名为 EmbodiedRAG 的 3D 场景子图检索框架，用它来增强基于 LLM 的规划器以执行自然语言机器人任务。值得注意的是，当机器人执行计划时，我们检索的子图能够适应环境的变化以及任务相关性的变化。我们证明了 EmbodiedRAG 能够显著减少输入令牌数量（达一个数量级）和规划时间（每个规划步骤的平均时间最多减少 70％），同时提高了在 AI2Thor 模拟的单臂移动机械手家庭任务中的成功率。此外，我们在带有机械手的四足机器人上实现了 EmbodiedRAG，以突显其在真实环境中边缘机器人部署方面的性能优势。

> Recent advances in Large Language Models (LLMs) have helped facilitate exciting progress for robotic planning in real, open-world environments. 3D scene graphs (3DSGs) offer a promising environment representation for grounding such LLM-based planners as they are compact and semantically rich. However, as the robot's environment scales (e.g., number of entities tracked) and the complexity of scene graph information increases (e.g., maintaining more attributes), providing the 3DSG as-is to an LLM-based planner quickly becomes infeasible due to input token count limits and attentional biases present in LLMs. Inspired by the successes of Retrieval-Augmented Generation (RAG) methods that retrieve query-relevant document chunks for LLM question and answering, we adapt the paradigm for our embodied domain. Specifically, we propose a 3D scene subgraph retrieval framework, called EmbodiedRAG, that we augment an LLM-based planner with for executing natural language robotic tasks. Notably, our retrieved subgraphs adapt to changes in the environment as well as changes in task-relevancy as the robot executes its plan. We demonstrate EmbodiedRAG's ability to significantly reduce input token counts (by an order of magnitude) and planning time (up to 70% reduction in average time per planning step) while improving success rates on AI2Thor simulated household tasks with a single-arm, mobile manipulator. Additionally, we implement EmbodiedRAG on a quadruped with a manipulator to highlight the performance benefits for robot deployment at the edge in real environments.

[Arxiv](https://arxiv.org/abs/2410.23968)