# RAGViz：对检索增强生成进行诊断与可视化

发布时间：2024年11月03日

`RAG` `语言模型` `工具开发`

> RAGViz: Diagnose and Visualize Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）把来自特定领域的知识融入大型语言模型，从而生成有依据的答案。当下的 RAG 系统在上下文文档的可定制可见性以及模型对这类文档的关注度上有所欠缺。我们推出了 RAGViz 这一 RAG 诊断工具，它能将检索文档中生成的标记的关注度予以可视化。凭借内置的用户界面、检索索引和大型语言模型（LLM）框架，RAGViz 具备两大主要功能：（1）标记和文档级别的关注度可视化；（2）在添加和删除上下文文档时进行生成比较。作为一个开源工具包，RAGViz 能够轻松与自定义嵌入模型和 HuggingFace 支持的 LLM 框架一同托管。借助混合 ANN（近似最近邻）索引、内存高效的 LLM 推理工具和自定义上下文片段方法，RAGViz 在中等 GPU 节点上运行高效，中位查询时间约为 5 秒。我们的代码位于 https://github.com/cxcscmu/RAGViz 。RAGViz 的演示视频在 https://youtu.be/cTAbuTu6ur4 可以找到。

> Retrieval-augmented generation (RAG) combines knowledge from domain-specific sources into large language models to ground answer generation. Current RAG systems lack customizable visibility on the context documents and the model's attentiveness towards such documents. We propose RAGViz, a RAG diagnosis tool that visualizes the attentiveness of the generated tokens in retrieved documents. With a built-in user interface, retrieval index, and Large Language Model (LLM) backbone, RAGViz provides two main functionalities: (1) token and document-level attention visualization, and (2) generation comparison upon context document addition and removal. As an open-source toolkit, RAGViz can be easily hosted with a custom embedding model and HuggingFace-supported LLM backbone. Using a hybrid ANN (Approximate Nearest Neighbor) index, memory-efficient LLM inference tool, and custom context snippet method, RAGViz operates efficiently with a median query time of about 5 seconds on a moderate GPU node. Our code is available at https://github.com/cxcscmu/RAGViz. A demo video of RAGViz can be found at https://youtu.be/cTAbuTu6ur4.

[Arxiv](https://arxiv.org/abs/2411.01751)