# 确定性字符串机器的运算效率分析

发布时间：2024年05月09日

`Agent

这篇论文主要讨论了自动机的构建和运行时间复杂性，提出了一种新的组合语言和字符串图的概念来更准确地映射自动机的描述复杂性。这种工作更偏向于智能体（Agent）的设计和优化，因为它关注的是自动机如何在特定环境中学习和操作，以及如何通过字符串机器来模拟需要变量内存的计算。因此，它属于Agent分类。` `自动机理论` `计算复杂性`

> Time complexity for deterministic string machines

# 摘要

> 以往学习自动机环境的方法，其复杂度随状态数增长，即便对于描述简短的正则表达式，状态数也可能剧增。为此，我们提出了一种组合语言，通过字符串图在特定类别间转换，构建自动机，更准确地映射了自动机的描述复杂性。我们通过在过滤集上丰富的类别上施加复杂性约束，定义了这一框架，并证明了有限状态空间上确定性操作的变换子集的运行时间和表达性。这些字符串图，即“字符串机器”，是类别中的态射，能在运行时生成新的字符串机器，模拟需变量内存的计算。我们证明了这些字符串机器的运行时间保证多项式时间，有助于制定包含运行时间复杂性的字符串机器的复杂性约束。

> Algorithms which learn environments represented by automata in the past have had complexity scaling with the number of states in the automaton, which can be exponentially large even for automata recognizing regular expressions with a small description length. We thus formalize a compositional language that can construct automata as transformations between certain types of category, representable as string diagrams, which better reflects the description complexity of various automata. We define complexity constraints on this framework by having them operate on categories enriched over filtered sets, and using these constraints, we prove elementary results on the runtime and expressivity of a subset of these transformations which operate deterministically on finite state spaces. These string diagrams, or "string machines," are themselves morphisms in a category, so it is possible for string machines to create other string machines in runtime to model computations which take more than constant memory. We prove sufficient conditions for polynomial runtime guarantees on these, which can help develop complexity constraints on string machines which also encapsulate runtime complexity.

[Arxiv](https://arxiv.org/abs/2405.06043)