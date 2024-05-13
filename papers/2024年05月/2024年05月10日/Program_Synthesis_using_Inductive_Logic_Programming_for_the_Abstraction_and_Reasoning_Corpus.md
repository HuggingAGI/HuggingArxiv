# 归纳逻辑编程助力程序合成，探索抽象与推理语料库之奥秘

发布时间：2024年05月10日

`Agent

这篇论文探讨了如何利用归纳逻辑编程（ILP）和特定领域语言（DSL）来解决抽象与推理语料库（ARC）这一通用人工智能挑战，这是一个关于开发能够进行推理和泛化的智能系统的问题。虽然它涉及大型语言模型（LLMs），但重点在于构建一个能够解决特定问题的Agent，即一个能够通过ILP和DSL进行程序合成的系统。因此，这篇论文更符合Agent分类，因为它关注的是创建一个能够执行特定任务的智能实体，而不是LLM的理论研究或应用。` `人工智能`

> Program Synthesis using Inductive Logic Programming for the Abstraction and Reasoning Corpus

# 摘要

> 抽象与推理语料库（ARC）作为一项通用人工智能挑战，至今仍未被任何机器学习方法，包括大型语言模型（LLMs）所攻克。它对泛化与推理能力有着极高的要求，而这恰恰是神经网络系统的短板。本研究提出了一种基于归纳逻辑编程（ILP）的程序合成系统，ILP属于符号人工智能的范畴，专门针对ARC难题。我们精心设计了一种简洁的特定领域语言（DSL），它聚焦于ARC相关的一系列对象中心抽象。这种DSL构成了ILP生成逻辑程序的基础，为我们的系统赋予了推理能力。该系统具备泛化至新任务的潜力，因为ILP能从有限的示例中提炼出逻辑程序，例如ARC中的输入-输出网格示例对。这些逻辑程序能够创造出输出网格中的对象，而这些对象的组合则能编织成一个完整的程序，实现从输入网格到输出网格的转换。我们随机挑选了ARC中一些仅需少量对象原语的任务，并展示了即使仅依赖这些原语，我们的系统也能应对需要多样化推理的任务。

> The Abstraction and Reasoning Corpus (ARC) is a general artificial intelligence benchmark that is currently unsolvable by any Machine Learning method, including Large Language Models (LLMs). It demands strong generalization and reasoning capabilities which are known to be weaknesses of Neural Network based systems. In this work, we propose a Program Synthesis system that uses Inductive Logic Programming (ILP), a branch of Symbolic AI, to solve ARC. We have manually defined a simple Domain Specific Language (DSL) that corresponds to a small set of object-centric abstractions relevant to ARC. This is the Background Knowledge used by ILP to create Logic Programs that provide reasoning capabilities to our system. The full system is capable of generalize to unseen tasks, since ILP can create Logic Program(s) from few examples, in the case of ARC: pairs of Input-Output grids examples for each task. These Logic Programs are able to generate Objects present in the Output grid and the combination of these can form a complete program that transforms an Input grid into an Output grid. We randomly chose some tasks from ARC that dont require more than the small number of the Object primitives we implemented and show that given only these, our system can solve tasks that require each, such different reasoning.

[Arxiv](https://arxiv.org/abs/2405.06399)