# 关于基于大型语言模型（LLM）的低资源和特定领域编程语言的代码生成的调查

发布时间：2024年11月04日

`LLM应用` `软件工程` `编程语言`

> A Survey on LLM-based Code Generation for Low-Resource and Domain-Specific Programming Languages

# 摘要

> 大型语言模型（LLM）在流行编程语言的代码生成方面展现出了令人印象深刻的能力。然而，它们在低资源编程语言（LRPL）和领域特定语言（DSL）上的表现仍然是一个重大挑战，影响了数百万的开发者——仅 Rust 就有 350 万用户——他们无法充分利用 LLM 的能力。LRPL 和 DSL 遇到了独特的障碍，包括数据稀缺，对于 DSL 来说，还有在通用数据集中表现不佳的专门语法。

解决这些挑战至关重要，因为 LRPL 和 DSL 在诸如金融和科学等专业领域提高了开发效率。虽然有几项调查讨论了软件工程中的 LLM，但没有一项专门关注与 LRPL 和 DSL 相关的挑战和机会。我们的调查通过系统地回顾这些语言中利用 LLM 进行代码生成的现状、方法和挑战来填补这一空白。我们从 2020 年至 2024 年发表的超过 27000 项研究中筛选了 111 篇论文，以评估 LLM 在 LRPL 和 DSL 中的能力和局限性。我们报告了所使用的 LLM、基准和评估指标、提高性能的策略以及数据集收集和整理的方法。

我们确定了评估 LRPL 和 DSL 中代码生成的四种主要评估技术和若干指标。我们的分析将改进方法分为六组，并总结了研究人员提出的新颖架构。尽管有各种技术和指标，但缺乏用于评估 LRPL 和 DSL 中代码生成的标准方法和基准数据集。这项调查为 LLM、软件工程和专业编程语言交叉领域的研究人员和从业者提供了资源，为 LRPL 和 DSL 的代码生成未来发展奠定了基础。

> Large Language Models (LLMs) have shown impressive capabilities in code generation for popular programming languages. However, their performance on Low-Resource Programming Languages (LRPLs) and Domain-Specific Languages (DSLs) remains a significant challenge, affecting millions of developers-3.5 million users in Rust alone-who cannot fully utilize LLM capabilities. LRPLs and DSLs encounter unique obstacles, including data scarcity and, for DSLs, specialized syntax that is poorly represented in general-purpose datasets.
  Addressing these challenges is crucial, as LRPLs and DSLs enhance development efficiency in specialized domains, such as finance and science. While several surveys discuss LLMs in software engineering, none focus specifically on the challenges and opportunities associated with LRPLs and DSLs. Our survey fills this gap by systematically reviewing the current state, methodologies, and challenges in leveraging LLMs for code generation in these languages. We filtered 111 papers from over 27,000 published studies between 2020 and 2024 to evaluate the capabilities and limitations of LLMs in LRPLs and DSLs. We report the LLMs used, benchmarks, and metrics for evaluation, strategies for enhancing performance, and methods for dataset collection and curation.
  We identified four main evaluation techniques and several metrics for assessing code generation in LRPLs and DSLs. Our analysis categorizes improvement methods into six groups and summarizes novel architectures proposed by researchers. Despite various techniques and metrics, a standard approach and benchmark dataset for evaluating code generation in LRPLs and DSLs are lacking. This survey serves as a resource for researchers and practitioners at the intersection of LLMs, software engineering, and specialized programming languages, laying the groundwork for future advancements in code generation for LRPLs and DSLs.

[Arxiv](https://arxiv.org/abs/2410.03981)