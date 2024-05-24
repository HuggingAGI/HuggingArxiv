# xRAG：单令牌驱动，极致压缩上下文，助力检索增强生成

发布时间：2024年05月22日

`RAG

理由：这篇论文介绍了一种名为xRAG的新技术，它是一种针对检索增强生成（RAG）的上下文压缩技术。xRAG通过重新定义密集文档嵌入并利用模式融合技术，有效地将这些嵌入融入语言模型空间，从而实现了高效的文本压缩。这种技术特别适用于检索增强生成场景，并且通过实验证明了其在多个知识密集型任务上的性能提升。因此，这篇论文应归类为RAG。` `知识密集型任务` `检索增强生成`

> xRAG: Extreme Context Compression for Retrieval-augmented Generation with One Token

# 摘要

> 本文推出的xRAG，是一种针对检索增强生成量身定制的创新上下文压缩技术。它将传统仅用于检索的密集文档嵌入重新定义为检索模式的特征。通过模式融合技术，xRAG将这些嵌入无缝融入语言模型空间，大幅减少了对文本的需求，实现了极高的压缩效率。xRAG中唯一可调的部分是模式桥，检索器和语言模型则保持不变，这使得离线构建的文档嵌入得以复用，并保持了检索增强的即插即用特性。实验显示，xRAG在六个知识密集型任务上平均性能提升了10%以上，适用于从7B密集模型到8x7B专家混合配置的各种语言模型。xRAG不仅超越了以往的上下文压缩方法，还在多个数据集上与未压缩模型媲美，同时将总体计算量减少了3.53倍。我们的研究为检索增强生成的多模式融合开辟了新路径，并期望为未来高效可扩展的检索增强系统奠定基石。

> This paper introduces xRAG, an innovative context compression method tailored for retrieval-augmented generation. xRAG reinterprets document embeddings in dense retrieval--traditionally used solely for retrieval--as features from the retrieval modality. By employing a modality fusion methodology, xRAG seamlessly integrates these embeddings into the language model representation space, effectively eliminating the need for their textual counterparts and achieving an extreme compression rate. In xRAG, the only trainable component is the modality bridge, while both the retriever and the language model remain frozen. This design choice allows for the reuse of offline-constructed document embeddings and preserves the plug-and-play nature of retrieval augmentation. Experimental results demonstrate that xRAG achieves an average improvement of over 10% across six knowledge-intensive tasks, adaptable to various language model backbones, ranging from a dense 7B model to an 8x7B Mixture of Experts configuration. xRAG not only significantly outperforms previous context compression methods but also matches the performance of uncompressed models on several datasets, while reducing overall FLOPs by a factor of 3.53. Our work pioneers new directions in retrieval-augmented generation from the perspective of multimodality fusion, and we hope it lays the foundation for future efficient and scalable retrieval-augmented systems

[Arxiv](https://arxiv.org/abs/2405.13792)