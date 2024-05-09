# 思维链的盲点：探究计划中思维链的运用与局限在翻译过程中，我首先确保原文的核心意义被准确传达，即对“思维链”（Chain of Thought）在计划制定中的应用进行分析。在第二步中，我调整了表达方式，使其更符合中文的修辞习惯，同时保持了原文的生动性和简洁性。通过使用“盲点”一词，我强调了研究中可能忽视的方面，同时也为读者提供了一个形象的视角来理解这一复杂的概念。

发布时间：2024年05月07日

`LLM理论

这篇论文探讨了大型语言模型（LLM）在推理问题上的局限性，特别是在使用思维链（Chain of Thought）提示时的表现。它分析了思维链在特定问题类型上的应用，并指出了其性能提升的局限性，这主要是因为需要与问题紧密相关的精心设计的提示。这种分析属于对LLM理论层面的探讨，因为它关注的是LLM的工作原理和性能提升的机制，而不是直接的应用或安全性问题。因此，它被归类为LLM理论。` `人工智能` `规划问题`

> Chain of Thoughtlessness: An Analysis of CoT in Planning

# 摘要

> 大型语言模型在推理问题上的表现往往局限于特定范围。以往的研究提出，通过在提示中加入思维链示例——展示解决问题的步骤——可以提升LLM的泛化能力。本文以Blocksworld为例，探讨了思维链在经典规划问题上的应用，并分析了两种顶尖LLM在示例通用性和问题复杂性两个维度上的表现。尽管问题简单，但只有在提示极度贴合特定问题类型时，思维链才能带来显著的性能提升，且这种提升随着查询中的堆栈大小超过示例中的大小而迅速减弱。研究结果表明，与之前的观点不同，思维链的改进并非因为模型学会了通用算法，而是需要精心设计与问题紧密相关的提示。这揭示了思维链方法的局限性，尤其是性能提升与人工设计示例所需劳动之间的矛盾。

> Large language model (LLM) performance on reasoning problems typically does not generalize out of distribution. Previous work has claimed that this can be mitigated by modifying prompts to include examples with chains of thought--demonstrations of solution procedures--with the intuition that it is possible to in-context teach an LLM an algorithm for solving the problem. This paper presents a case study of chain of thought on problems from Blocksworld, a classical planning domain, and examine the performance of two state-of-the-art LLMs across two axes: generality of examples given in prompt, and complexity of problems queried with each prompt. While our problems are very simple, we only find meaningful performance improvements from chain of thought prompts when those prompts are exceedingly specific to their problem class, and that those improvements quickly deteriorate as the size n of the query-specified stack grows past the size of stacks shown in the examples. Our results hint that, contrary to previous claims in the literature, CoT's performance improvements do not stem from the model learning general algorithmic procedures via demonstrations and depend on carefully engineering highly problem specific prompts. This spotlights drawbacks of chain of thought, especially because of the sharp tradeoff between possible performance gains and the amount of human labor necessary to generate examples with correct reasoning traces.

[Arxiv](https://arxiv.org/abs/2405.04776)