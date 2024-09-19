# 借助多智能体思维树验证器，提升 LLM 的推理能力

发布时间：2024年09月17日

`Agent` `人工智能`

> Improving LLM Reasoning with Multi-Agent Tree-of-Thought Validator Agent

# 摘要

> 多代理策略通过在问题解决过程中分配专门角色，已成为提升大型语言模型 (LLM) 推理能力的有效途径。同时，思维树 (ToT) 方法通过探索多样推理路径，在复杂问答任务中展现出提升推理能力的潜力。然而，多代理推理中的“推理者”代理对推理路径的探索往往浅尝辄止。虽然 ToT 策略能缓解这一问题，但也可能生成有缺陷的推理分支，影响最终答案的可信度。为此，我们提出了一种新方法，结合基于 ToT 的推理者代理和思维验证者代理。多个推理者代理并行操作，使用 ToT 探索多样推理路径。思维验证者随后严格审查这些路径，仅在推理有效时采纳推理者的结论。这种方法通过排除有缺陷的推理路径，实现了更强大的投票策略，显著提升了系统处理需要系统化和可信推理任务的能力。在 GSM8K 数据集上的评估显示，我们的方法相比现有技术表现更优，平均超过四种 LLM 的标准 ToT 策略 5.6%。

> Multi-agent strategies have emerged as a promising approach to enhance the reasoning abilities of Large Language Models (LLMs) by assigning specialized roles in the problem-solving process. Concurrently, Tree of Thoughts (ToT) methods have shown potential in improving reasoning for complex question-answering tasks by exploring diverse reasoning paths. A critical limitation in multi-agent reasoning is the 'Reasoner' agent's shallow exploration of reasoning paths. While ToT strategies could help mitigate this problem, they may generate flawed reasoning branches, which could harm the trustworthiness of the final answer. To leverage the strengths of both multi-agent reasoning and ToT strategies, we introduce a novel approach combining ToT-based Reasoner agents with a Thought Validator agent. Multiple Reasoner agents operate in parallel, employing ToT to explore diverse reasoning paths. The Thought Validator then scrutinizes these paths, considering a Reasoner's conclusion only if its reasoning is valid. This method enables a more robust voting strategy by discarding faulty reasoning paths, enhancing the system's ability to tackle tasks requiring systematic and trustworthy reasoning. Our method demonstrates superior performance compared to existing techniques when evaluated on the GSM8K dataset, outperforming the standard ToT strategy by an average 5.6\% across four LLMs.

[Arxiv](https://arxiv.org/abs/2409.11527)