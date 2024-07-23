# 探讨基于LLM算法的构思与评估

发布时间：2024年07月20日

`LLM理论` `人工智能` `软件开发`

> On the Design and Analysis of LLM-Based Algorithms

# 摘要

> 我们正式开启了基于大型语言模型（LLM）算法的深入研究，这些算法将LLM作为核心子程序，并高度依赖其能力。尽管从简单的提示工程到复杂的AI系统，基于LLM的算法已取得显著成就，但其设计与优化仍多依赖于经验法则和反复试验。为弥补这一理论空缺，我们首先确立了LLM算法的计算图表示、任务分解原则及关键抽象，以此为基础，我们进行了严谨的准确性与效率分析，即便面对LLM的黑箱特性。此外，我们还通过并行分解案例，深入探讨了四个具体实例。我们的框架不仅揭示了实证现象的内在逻辑，指导超参数选择，预测算法性能，还激发了新算法设计的灵感，推动了LLM算法的进步。为促进更广泛的研究，我们在GitHub上公开了我们的研究代码。

> We initiate a formal investigation into the design and analysis of LLM-based algorithms, i.e. algorithms that contain one or multiple calls of large language models (LLMs) as sub-routines and critically rely on the capabilities of LLMs. While LLM-based algorithms, ranging from basic LLM calls with prompt engineering to complicated LLM-powered agent systems and compound AI systems, have achieved remarkable empirical success, the design and optimization of them have mostly relied on heuristics and trial-and-errors, which is largely due to a lack of formal and analytical study for these algorithms. To fill this gap, we start by identifying the computational-graph representation of LLM-based algorithms, the design principle of task decomposition, and some key abstractions, which then facilitate our formal analysis for the accuracy and efficiency of LLM-based algorithms, despite the black-box nature of LLMs. We further consider parallel decomposition for a case study, providing extensive analytical and empirical study for four concrete examples of this pattern. Our proposed framework holds promise for advancing LLM-based algorithms, by revealing the reasons behind curious empirical phenomena, guiding the choices of hyperparameters, predicting the empirical performance of algorithms, and inspiring new algorithm design. To promote further study of LLM-based algorithms, we release our source code at https://github.com/modelscope/agentscope/tree/main/examples/paper_llm_based_algorithm.

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x1.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x2.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x3.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x4.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x5.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x6.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x7.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x8.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x9.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x10.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x11.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x12.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x13.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x14.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x15.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x16.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x17.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x18.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x19.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x20.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x21.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x22.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x23.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x24.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x25.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x26.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x27.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x28.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x29.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x30.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x31.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x32.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x33.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x34.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x35.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x36.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x37.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x38.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x39.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x40.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x41.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x42.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x43.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x44.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x45.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x46.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x47.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x48.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x49.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x50.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x51.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x52.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x53.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x54.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x55.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x56.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x57.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x58.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x59.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x60.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x61.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x62.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x63.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x64.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x65.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x66.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x67.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x68.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x69.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x70.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x71.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x72.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x73.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x74.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x75.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x76.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x77.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x78.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x79.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x80.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x81.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x82.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x83.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x84.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x85.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x86.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x87.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x88.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x89.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x90.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x91.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x92.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x93.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x94.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x95.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x96.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x97.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x98.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x99.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x100.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x101.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x102.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x103.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x104.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x105.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x106.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x107.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x108.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x109.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x110.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x111.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x112.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x113.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x114.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x115.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x116.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x117.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x118.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x119.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x120.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x121.png)

![探讨基于LLM算法的构思与评估](../../../paper_images/2407.14788/x122.png)

[Arxiv](https://arxiv.org/abs/2407.14788)