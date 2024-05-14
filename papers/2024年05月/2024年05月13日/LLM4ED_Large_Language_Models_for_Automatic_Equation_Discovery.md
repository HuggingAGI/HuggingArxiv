# 大型语言模型助力自动方程发现：LLM4ED在这项研究中，我们探索了大型语言模型（LLM）在自动方程发现（AED）领域的应用，旨在利用LLM的强大能力来辅助科学家和工程师在复杂系统中发现潜在的数学模型。通过深入分析LLM在处理数学表达式和逻辑推理方面的优势，我们提出了一种新颖的框架，该框架能够有效地从数据中提取规律，并生成描述这些规律的数学方程。我们的方法不仅提高了AED的自动化水平，还为解决实际问题提供了新的视角。

发布时间：2024年05月13日

`LLM应用

这篇论文探讨了如何利用大型语言模型（LLMs）来自动发现数据中的物理定律，即方程发现。它提出了一种创新的框架，通过自然语言提示引导LLMs进行这一过程，并采用了特定的优化策略来提高方程发现的效率和准确性。这种方法的应用性质明显，因为它旨在解决实际问题，即从数据中提取科学知识，而不是专注于LLMs的理论研究或Agent的设计与实现。因此，它属于LLM应用类别。` `科学研究` `物理定律发现`

> LLM4ED: Large Language Models for Automatic Equation Discovery

# 摘要

> 方程发现，这一旨在从数据中揭示物理定律的研究领域，已成为科学探索的前沿。尽管基于符号数学的方法取得了显著进步，但它们往往依赖于复杂算法的设计与实施。本文提出了一种创新框架，通过自然语言提示引导大型语言模型（LLMs）自动挖掘数据中的控制方程。我们首先利用LLMs的生成能力，创造出多样化的方程表达式，随后依据实际观测对其进行评估。在优化过程中，我们采用了两种交替迭代的策略：一是将LLMs作为黑盒优化器，利用历史样本及其表现进行方程的自我完善；二是指导LLMs执行进化操作，以实现全局搜索。实验涵盖了偏微分方程和常微分方程，结果显示我们的框架能够有效揭示多种非线性动态系统中的物理定律。与顶尖模型的对比进一步验证了其稳定性和实用性。这一框架极大地简化了方程发现技术的学习和应用，展现了LLMs在知识发现领域的巨大潜力。

> Equation discovery is aimed at directly extracting physical laws from data and has emerged as a pivotal research domain. Previous methods based on symbolic mathematics have achieved substantial advancements, but often require the design of implementation of complex algorithms. In this paper, we introduce a new framework that utilizes natural language-based prompts to guide large language models (LLMs) in automatically mining governing equations from data. Specifically, we first utilize the generation capability of LLMs to generate diverse equations in string form, and then evaluate the generated equations based on observations. In the optimization phase, we propose two alternately iterated strategies to optimize generated equations collaboratively. The first strategy is to take LLMs as a black-box optimizer and achieve equation self-improvement based on historical samples and their performance. The second strategy is to instruct LLMs to perform evolutionary operators for global search. Experiments are extensively conducted on both partial differential equations and ordinary differential equations. Results demonstrate that our framework can discover effective equations to reveal the underlying physical laws under various nonlinear dynamic systems. Further comparisons are made with state-of-the-art models, demonstrating good stability and usability. Our framework substantially lowers the barriers to learning and applying equation discovery techniques, demonstrating the application potential of LLMs in the field of knowledge discovery.

[Arxiv](https://arxiv.org/abs/2405.07761)