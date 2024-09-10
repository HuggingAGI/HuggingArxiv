# 大规模模拟中的模型输入验证

发布时间：2024年09月09日

`LLM应用` `模拟建模` `数据验证`

> Model Input Verification of Large Scale Simulations

# 摘要

> 可靠的模拟对分析复杂系统至关重要，但其准确性依赖于正确的输入数据。不正确的输入数据，如无效值或格式错误，可能导致模拟失败或结果失真，最终影响结论的可靠性。本文提出了一种名为模型输入验证（MIV）的方法，用于验证模拟中的输入数据。我们在 FabGuard 工具集中实现了这一方法，该工具集使用既定的数据模式和验证工具，专门针对模拟建模的需求。我们引入了一种分类 MIV 模式的形式化方法，并提供了一个简化的验证流程，可无缝集成到现有模拟工作流程中。FabGuard 在冲突驱动的移民、灾难疏散和疾病传播模型等三个不同领域展示了其适用性。此外，我们还探讨了使用大型语言模型（LLM）来自动生成约束和推理。在一个移民模拟案例中，LLM 不仅正确推断了大部分开发者定义的约束，还发现了现有约束中的错误并提出了新的有效约束。评估结果显示，MIV 在大数据集上表现出色，FabGuard 在 140 秒内高效处理了 12,000 个输入文件，并在不同文件大小下保持稳定性能。

> Reliable simulations are critical for analyzing and understanding complex systems, but their accuracy depends on correct input data. Incorrect inputs such as invalid or out-of-range values, missing data, and format inconsistencies can cause simulation crashes or unnoticed result distortions, ultimately undermining the validity of the conclusions. This paper presents a methodology for verifying the validity of input data in simulations, a process we term model input verification (MIV). We implement this approach in FabGuard, a toolset that uses established data schema and validation tools for the specific needs of simulation modeling. We introduce a formalism for categorizing MIV patterns and offer a streamlined verification pipeline that integrates into existing simulation workflows. FabGuard's applicability is demonstrated across three diverse domains: conflict-driven migration, disaster evacuation, and disease spread models. We also explore the use of Large Language Models (LLMs) for automating constraint generation and inference. In a case study with a migration simulation, LLMs not only correctly inferred 22 out of 23 developer-defined constraints, but also identified errors in existing constraints and proposed new, valid constraints. Our evaluation demonstrates that MIV is feasible on large datasets, with FabGuard efficiently processing 12,000 input files in 140 seconds and maintaining consistent performance across varying file sizes.

[Arxiv](https://arxiv.org/abs/2409.05768)