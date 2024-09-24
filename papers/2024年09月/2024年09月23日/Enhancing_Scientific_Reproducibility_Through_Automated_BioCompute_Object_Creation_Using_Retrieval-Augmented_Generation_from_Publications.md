# 利用检索增强生成技术，自动创建 BioCompute 对象，从而提升科学研究的可重复性。

发布时间：2024年09月23日

`RAG` `生物信息学` `科学文档编制`

> Enhancing Scientific Reproducibility Through Automated BioCompute Object Creation Using Retrieval-Augmented Generation from Publications

# 摘要

> 计算能力的飞速提升和普及，使得生物信息学研究的复杂性和规模发生了巨大变化，迫切需要标准化文档来确保透明度、可重复性和法规遵从性。IEEE BioCompute Object (BCO) 标准应运而生，但因创建合规文档的繁琐，尤其是在旧研究中，其推广面临挑战。本文提出了一种创新方法，利用检索增强生成 (RAG) 和大型语言模型 (LLM) 从科学论文中自动生成 BCO。我们开发的 BCO 助手工具，通过 RAG 从源论文和代码库中提取关键信息，有效应对了 LLM 幻觉和长上下文理解等难题。该工具采用优化的两遍检索与重新排序技术，并针对不同 BCO 领域设计了精巧的提示。我们详细介绍了工具的架构、可扩展性及评估方法，包括自动化和手动评估。BCO 助手不仅大幅减少了生物信息学研究事后文档编制的时间和精力，还确保了与标准的合规性。这一创新为 AI 辅助的科学文档编制和知识提取打开了新篇章，有力推动了科学研究的可重复性。BCO 助手工具和文档现已上线，访问地址为 https://biocompute-objects.github.io/bco-rag/。

> The exponential growth in computational power and accessibility has transformed the complexity and scale of bioinformatics research, necessitating standardized documentation for transparency, reproducibility, and regulatory compliance. The IEEE BioCompute Object (BCO) standard addresses this need but faces adoption challenges due to the overhead of creating compliant documentation, especially for legacy research. This paper presents a novel approach to automate the creation of BCOs from scientific papers using Retrieval-Augmented Generation (RAG) and Large Language Models (LLMs). We describe the development of the BCO assistant tool that leverages RAG to extract relevant information from source papers and associated code repositories, addressing key challenges such as LLM hallucination and long-context understanding. The implementation incorporates optimized retrieval processes, including a two-pass retrieval with re-ranking, and employs carefully engineered prompts for each BCO domain. We discuss the tool's architecture, extensibility, and evaluation methods, including automated and manual assessment approaches. The BCO assistant demonstrates the potential to significantly reduce the time and effort required for retroactive documentation of bioinformatics research while maintaining compliance with the standard. This approach opens avenues for AI-assisted scientific documentation and knowledge extraction from publications thereby enhancing scientific reproducibility. The BCO assistant tool and documentation is available at https://biocompute-objects.github.io/bco-rag/.

[Arxiv](https://arxiv.org/abs/2409.15076)