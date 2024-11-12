# UTMath：通过推理到编码思想的单元测试进行数学评估

发布时间：2024年11月11日

`LLM应用` `人工智能`

> UTMath: Math Evaluation with Unit Test via Reasoning-to-Coding Thoughts

# 摘要

> 数学推理能力的评估对于推进通用人工智能（AGI）至关重要。虽然大型语言模型（LLMs）在解决数学问题方面表现出色，但现有的基准测试，如 GSM8K 和 MATH 存在局限性，包括问题定义狭窄、特定数字以及依赖预定规则，这些都阻碍了对推理和适应性的准确评估。本文介绍了 UTMath 基准，它通过广泛的单元测试对模型进行了稳健的评估。它涵盖了 9 个数学领域的 1053 个问题，每个问题有超过 68 个测试用例。我们提出了一个受软件开发中单元测试启发的创新评估框架，重点关注结果的准确性和可靠性。此外，我们引入了思维推理到编码（RCoT）方法，鼓励 LLMs 在生成代码之前进行明确的推理，从而生成更高级的解决方案并提高性能。此外，我们不仅发布了 UTMath 基准，还发布了 UTMath-Train 训练数据集（超过 70,000 个样本），以支持社区进一步探索数学推理。

> The evaluation of mathematical reasoning capabilities is essential for advancing Artificial General Intelligence (AGI). While Large Language Models (LLMs) have shown impressive performance in solving mathematical problems, existing benchmarks such as GSM8K and MATH present limitations, including narrow problem definitions with specific numbers and reliance on predetermined rules that hinder accurate assessments of reasoning and adaptability. This paper introduces the UTMath Benchmark, which robustly evaluates the models through extensive unit tests. It consists of 1,053 problems across 9 mathematical domains, with over 68 test cases per problem.We propose an innovative evaluation framework inspired by unit testing in software development, focusing on both accuracy and reliability of results. Furthermore, we introduce the Reasoning-to-Coding of Thoughts (RCoT) approach, which encourages LLMs to perform explicit reasoning before generating code, leading to generating more advanced solution and improved performance. Furthermore, we are releasing not only the UTMath benchmark but also the UTMath-Train training dataset (more than 70k samples), to support the community in further exploring mathematical reasoning.

[Arxiv](https://arxiv.org/abs/2411.07240)