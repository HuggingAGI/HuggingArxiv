# 评估 ChatGPT-3.5 解决不同复杂程度编码问题的效率：一项实证研究

发布时间：2024年11月11日

`LLM应用` `软件开发` `程序语言`

> Evaluating ChatGPT-3.5 Efficiency in Solving Coding Problems of Different Complexity Levels: An Empirical Analysis

# 摘要

> ChatGPT 及其他大型语言模型（LLMs）有望凭借依据程序规范自动生成代码来变革软件开发。我们对 ChatGPT 的 GPT-3.5-turbo 模型在 LeetCode 上的表现予以评估，LeetCode 是个热门平台，设有用于技术面试练习的算法编码挑战，涵盖了简单、中等和困难这三个难度级别。我们检验了三个主要假设。其一，ChatGPT 解决的问题数量随难度上升而减少（假设 1）。其二，提示工程能提升 ChatGPT 的性能，在较简单的问题上提升幅度更大，在较难的问题上收益递减（假设 2）。其三，ChatGPT 在 Python、Java 和 C++ 等流行语言中的表现优于 Elixir、Erlang 和 Racket 等不太常见的语言（假设 3）。为探究这些假设，我们运用 Python 脚本开展自动实验，生成提示以指示 ChatGPT 生成 Python 解决方案。这些解决方案被存储并手动提交至 LeetCode 以检验其正确性。就假设 1 而言，结果表明 GPT-3.5-turbo 模型成功解决了 92%的简单问题、79%的中等问题和 51%的困难问题。对于假设 2，提示工程带来了改进：思维链提示提升了 14 - 29%，在第二个反馈提示中提供失败的测试用例提升了 38 - 60%，切换到 GPT-4 提升了 33 - 58%。从 ChatGPT 用 Python 解决的问题的随机子集中来看，它在 Java 中也解决了 78%，在 C++ 中解决了 50%，在 Elixir、Erlang 或 Racket 中均未解决。这些发现总体上验证了这三个假设。

> ChatGPT and other large language models (LLMs) promise to revolutionize software development by automatically generating code from program specifications. We assess the performance of ChatGPT's GPT-3.5-turbo model on LeetCode, a popular platform with algorithmic coding challenges for technical interview practice, across three difficulty levels: easy, medium, and hard. We test three main hypotheses. First, ChatGPT solves fewer problems as difficulty rises (Hypothesis 1). Second, prompt engineering improves ChatGPT's performance, with greater gains on easier problems and diminishing returns on harder ones (Hypothesis 2). Third, ChatGPT performs better in popular languages like Python, Java, and C++ than in less common ones like Elixir, Erlang, and Racket (Hypothesis 3). To investigate these hypotheses, we conduct automated experiments using Python scripts to generate prompts that instruct ChatGPT to create Python solutions. These solutions are stored and manually submitted on LeetCode to check their correctness. For Hypothesis 1, results show the GPT-3.5-turbo model successfully solves 92% of easy, 79% of medium, and 51% of hard problems. For Hypothesis 2, prompt engineering yields improvements: 14-29% for Chain of Thought Prompting, 38-60% by providing failed test cases in a second feedback prompt, and 33-58% by switching to GPT-4. From a random subset of problems ChatGPT solved in Python, it also solved 78% in Java, 50% in C++, and none in Elixir, Erlang, or Racket. These findings generally validate all three hypotheses.

[Arxiv](https://arxiv.org/abs/2411.07529)