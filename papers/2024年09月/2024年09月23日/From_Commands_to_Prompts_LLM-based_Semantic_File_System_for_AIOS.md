# 从命令到提示：LLM 驱动的 AIOS 语义文件系统

发布时间：2024年09月23日

`LLM应用` `信息技术` `文件管理系统`

> From Commands to Prompts: LLM-based Semantic File System for AIOS

# 摘要

> 大型语言模型 (LLM) 在智能应用和系统中展现出巨大潜力，如基于 LLM 的代理和代理操作系统 (AIOS)。然而，这些系统与底层文件系统交互时，仍依赖传统的手动导航和精确命令，这限制了系统的易用性。为此，我们提出了基于 LLM 的语义文件系统 (LSFS)，通过自然语言提示实现文件管理。在宏观层面，我们设计了全面的 API 集，支持语义文件检索、更新监控和回滚等功能。在微观层面，我们通过构建语义索引存储文件，并利用向量数据库实现语义操作的系统调用。实验表明，LSFS 在用户便利性、功能多样性和操作效率方面显著优于传统文件系统。此外，集成 LLM 后，系统还能进行内容摘要和版本比较等智能任务，进一步提升了其能力。

> Large language models (LLMs) have demonstrated significant potential in the development of intelligent applications and systems such as LLM-based agents and agent operating systems (AIOS). However, when these applications and systems interact with the underlying file system, the file system still remains the traditional paradigm: reliant on manual navigation through precise commands. This paradigm poses a bottleneck to the usability of these systems as users are required to navigate complex folder hierarchies and remember cryptic file names. To address this limitation, we propose an LLM-based semantic file system ( LSFS ) for prompt-driven file management. Unlike conventional approaches, LSFS incorporates LLMs to enable users or agents to interact with files through natural language prompts, facilitating semantic file management. At the macro-level, we develop a comprehensive API set to achieve semantic file management functionalities, such as semantic file retrieval, file update monitoring and summarization, and semantic file rollback). At the micro-level, we store files by constructing semantic indexes for them, design and implement syscalls of different semantic operations (e.g., CRUD, group by, join) powered by vector database. Our experiments show that LSFS offers significant improvements over traditional file systems in terms of user convenience, the diversity of supported functions, and the accuracy and efficiency of file operations. Additionally, with the integration of LLM, our system enables more intelligent file management tasks, such as content summarization and version comparison, further enhancing its capabilities.

[Arxiv](https://arxiv.org/abs/2410.11843)