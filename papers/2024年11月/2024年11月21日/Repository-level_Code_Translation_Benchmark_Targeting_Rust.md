# 针对 Rust 的仓库级别代码翻译基准

发布时间：2024年11月21日

`LLM应用` `软件开发` `代码翻译`

> Repository-level Code Translation Benchmark Targeting Rust

# 摘要

> 近期大型语言模型（LLMs）在代码翻译领域取得了显著进展，常以 CodeTransOcean 等基准来评估。但这些评估多聚焦于简单的函数级翻译，未考虑依赖关系，无法体现真实软件开发的复杂性。而且，它们在现实场景中向诸如 Rust 这类较新且资源较少的语言翻译的有效性仍有待深入探究。为填补这一空缺，我们推出了首个涵盖 375 个针对 Rust 任务的存储库级代码翻译基准，包含相关依赖关系。基于此基准，我们对四个前沿的 LLMs 展开研究，分析其错误输出，以洞悉它们在更复杂翻译场景中的表现。我们发现，与简单任务相比，LLMs 在存储库级翻译中的表现差很多（GPT-4 的 Pass@1 下降 41.5%-56.2%），暴露出现有评估方法的局限性。表现最佳的是 Claude-3.5 模型，在基本功能准确性及若干相关附加能力方面展现出最强的翻译能力。另外，我们还发现 LLMs 在复杂任务中难以辨别语言差异，且依赖关系增多会加大翻译难度。

> Recent advances in large language models (LLMs) have shown significant capabilities in code translation, often evaluated using benchmarks like CodeTransOcean. However, these evaluations typically focus on simple, function-level translations without considering dependencies, which does not reflect the complexities of real-world software development. Further, their effectiveness in translating to newer, lower-resource languages like Rust in realistic scenarios is still under-explored. To address this gap, we introduce first repository-level code translation benchmark comprising 375 tasks targeting Rust, complete with relevant dependencies. Using this benchmark, we study four state-of-the-art LLMs, analyzing their erroneous outputs to understand their performance in more complex translation scenarios. Our findings reveal that LLMs exhibit substantially worse performance (41.5%-56.2% Pass@1 drop of GPT-4) on repository-level translations compared to simpler tasks, highlighting limitations in existing evaluation methods. The model that performed the best is Claude-3.5, demonstrating the strongest translation capabilities in both basic functionality accuracy and several relevant additional abilities. Additionally, we discover that LLMs struggle with identifying language differences in complex tasks, and that increased dependencies correlate with greater translation difficulty.

[Arxiv](https://arxiv.org/abs/2411.13990)