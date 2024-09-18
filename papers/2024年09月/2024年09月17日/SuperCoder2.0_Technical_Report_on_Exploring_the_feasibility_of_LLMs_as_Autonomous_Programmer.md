# SuperCoder2.0：探究 LLM 成为自主程序员可能性的技术报告

发布时间：2024年09月17日

`Agent` `软件开发` `人工智能`

> SuperCoder2.0: Technical Report on Exploring the feasibility of LLMs as Autonomous Programmer

# 摘要

> 我们推出了 SuperCoder2.0，一个结合 AI 和智能代理的先进自主系统，旨在实现完全自主的软件开发。其核心功能包括：错误追溯重试机制、基于抽象语法树的全面代码重写、检索增强生成的代码嵌入技术，以及问题解决的本地化方法。系统采用三步搜索空间缩减策略：首先识别候选文件，然后缩小至最相关文件，最后定位文件内的“相关位置”。代码编辑通过 CodeGeneration 和 CodeEditing 模块完成，生成多样解决方案并确保代码完整性。实验显示，SuperCoder2.0 在 SWE-bench Lite 数据集上表现优异，文件本地化准确率达 84.33%，问题解决率达 34%，全球排名第四。未来，我们将优化代码编辑流程，并探索更先进的嵌入模型，以进一步提升自然语言到代码的转换效率。

> We present SuperCoder2.0, an advanced autonomous system designed to enhance software development through artificial intelligence. The system combines an AI-native development approach with intelligent agents to enable fully autonomous coding. Key focus areas include a retry mechanism with error output traceback, comprehensive code rewriting and replacement using Abstract Syntax Tree (ast) parsing to minimize linting issues, code embedding technique for retrieval-augmented generation, and a focus on localizing methods for problem-solving rather than identifying specific line numbers. The methodology employs a three-step hierarchical search space reduction approach for code base navigation and bug localization:utilizing Retrieval Augmented Generation (RAG) and a Repository File Level Map to identify candidate files, (2) narrowing down to the most relevant files using a File Level Schematic Map, and (3) extracting 'relevant locations' within these files. Code editing is performed through a two-part module comprising CodeGeneration and CodeEditing, which generates multiple solutions at different temperature values and replaces entire methods or classes to maintain code integrity. A feedback loop executes repository-level test cases to validate and refine solutions. Experiments conducted on the SWE-bench Lite dataset demonstrate SuperCoder2.0's effectiveness, achieving correct file localization in 84.33% of cases within the top 5 candidates and successfully resolving 34% of test instances. This performance places SuperCoder2.0 fourth globally on the SWE-bench leaderboard. The system's ability to handle diverse repositories and problem types highlights its potential as a versatile tool for autonomous software development. Future work will focus on refining the code editing process and exploring advanced embedding models for improved natural language to code mapping.

[Arxiv](https://arxiv.org/abs/2409.11190)