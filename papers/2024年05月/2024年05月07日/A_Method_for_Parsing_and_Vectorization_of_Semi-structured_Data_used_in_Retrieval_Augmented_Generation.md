# 一种解析与向量化半结构化数据的精妙方法，专为检索增强生成而设计。

发布时间：2024年05月07日

`RAG

这篇论文介绍了一种通过解析和向量化半结构化数据来提升大型语言模型（LLMs）中检索增强生成（RAG）效能的创新方法。它专注于构建一个转换流程，将多种数据格式转换为.docx格式，以便于高效解析和结构化数据提取。该方法利用Pinecone创建向量数据库，与LLMs结合，为特定领域（如环境管理和废水处理）提供精准、上下文相关的解答。论文通过多语言、多格式的测试验证了其方法的有效性，并展示了在特定领域内生成丰富且技术准确的上下文响应的能力。因此，这篇论文属于RAG分类。` `环境管理` `废水处理`

> A Method for Parsing and Vectorization of Semi-structured Data used in Retrieval Augmented Generation

# 摘要

> 本文介绍了一种创新方法，通过解析和向量化半结构化数据，提升大型语言模型（LLMs）中检索增强生成（RAG）的效能。我们构建了一套完整的转换流程，将多样数据格式转化为.docx，便于高效解析和结构化数据提取。核心在于利用Pinecone打造向量数据库，与LLMs完美融合，为环境管理及废水处理等场景提供精准、上下文相关的解答。经过多语言、多格式的严格测试，我们的模型在输出精确度和可靠性上取得了显著进步，展现出在特定领域内生成丰富且技术准确的上下文响应的强大能力。此研究不仅验证了我们方法的效力，更预示了其在环境科学数据处理领域的革新潜力，为AI驱动应用的未来发展树立了标杆。相关代码已公开于https://github.com/linancn/TianGong-AI-Unstructure.git。

> This paper presents a novel method for parsing and vectorizing semi-structured data to enhance the functionality of Retrieval-Augmented Generation (RAG) within Large Language Models (LLMs). We developed a comprehensive pipeline for converting various data formats into .docx, enabling efficient parsing and structured data extraction. The core of our methodology involves the construction of a vector database using Pinecone, which integrates seamlessly with LLMs to provide accurate, context-specific responses, particularly in environmental management and wastewater treatment operations. Through rigorous testing with both English and Chinese texts in diverse document formats, our results demonstrate a marked improvement in the precision and reliability of LLMs outputs. The RAG-enhanced models displayed enhanced ability to generate contextually rich and technically accurate responses, underscoring the potential of vector knowledge bases in significantly boosting the performance of LLMs in specialized domains. This research not only illustrates the effectiveness of our method but also highlights its potential to revolutionize data processing and analysis in environmental sciences, setting a precedent for future advancements in AI-driven applications. Our code is available at https://github.com/linancn/TianGong-AI-Unstructure.git.

[Arxiv](https://arxiv.org/abs/2405.03989)