# DyPyBench 是一款专注于可执行 Python 软件性能评估的基准测试工具，用于衡量各类 Python 应用程序的实际运行效果。

发布时间：2024年03月01日

`未提供

由于该论文摘要并未直接涉及Agent、RAG、LLM应用或LLM理论中的任何一个主题，无法对其进行准确分类。根据摘要内容，该论文主要介绍了一种名为DyPyBench的Python项目基准套件及其在动态分析中的应用，因此可以将其分类为“编程语言与动态分析”或类似的类别。`

> DyPyBench: A Benchmark of Executable Python Software

> Python 凭借其在机器学习、数据分析及 web 开发等领域的广泛应用，已成为最受欢迎的编程语言之一。其动态特性使之成为动态程序分析的理想选择，但遗憾的是，相较于其他主流语言，当前尚未出现一套全面的 Python 可执行项目基准套件，这一缺失制约了动态分析技术的发展。因此，本文提出了 DyPyBench ——首个大型、多样、即刻运行（所有测试套件均已完成配置和预处理）、无缝对接 DynaPyt 动态分析框架的 Python 项目基准。它包含了来自不同应用场景的50个知名开源项目，总计拥有68.1万行 Python 代码和3万个测试案例。基于 DyPyBench，我们可以开展多种测试与动态分析实践，并在本文中探讨了三个实例：(i) 收集并对比实际运行产生的动态调用图与静态计算的调用图，从而揭示并量化现行 Python 调用图构建方法的局限；(ii) 运用 DyPyBench 数据集训练 LExecutor 神经网络模型，以预测原本在运行时可能缺失的值；(iii) 通过解析动态捕获的执行轨迹，提炼出 API 使用规范，为后续 Python 规范挖掘奠定基础。我们期待 DyPyBench 能够为更多种类的动态分析研究及深入探究 Python 代码运行时行为提供有力支持。

> Python has emerged as one of the most popular programming languages, extensively utilized in domains such as machine learning, data analysis, and web applications. Python's dynamic nature and extensive usage make it an attractive candidate for dynamic program analysis. However, unlike for other popular languages, there currently is no comprehensive benchmark suite of executable Python projects, which hinders the development of dynamic analyses. This work addresses this gap by presenting DyPyBench, the first benchmark of Python projects that is large scale, diverse, ready to run (i.e., with fully configured and prepared test suites), and ready to analyze (by integrating with the DynaPyt dynamic analysis framework). The benchmark encompasses 50 popular opensource projects from various application domains, with a total of 681k lines of Python code, and 30k test cases. DyPyBench enables various applications in testing and dynamic analysis, of which we explore three in this work: (i) Gathering dynamic call graphs and empirically comparing them to statically computed call graphs, which exposes and quantifies limitations of existing call graph construction techniques for Python. (ii) Using DyPyBench to build a training data set for LExecutor, a neural model that learns to predict values that otherwise would be missing at runtime. (iii) Using dynamically gathered execution traces to mine API usage specifications, which establishes a baseline for future work on specification mining for Python. We envision DyPyBench to provide a basis for other dynamic analyses and for studying the runtime behavior of Python code.

[Arxiv](https://arxiv.org/abs/2403.00539)