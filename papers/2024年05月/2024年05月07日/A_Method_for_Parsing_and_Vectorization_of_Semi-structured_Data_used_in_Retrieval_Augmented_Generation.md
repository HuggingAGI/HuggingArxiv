# 一种解析与向量化半结构化数据的技艺，专为检索增强生成而设计

发布时间：2024年05月07日

`RAG

这篇论文主要介绍了一种用于解析和向量化半结构化数据的方法，旨在提升大型语言模型（LLMs）中检索增强生成（RAG）的效能。它通过构建转换流程将多种数据格式转化为.docx，并利用Pinecone构建向量数据库，与LLMs结合，以提供精准、上下文相关的响应。这种方法特别适用于环境管理和废水处理等场景，并经过测试显示能够显著提升LLMs的输出精确度和可靠性。因此，它更符合RAG分类，因为它专注于通过向量化和检索增强来改进LLMs的性能。` `环境管理` `废水处理`

> A Method for Parsing and Vectorization of Semi-structured Data used in Retrieval Augmented Generation

# 摘要

> 本文介绍了一种创新方法，用于解析和向量化半结构化数据，以提升大型语言模型（LLMs）中检索增强生成（RAG）的效能。我们构建了一套全面的转换流程，将多种数据格式转化为.docx，以便进行高效解析和结构化数据提取。我们的核心技术是利用Pinecone构建向量数据库，与LLMs完美融合，为环境管理和废水处理等场景提供精准、上下文相关的响应。经过对英汉文本及多样文档格式的严格测试，我们发现LLMs的输出精确度和可靠性显著提升。RAG增强的模型在生成富含上下文且技术准确的响应方面表现出色，凸显了向量知识库在提升LLMs专业领域性能方面的巨大潜力。这项研究不仅验证了我们方法的有效性，还预示了其在环境科学数据处理和分析领域的革新潜力，为AI驱动应用的未来发展树立了标杆。我们的代码已公开在https://github.com/linancn/TianGong-AI-Unstructure.git。

> This paper presents a novel method for parsing and vectorizing semi-structured data to enhance the functionality of Retrieval-Augmented Generation (RAG) within Large Language Models (LLMs). We developed a comprehensive pipeline for converting various data formats into .docx, enabling efficient parsing and structured data extraction. The core of our methodology involves the construction of a vector database using Pinecone, which integrates seamlessly with LLMs to provide accurate, context-specific responses, particularly in environmental management and wastewater treatment operations. Through rigorous testing with both English and Chinese texts in diverse document formats, our results demonstrate a marked improvement in the precision and reliability of LLMs outputs. The RAG-enhanced models displayed enhanced ability to generate contextually rich and technically accurate responses, underscoring the potential of vector knowledge bases in significantly boosting the performance of LLMs in specialized domains. This research not only illustrates the effectiveness of our method but also highlights its potential to revolutionize data processing and analysis in environmental sciences, setting a precedent for future advancements in AI-driven applications. Our code is available at https://github.com/linancn/TianGong-AI-Unstructure.git.

[Arxiv](https://arxiv.org/abs/2405.03989)