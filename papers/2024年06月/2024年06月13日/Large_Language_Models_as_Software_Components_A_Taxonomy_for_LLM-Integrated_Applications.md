# 大型语言模型：软件组件的新分类法，专为集成LLM的应用而设计

发布时间：2024年06月13日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLMs）在软件工程中的应用，特别是在集成到软件系统中的方式和效果。论文提供了一个分类体系和框架来分析和描述这些集成应用，并讨论了如何有效地利用LLMs来完成复杂的任务。这与LLM应用分类下的内容相符，因为它关注的是LLMs在实际应用中的集成和使用，而不是理论研究或Agent的行为。` `软件工程` `人工智能`

> Large Language Models as Software Components: A Taxonomy for LLM-Integrated Applications

# 摘要

> 大型语言模型（LLMs）近期广受欢迎，研究领域不仅将其视为自主代理，也作为软件工程的辅助工具。LLM集成的应用程序是那些利用LLM来完成原本难以实现或需大量编码的任务的软件系统。尽管LLM集成应用工程正崭露头角，但其术语、概念和方法尚待确立。本研究为此类应用提供了一套分类体系，构建了一个分析和描述这些系统的框架，并展示了如何在应用中巧妙运用LLMs，以及如何实现这种集成。我们采用标准方法，对近期的一些LLM集成应用进行了分析，以揭示关键维度。通过将分类法应用于更多案例，我们验证了其有效性。研究发现，LLMs在应用中的集成方式多样，目的各异，常常涉及多个“LLM组件”。为了深入理解应用架构，我们逐一剖析了这些LLM组件。我们识别了十三个维度来刻画LLM组件，涵盖了所利用的LLM技能、输出格式等。LLM集成应用程序被视为其LLM组件的组合，我们提出了使用特征向量进行简洁可视化的方法。这一分类体系为描述LLM集成应用程序提供了有效工具，有助于在LLM集成应用工程这一新兴领域构建理论，并促进此类系统的开发。尽管挑战犹存，但LLMs的集成有望革新软件系统的构建方式。

> Large Language Models (LLMs) have become widely adopted recently. Research explores their use both as autonomous agents and as tools for software engineering. LLM-integrated applications, on the other hand, are software systems that leverage an LLM to perform tasks that would otherwise be impossible or require significant coding effort. While LLM-integrated application engineering is emerging as new discipline, its terminology, concepts and methods need to be established. This study provides a taxonomy for LLM-integrated applications, offering a framework for analyzing and describing these systems. It also demonstrates various ways to utilize LLMs in applications, as well as options for implementing such integrations.
  Following established methods, we analyze a sample of recent LLM-integrated applications to identify relevant dimensions. We evaluate the taxonomy by applying it to additional cases. This review shows that applications integrate LLMs in numerous ways for various purposes. Frequently, they comprise multiple LLM integrations, which we term ``LLM components''. To gain a clear understanding of an application's architecture, we examine each LLM component separately. We identify thirteen dimensions along which to characterize an LLM component, including the LLM skills leveraged, the format of the output, and more. LLM-integrated applications are described as combinations of their LLM components. We suggest a concise representation using feature vectors for visualization.
  The taxonomy is effective for describing LLM-integrated applications. It can contribute to theory building in the nascent field of LLM-integrated application engineering and aid in developing such systems. Researchers and practitioners explore numerous creative ways to leverage LLMs in applications. Though challenges persist, integrating LLMs may revolutionize the way software systems are built.

[Arxiv](https://arxiv.org/abs/2406.10300)