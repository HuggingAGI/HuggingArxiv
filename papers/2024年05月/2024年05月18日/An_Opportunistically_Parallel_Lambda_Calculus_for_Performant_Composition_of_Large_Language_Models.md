# 一种机会主义并行的Lambda演算，旨在高效组合大型语言模型，提升性能。

发布时间：2024年05月18日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLMs）在解码技术上的应用，特别是在并行化和批处理方面的挑战。论文提出了一种新的方法——通用lambda演算，用于自动并行化LLM交互，并通过EPIC框架展示了其在实际机器学习案例中的应用。这些内容主要关注LLM在实际应用中的技术改进和效率提升，因此属于LLM应用分类。` `机器学习` `软件开发`

> An Opportunistically Parallel Lambda Calculus for Performant Composition of Large Language Models

# 摘要

> 大型语言模型（LLMs）在众多任务中表现出色，但仍面临虚构事实和算术难题等挑战。近期研究采用复杂解码技术来克服这些限制，但高效解码依赖于并行化和批处理，这对开发者而言是一大难题。我们发现：1）现有方法虽为高阶领域特定语言，用于整合昂贵的黑盒调用，但缺乏通用性和组合性；2）LLM程序本质上是纯的，所有操作均可交换。基于此，我们创新性地开发了一种通用lambda演算，自动并行化LLM交互，无需用户介入。这一策略的关键在于“机会主义”评估，它并行处理程序独立部分，并积极分派外部黑盒调用，即便在等待其他外部调用返回时亦如此。为保持语言简洁并确保评估一致性，我们通过Church编码在语言内部实现了控制流和循环结构。我们实现的EPIC框架紧密嵌入并交互于Python中，通过三个机器学习案例展示了其灵活性和高效性：思维树（嵌入搜索程序的LLMs）、嵌套工具使用和受限解码。实验显示，机会主义评估相比顺序评估提供了1.5至4.8倍的加速，同时允许开发者编写简洁且可组合的程序，无需手动并行或批处理。

> Large language models (LLMs) have shown impressive results at a wide-range of tasks. However, they have limitations, such as hallucinating facts and struggling with arithmetic. Recent work has addressed these issues with sophisticated decoding techniques. However, performant decoding, particularly for sophisticated techniques, relies crucially on parallelization and batching, which are difficult for developers.
  We make two observations: 1) existing approaches are high-level domain-specific languages for gluing expensive black-box calls, but are not general or compositional; 2) LLM programs are essentially pure (all effects commute). Guided by these observations, we develop a novel, general-purpose lambda calculus for automatically parallelizing a wide-range of LLM interactions, without user intervention. The key difference versus standard lambda calculus is a novel "opportunistic" evaluation strategy, which steps independent parts of a program in parallel, dispatching black-box external calls as eagerly as possible, even while data-independent parts of the program are waiting for their own external calls to return. To maintain the simplicity of the language and to ensure uniformity of opportunistic evaluation, control-flow and looping constructs are implemented in-language, via Church encodings.
  We implement this approach in a framework called EPIC, embedded in--and interoperating closely with--Python. We demonstrate its versatility and performance with three case studies drawn from the machine learning literature: Tree-of-Thoughts (LLMs embedded in classic search procedures), nested tool use, and constrained decoding. Our experiments show that opportunistic evaluation offers a $1.5\times$ to $4.8\times$ speedup over sequential evaluation, while still allowing practitioners to write straightforward and composable programs, without any manual parallelism or batching.

[Arxiv](https://arxiv.org/abs/2405.11361)