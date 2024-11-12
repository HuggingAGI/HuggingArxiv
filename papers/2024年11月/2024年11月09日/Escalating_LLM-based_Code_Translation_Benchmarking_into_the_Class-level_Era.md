# 将基于 LLM 的代码翻译基准测试提升到类级别时代

发布时间：2024年11月09日

`LLM应用` `代码翻译` `软件开发`

> Escalating LLM-based Code Translation Benchmarking into the Class-level Era

# 摘要

> 近年来，大型语言模型（LLMs）显著提高了自动代码翻译的水平，在现有的基准测试中经常达到 80%以上的准确率。然而，这些基准测试大多由简短、独立的算法样本组成，不能反映实际的编码任务。为了解决这一差距，我们引入了 ClassEval-T，这是一个类级别的代码翻译基准，旨在评估 LLM 在现实世界编码场景中的性能。ClassEval-T 基于 ClassEval 构建，ClassEval 是一个涵盖数据库操作和游戏设计等主题的类级别的 Python 代码生成基准，ClassEval-T 扩展到 Java 和 C++，具有完整的代码样本和测试套件，需要 360 个人工时进行手动迁移。我们提出了三种翻译策略（整体、最小依赖和独立），并在 ClassEval-T 上对来自不同家族和规模的六个近期的 LLM 进行了评估。结果显示，与方法级别的基准相比，性能显著下降，突出了 LLM 之间的差异，并证明了 ClassEval-T 的有效性。我们进一步分析了 LLM 在翻译类样本时的依赖意识，并由表现最佳的 LLM 对 1397 个失败案例进行分类，以获取实际的见解和未来的改进。

> In recent years, Large Language Models (LLMs) have significantly improved automated code translation, often achieving over 80% accuracy on existing benchmarks. However, most of these benchmarks consist of short, standalone, algorithmic samples that do not reflect practical coding tasks. To address this gap, we introduce ClassEval-T, a class-level code translation benchmark designed to assess LLM performance on real-world coding scenarios. Built upon ClassEval, a class-level Python code generation benchmark covering topics such as database operations and game design, ClassEval-T extends into Java and C++ with complete code samples and test suites, requiring 360 person-hours for manual migration. We propose three translation strategies (holistic, min-dependency, and standalone) and evaluate six recent LLMs across various families and sizes on ClassEval-T. Results reveal a significant performance drop compared to method-level benchmarks, highlighting discrepancies among LLMs and demonstrating ClassEval-T's effectiveness. We further analyze LLMs' dependency awareness in translating class samples and categorize 1,397 failure cases by the best-performing LLM for practical insights and future improvement.

[Arxiv](https://arxiv.org/abs/2411.06145)