# xRAG：单令牌驱动，极致压缩上下文，助力检索增强生成
发布时间：2024年05月22日

`RAG`
> xRAG: Extreme Context Compression for Retrieval-augmented Generation with One Token
>
> 本文推出的xRAG，是一种针对检索增强生成量身定制的创新上下文压缩技术。它将传统仅用于检索的密集文档嵌入重新定义为检索模式的特征。通过模式融合技术，xRAG将这些嵌入无缝融入语言模型空间，大幅减少了对文本的需求，实现了极高的压缩效率。xRAG中唯一可调的部分是模式桥，检索器和语言模型则保持不变，这使得离线构建的文档嵌入得以复用，并保持了检索增强的即插即用特性。实验显示，xRAG在六个知识密集型任务上平均性能提升了10%以上，适用于从7B密集模型到8x7B专家混合配置的各种语言模型。xRAG不仅超越了以往的上下文压缩方法，还在多个数据集上与未压缩模型媲美，同时将总体计算量减少了3.53倍。我们的研究为检索增强生成的多模式融合开辟了新路径，并期望为未来高效可扩展的检索增强系统奠定基石。
>
> https://arxiv.org/abs/2405.13792


<hr />

- 论文原文: [https://arxiv.org/abs/2405.13792](https://arxiv.org/abs/2405.13792)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886