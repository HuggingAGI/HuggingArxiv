# 一种灵活并行的Lambda演算，旨在优化大型语言模型的组合效率

发布时间：2024年05月18日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在解码技术上的挑战，并提出了一种新的通用lambda演算方法来实现自动并行处理，以提高解码效率。这种方法特别强调了并行化和批处理的自动化，以及在保持语言简洁性的同时实现高效的外部调用。论文通过EPIC框架的开发和在多个机器学习领域的应用案例展示了其方法的广泛适用性和性能优势。因此，这篇论文属于LLM应用类别，因为它专注于改进LLM的实际应用技术，而不是理论研究。` `机器学习` `软件开发`

> An Opportunistically Parallel Lambda Calculus for Performant Composition of Large Language Models

# 摘要

> 大型语言模型（LLMs）在众多任务中表现出色，但仍面临虚构事实和算术难题等挑战。近期研究利用复杂解码技术克服了这些限制，但高效解码依赖于并行化和批处理，这对开发者而言是一大难题。我们的观察揭示了两个关键点：1）现有方法虽为特定领域设计，但缺乏通用性和组合性；2）LLM程序本质上是纯的，所有操作均可交换。基于此，我们创新了一种通用lambda演算，能自动并行处理LLM交互，无需用户介入。这种演算的关键在于一种“机会主义”评估策略，它并行处理程序的独立部分，并尽可能迅速地执行外部黑盒调用，即便在等待其他外部调用返回时亦如此。为了保持语言的简洁并确保评估的一致性，我们通过Church编码在语言内部实现了控制流和循环结构。我们开发的EPIC框架紧密嵌入并兼容Python，通过三个机器学习领域的案例展示了其广泛应用和高效性能：思维树（结合经典搜索的LLMs）、嵌套工具使用和受限解码。实验结果显示，机会主义评估相比顺序评估提供了1.5倍至4.8倍的加速，同时允许开发者编写简洁且可组合的代码，无需手动并行或批处理。

> Large language models (LLMs) have shown impressive results at a wide-range of tasks. However, they have limitations, such as hallucinating facts and struggling with arithmetic. Recent work has addressed these issues with sophisticated decoding techniques. However, performant decoding, particularly for sophisticated techniques, relies crucially on parallelization and batching, which are difficult for developers.
  We make two observations: 1) existing approaches are high-level domain-specific languages for gluing expensive black-box calls, but are not general or compositional; 2) LLM programs are essentially pure (all effects commute). Guided by these observations, we develop a novel, general-purpose lambda calculus for automatically parallelizing a wide-range of LLM interactions, without user intervention. The key difference versus standard lambda calculus is a novel "opportunistic" evaluation strategy, which steps independent parts of a program in parallel, dispatching black-box external calls as eagerly as possible, even while data-independent parts of the program are waiting for their own external calls to return. To maintain the simplicity of the language and to ensure uniformity of opportunistic evaluation, control-flow and looping constructs are implemented in-language, via Church encodings.
  We implement this approach in a framework called EPIC, embedded in--and interoperating closely with--Python. We demonstrate its versatility and performance with three case studies drawn from the machine learning literature: Tree-of-Thoughts (LLMs embedded in classic search procedures), nested tool use, and constrained decoding. Our experiments show that opportunistic evaluation offers a $1.5\times$ to $4.8\times$ speedup over sequential evaluation, while still allowing practitioners to write straightforward and composable programs, without any manual parallelism or batching.

[Arxiv](https://arxiv.org/abs/2405.11361)