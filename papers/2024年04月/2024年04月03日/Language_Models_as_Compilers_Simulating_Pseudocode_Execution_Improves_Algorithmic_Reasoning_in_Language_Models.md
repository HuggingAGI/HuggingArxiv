# 将语言模型视作编译器，通过模拟伪代码的执行，我们能够显著提升模型在算法推理上的能力。

发布时间：2024年04月03日

`LLM理论` `算法推理` `编程语言`

> Language Models as Compilers: Simulating Pseudocode Execution Improves Algorithmic Reasoning in Language Models

# 摘要

> 算法推理是解构问题背后的复杂模式并逐步推导至答案的能力，这对大型语言模型（LLMs）而言颇具挑战，尽管它们在其他推理领域已展现潜力。近期研究开始借鉴编程语言（如Python）的严格语法，用以表述特定问题/实例的解决逻辑（即思维程序）。但在单次推理调用中即时编写出正确逻辑的可执行代码并非易事，且特定实例的代码难以复用于其他同类问题。本文介绍了Think-and-Execute框架，将语言模型的推理分为两步：首先，在思考阶段，我们找出适用于解决特定任务的所有实例的任务级逻辑，并用伪代码表达；其次，在执行阶段，我们将伪代码针对每个实例进行定制，并模拟执行过程。通过七项算法推理任务的广泛实验验证了该框架的有效性，相较于其他特定实例推理方法，我们的方法在提升语言模型推理能力方面表现更佳，这证明了发掘任务级逻辑的重要性。同时，我们发现伪代码相较于自然语言，能更有效地引导模型的推理过程，即便模型原本是针对自然语言指令进行训练的。

> Algorithmic reasoning refers to the ability to understand the complex patterns behind the problem and decompose them into a sequence of reasoning steps towards the solution. Such nature of algorithmic reasoning makes it a challenge for large language models (LLMs), even though they have demonstrated promising performance in other reasoning tasks. Within this context, some recent studies use programming languages (e.g., Python) to express the necessary logic for solving a given instance/question (e.g., Program-of-Thought) as inspired by their strict and precise syntaxes. However, it is non-trivial to write an executable code that expresses the correct logic on the fly within a single inference call. Also, the code generated specifically for an instance cannot be reused for others, even if they are from the same task and might require identical logic to solve. This paper presents Think-and-Execute, a novel framework that decomposes the reasoning process of language models into two steps. (1) In Think, we discover a task-level logic that is shared across all instances for solving a given task and then express the logic with pseudocode; (2) In Execute, we further tailor the generated pseudocode to each instance and simulate the execution of the code. With extensive experiments on seven algorithmic reasoning tasks, we demonstrate the effectiveness of Think-and-Execute. Our approach better improves LMs' reasoning compared to several strong baselines performing instance-specific reasoning (e.g., CoT and PoT), suggesting the helpfulness of discovering task-level logic. Also, we show that compared to natural language, pseudocode can better guide the reasoning of LMs, even though they are trained to follow natural language instructions.

[Arxiv](https://arxiv.org/abs/2404.02575)