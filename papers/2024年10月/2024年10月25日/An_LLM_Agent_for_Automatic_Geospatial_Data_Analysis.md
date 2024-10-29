# 一个用于自动地理空间数据分析的大型语言模型代理

发布时间：2024年10月25日

`Agent` `地理空间` `数据科学`

> An LLM Agent for Automatic Geospatial Data Analysis

# 摘要

> 大型语言模型（LLMs）正被用于数据科学代码生成任务，但它们在复杂的顺序任务中常常遇到困难，导致逻辑错误。由于在纳入复杂的数据结构和空间约束、有效利用各种函数调用以及容易对较少使用的地理空间库产生幻觉方面存在困难，它们在地理空间数据处理中的应用尤其具有挑战性。为了解决这些问题，我们引入了 GeoAgent，这是一个新的交互式框架，旨在帮助 LLMs 更有效地处理地理空间数据处理。GeoAgent 率先在蒙特卡罗树搜索（MCTS）算法中集成了代码解释器、静态分析和检索增强生成（RAG）技术，为地理空间数据处理提供了一种新方法。此外，我们贡献了一个专门设计用于评估基于 LLM 的地理空间任务方法的新基准。这个基准利用了各种 Python 库，包括单轮和多轮任务，如数据获取、数据分析和可视化。通过在不同的地理空间环境中提供全面评估，该基准为在地理空间数据分析任务中开发基于 LLM 的方法设定了新的标准。我们的研究结果表明，仅仅依靠 LLM 的知识对于准确的地理空间任务编程是不够的，这需要连贯的多步骤流程和多个函数调用。与基线 LLMs 相比，所提出的 GeoAgent 表现出了优越的性能，在函数调用和任务完成方面有显著的改进。此外，这些结果为未来在自动地理空间数据分析任务编程中 LLM 代理的发展提供了有价值的见解。

> Large language models (LLMs) are being used in data science code generation tasks, but they often struggle with complex sequential tasks, leading to logical errors. Their application to geospatial data processing is particularly challenging due to difficulties in incorporating complex data structures and spatial constraints, effectively utilizing diverse function calls, and the tendency to hallucinate less-used geospatial libraries. To tackle these problems, we introduce GeoAgent, a new interactive framework designed to help LLMs handle geospatial data processing more effectively. GeoAgent pioneers the integration of a code interpreter, static analysis, and Retrieval-Augmented Generation (RAG) techniques within a Monte Carlo Tree Search (MCTS) algorithm, offering a novel approach to geospatial data processing. In addition, we contribute a new benchmark specifically designed to evaluate the LLM-based approach in geospatial tasks. This benchmark leverages a variety of Python libraries and includes both single-turn and multi-turn tasks such as data acquisition, data analysis, and visualization. By offering a comprehensive evaluation among diverse geospatial contexts, this benchmark sets a new standard for developing LLM-based approaches in geospatial data analysis tasks. Our findings suggest that relying solely on knowledge of LLM is insufficient for accurate geospatial task programming, which requires coherent multi-step processes and multiple function calls. Compared to the baseline LLMs, the proposed GeoAgent has demonstrated superior performance, yielding notable improvements in function calls and task completion. In addition, these results offer valuable insights for the future development of LLM agents in automatic geospatial data analysis task programming.

[Arxiv](https://arxiv.org/abs/2410.18792)