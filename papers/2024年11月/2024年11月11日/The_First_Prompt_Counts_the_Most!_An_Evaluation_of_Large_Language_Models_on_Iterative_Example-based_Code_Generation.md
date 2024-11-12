# 第一个提示最为重要！对大型语言模型在基于迭代示例的代码生成方面的评估

发布时间：2024年11月11日

`LLM应用` `代码生成`

> The First Prompt Counts the Most! An Evaluation of Large Language Models on Iterative Example-based Code Generation

# 摘要

> 大型语言模型（LLM）在代码生成方面的能力，特别是从自然语言描述中实现目标功能的能力，已经得到了广泛的研究。作为自然语言的一种替代形式，输入输出示例（I/O 示例）提供了一种易于理解、明确且灵活的方式来描述功能，但 I/O 示例的多样性、稀疏性和不完整性也给理解和实现需求带来了挑战。因此，从输入输出示例生成代码（即基于示例的代码生成）提供了一个新的视角，使我们能够评估 LLM 从有限信息中推断目标功能以及处理新形式需求的能力。然而，关于 LLM 在基于示例的代码生成方面的相关研究在很大程度上仍未得到探索。为了填补这一空白，本文对使用 LLM 的基于示例的代码生成进行了首次全面研究。为了解决 I/O 示例不完整导致的不正确性，我们采用了一个迭代评估框架，并将基于示例的代码生成的目标形式化为两个连续的子目标：生成符合给定示例的代码，以及生成从（迭代地）给定示例中成功实现目标功能的代码。我们使用一个包含 168 种不同目标功能的新基准评估了六个最先进的 LLM。结果表明，当使用迭代的 I/O 示例而不是自然语言描述需求时，LLM 的得分下降了 60%以上，这表明基于示例的代码生成对于所评估的 LLM 仍然具有挑战性。更有趣的是，绝大多数（甚至超过 95%）成功实现的功能是在第一轮迭代中实现的，这表明 LLM 难以有效地利用迭代补充的需求。

> The capabilities of Large Language Models (LLMs) in code generation, particularly for implementing target functionalities from natural language descriptions, have been extensively studied. As an alternative form of natural language, input-output examples (I/O examples) provide an accessible, unambiguous, and flexible way to describe functionalities, but the diversity, sparseness, and incompleteness of I/O examples also place challenges on understanding and implementing requirements. Therefore, generating code from input-output examples (i.e., example-based code generation) provides a new perspective, allowing us to evaluate LLMs' capability to infer target functionalities from limited information and to process new-form requirements. However, related research about LLMs in example-based code generation remains largely unexplored. To fill this gap, this paper presents the first comprehensive study on example-based code generation using LLMs. To address the incorrectness caused by the incompleteness of I/O examples, we adopt an iterative evaluation framework and formalize the objective of example-based code generation as two sequential sub-objectives: generating code conforming to given examples and generating code that successfully implements the target functionalities from (iteratively) given examples. We assess six state-of-the-art LLMs using a new benchmark of 168 diverse target functionalities. The results demonstrate that when requirements were described using iterative I/O examples rather than natural language, the LLMs' score decreased by over 60%, indicating that example-based code generation remains challenging for the evaluated LLMs. More interestingly, the vast majority (even over 95%) of successfully implemented functionalities are achieved in the first round of iterations, suggesting that the LLMs struggle to effectively utilize the iteratively supplemented requirements.

[Arxiv](https://arxiv.org/abs/2411.06774)