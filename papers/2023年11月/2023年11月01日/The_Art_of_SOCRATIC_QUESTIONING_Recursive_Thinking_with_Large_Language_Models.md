# 探索苏格拉底式提问的艺术：大型语言模型中的递归思维之旅

发布时间：2023年11月01日

`LLM应用

理由：这篇论文介绍了一种新的方法——苏格拉底式提问，用于改进大型语言模型（LLM）在复杂推理任务中的表现。这种方法模仿人类的递归思维过程，通过分解问题为子问题并逐步解答来解决原问题。论文通过实验验证了该方法在多个复杂推理任务上的有效性，并进行了定性分析以展示其与人类思维过程的一致性。因此，这篇论文属于LLM应用类别，因为它专注于改进和应用LLM技术来解决实际问题。` `人工智能`

> The Art of SOCRATIC QUESTIONING: Recursive Thinking with Large Language Models

# 摘要

> 思维链（CoT）提示通过生成中间步骤，使大型语言模型能够解决复杂的推理问题。但其单次和顺序的生成特性导致对初始决策的依赖过重，早期错误会累积影响最终答案。与此不同，人类在面对复杂推理时采用递归思维，将问题分解为可管理的子问题，并逐步整合答案以解决原问题。受此启发，我们提出了苏格拉底式提问，一种模仿递归思维的分而治之算法。该方法通过大型语言模型提出并解答子问题，直至积累足够信息解决原问题。与CoT相比，苏格拉底式提问更明确地引导思维路径，促进有效递归思维，并对思维过程中的错误更具抵抗力。在MMLU、MATH、LogiQA及视觉问答等多个复杂推理任务上的实验表明，该方法显著优于CoT和思维树等现有技术。定性分析显示，苏格拉底式提问引发的推理步骤与人类递归解决复杂问题的思维过程高度一致。

> Chain-of-Thought (CoT) prompting enables large language models to solve complex reasoning problems by generating intermediate steps. However, confined by its inherent single-pass and sequential generation process, CoT heavily relies on the initial decisions, causing errors in early steps to accumulate and impact the final answers. In contrast, humans adopt recursive thinking when tackling complex reasoning problems, i.e., iteratively breaking the original problem into approachable sub-problems and aggregating their answers to resolve the original one. Inspired by the human cognitive process, we propose SOCRATIC QUESTIONING, a divide-and-conquer style algorithm that mimics the recursive thinking process. Specifically, SOCRATIC QUESTIONING leverages large language models to raise and answer sub-questions until collecting enough information to tackle the original question. Unlike CoT, SOCRATIC QUESTIONING explicitly navigates the thinking space, stimulates effective recursive thinking, and is more robust towards errors in the thinking process. Extensive experiments on several complex reasoning tasks, including MMLU, MATH, LogiQA, and visual question-answering demonstrate significant performance improvements over the state-of-the-art prompting methods, such as CoT, and Tree-of-Thought. The qualitative analysis clearly shows that the intermediate reasoning steps elicited by SOCRATIC QUESTIONING are similar to humans' recursively thinking process of complex reasoning problems.

[Arxiv](https://arxiv.org/abs/2305.14999)