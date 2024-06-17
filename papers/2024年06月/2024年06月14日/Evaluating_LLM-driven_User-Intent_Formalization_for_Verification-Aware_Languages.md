# 探究大型语言模型在验证感知语言中对用户意图形式化的评估

发布时间：2024年06月14日

`LLM应用

这篇论文探讨了如何利用大型语言模型（LLMs）来促进非正式意图与正式程序实现之间的转换，特别是在验证感知编程语言如Dafny和F*中。论文提出了一种新的方法——符号测试规范，用于评估验证感知语言的规范质量，并展示了这种方法与GPT-4生成和人工标记的数据集的高度一致性。这一研究直接应用于LLM在编程语言规范和验证中的应用，因此属于LLM应用分类。` `编程语言` `软件验证`

> Evaluating LLM-driven User-Intent Formalization for Verification-Aware Languages

# 摘要

> Dafny和F*等验证感知编程语言允许正式指定和证明程序属性。虽然可以机械地检查实现是否符合规范，但确保规范符合用户意图的算法方法尚不存在。用户意图以非正式的自然语言表达，而规范则是正式的产物。大型语言模型（LLMs）的出现促进了非正式意图与正式程序实现之间的桥梁，这在很大程度上得益于评估基准和自动化指标。最近的研究提出了评估主流编程语言的用户意图正式化问题，但这种方法不适用于支持复杂规范（如量词和幽灵变量）的验证感知语言，这些规范无法通过动态执行评估。以往的研究还依赖于使用LLMs生成程序变异体来创建基准。我们提出了一种替代方法——符号测试规范，以提供一个直观的指标来评估验证感知语言的规范质量。我们的自动化指标与GPT-4生成和人工标记的大约150个Dafny规范的数据集高度一致，这些规范用于流行的MBPP代码生成基准，同时也揭示了人工标记的不足之处。我们相信，我们的工作为建立用户意图正式化问题的基准和研究议程奠定了基础。

> Verification-aware programming languages such as Dafny and F* provide means to formally specify and prove properties of programs. Although the problem of checking an implementation against a specification can be defined mechanically, there is no algorithmic way of ensuring the correctness of the user-intent formalization for programs -- that a specification adheres to the user's intent behind the program. The intent or requirement is expressed informally in natural language and the specification is a formal artefact. The advent of large language models (LLMs) has made strides bridging the gap between informal intent and formal program implementations recently, driven in large parts due to benchmarks and automated metrics for evaluation.
  Recent work has proposed evaluating {\it user-intent formalization} problem for mainstream programming languages~\cite{endres-fse24}. However, such an approach does not readily extend to verification-aware languages that support rich specifications (containing quantifiers and ghost variables) that cannot be evaluated through dynamic execution. Previous work also required generating program mutants using LLMs to create the benchmark. We advocate an alternate approach of {\it symbolically testing specifications} to provide an intuitive metric for evaluating the quality of specifications for verification-aware languages. We demonstrate that our automated metric agrees closely with mostly GPT-4 generated and human-labeled dataset of roughly 150 Dafny specifications for the popular MBPP code-generation benchmark, yet demonstrates cases where the human labeling is not perfect. We believe our work provides a stepping stone to enable the establishment of a benchmark and research agenda for the problem of user-intent formalization for programs.

[Arxiv](https://arxiv.org/abs/2406.09757)