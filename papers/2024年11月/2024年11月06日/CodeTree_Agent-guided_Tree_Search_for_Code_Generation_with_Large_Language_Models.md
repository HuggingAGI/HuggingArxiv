# CodeTree：使用大型语言模型进行代码生成的代理引导树搜索

发布时间：2024年11月06日

`Agent` `代码生成` `软件开发`

> CodeTree: Agent-guided Tree Search for Code Generation with Large Language Models

# 摘要

> 在大量的代码和文本数据上进行预训练，大型语言模型（LLMs）在执行代码生成任务方面已经取得了显著成就。通过额外的基于执行的反馈，这些模型可以作为具有自主完善和改进生成代码能力的代理。然而，在具有极大搜索空间的具有挑战性的编码任务上，当前的代理方法在多阶段规划、生成和调试方面仍然存在困难。为了解决这个问题，我们提出了 CodeTree，这是一个用于 LLM 代理在代码生成过程的不同阶段有效探索搜索空间的框架。具体来说，我们采用了统一的树结构来明确探索不同的编码策略，生成相应的编码解决方案，并随后改进这些解决方案。在每个阶段，探索过程的关键决策（排名、终止、扩展）都由基于环境执行的反馈和 LLM 代理生成的反馈所引导。我们在 7 个代码生成基准上对 CodeTree 进行了全面评估，并证明了 CodeTree 相对于强大的基线有显著的性能提升。使用 GPT-4o 作为基础模型，我们在 HumanEval 上始终取得了 95.1 的顶级结果，在 MBPP 上取得了 98.7 的成绩，在 CodeContests 上取得了 43.0 的成绩。在具有挑战性的 SWEBench 基准上，我们的方法带来了显著的性能提升。

> Pre-trained on massive amounts of code and text data, large language models (LLMs) have demonstrated remarkable achievements in performing code generation tasks. With additional execution-based feedback, these models can act as agents with capabilities to self-refine and improve generated code autonomously. However, on challenging coding tasks with extremely large search space, current agentic approaches still struggle with multi-stage planning, generating, and debugging. To address this problem, we propose CodeTree, a framework for LLM agents to efficiently explore the search space in different stages of the code generation process. Specifically, we adopted a unified tree structure to explicitly explore different coding strategies, generate corresponding coding solutions, and subsequently refine the solutions. In each stage, critical decision-making (ranking, termination, expanding) of the exploration process is guided by both the environmental execution-based feedback and LLM-agent-generated feedback. We comprehensively evaluated CodeTree on 7 code generation benchmarks and demonstrated the significant performance gains of CodeTree against strong baselines. Using GPT-4o as the base model, we consistently achieved top results of 95.1 on HumanEval, 98.7 on MBPP, and 43.0 on CodeContests. On the challenging SWEBench benchmark, our approach led to significant performance gains.

[Arxiv](https://arxiv.org/abs/2411.04329)