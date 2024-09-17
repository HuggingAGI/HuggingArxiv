# 思维图谱探析

发布时间：2024年09月16日

`LLM理论` `人工智能`

> On the Diagram of Thought

# 摘要

> 我们推出了思维图（DoT），一个将大型语言模型（LLM）中的迭代推理建模为单个模型内有向无环图（DAG）构建的框架。与传统方法不同，DoT将命题、批评、改进和验证组织成连贯的DAG结构，使模型在保持逻辑一致性的同时探索复杂推理路径。每个节点对应一个已被提出、批评、改进或验证的命题，使LLM通过自然语言反馈迭代改进推理。通过角色特定标记的自回归下一标记预测，DoT促进提出想法和批判性评估之间的无缝过渡，提供更丰富的反馈。我们还使用拓扑理论正式化了DoT框架，确保推理过程中的逻辑一致性和健全性。这种方法增强了单个LLM的训练和推理过程，无需多个模型或外部控制机制。DoT为设计下一代推理专用模型提供了概念框架，强调训练效率、强大推理能力和理论基础。代码可在https://github.com/diagram-of-thought/diagram-of-thought获取。

> We introduce Diagram of Thought (DoT), a framework that models iterative reasoning in large language models (LLMs) as the construction of a directed acyclic graph (DAG) within a single model. Unlike traditional approaches that represent reasoning as linear chains or trees, DoT organizes propositions, critiques, refinements, and verifications into a cohesive DAG structure, allowing the model to explore complex reasoning pathways while maintaining logical consistency. Each node in the diagram corresponds to a proposition that has been proposed, critiqued, refined, or verified, enabling the LLM to iteratively improve its reasoning through natural language feedback. By leveraging auto-regressive next-token prediction with role-specific tokens, DoT facilitates seamless transitions between proposing ideas and critically evaluating them, providing richer feedback than binary signals. Furthermore, we formalize the DoT framework using Topos Theory, providing a mathematical foundation that ensures logical consistency and soundness in the reasoning process. This approach enhances both the training and inference processes within a single LLM, eliminating the need for multiple models or external control mechanisms. DoT offers a conceptual framework for designing next-generation reasoning-specialized models, emphasizing training efficiency, robust reasoning capabilities, and theoretical grounding. The code is available at https://github.com/diagram-of-thought/diagram-of-thought.

[Arxiv](https://arxiv.org/abs/2409.10038)