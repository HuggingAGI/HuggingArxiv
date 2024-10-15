# 思考型 LLM：通过思维生成实现通用指令跟随

发布时间：2024年10月14日

`LLM理论`

> Thinking LLMs: General Instruction Following with Thought Generation

# 摘要

> 摘要：LLM 通常被训练成像人类专家一样回答问题或遵循指令，但在标准对齐框架中，它们缺乏回答前的显式思考能力。思考对于需要推理和规划的复杂问题至关重要，且适用于任何任务。我们提出了一种训练方法，使现有 LLM 具备这种思考能力，无需额外人类数据。通过迭代搜索和优化过程，模型在无直接监督下学习思考。每个指令的思维候选者由评判模型评分，仅评估其响应，并通过偏好优化进行优化。实验表明，该方法在 AlpacaEval 和 Arena-Hard 上表现优异，且在营销、健康和一般知识等非推理任务中也有显著提升，超越了传统推理和问题解决任务。

> 
Abstract:LLMs are typically trained to answer user questions or follow instructions similarly to how human experts respond. However, in the standard alignment framework they lack the basic ability of explicit thinking before answering. Thinking is important for complex questions that require reasoning and planning -- but can be applied to any task. We propose a training method for equipping existing LLMs with such thinking abilities for general instruction following without use of additional human data. We achieve this by an iterative search and optimization procedure that explores the space of possible thought generations, allowing the model to learn how to think without direct supervision. For each instruction, the thought candidates are scored using a judge model to evaluate their responses only, and then optimized via preference optimization. We show that this procedure leads to superior performance on AlpacaEval and Arena-Hard, and shows gains from thinking on non-reasoning categories such as marketing, health and general knowledge, in addition to more traditional reasoning & problem-solving tasks.
    

[Arxiv](https://arxiv.org/pdf/2410.10630)