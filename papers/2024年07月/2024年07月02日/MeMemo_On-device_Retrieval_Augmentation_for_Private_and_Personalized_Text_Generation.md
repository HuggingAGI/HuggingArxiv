# MeMemo：实现设备端检索增强，助力私密且个性化的文本生成

发布时间：2024年07月02日

`RAG` `软件开发` `网络安全`

> MeMemo: On-device Retrieval Augmentation for Private and Personalized Text Generation

# 摘要

> RAG 通过从外部知识库检索信息，有效解决了 LLM 的幻觉问题。但现有方法依赖专用服务器，限制了其在高度隐私敏感领域的应用。为此，我们推出了 MeMemo，首个开源 JavaScript 工具包，将 HNSW 技术引入浏览器环境。借助现代 Web 技术，MeMemo 利用客户端硬件，支持在浏览器中高效处理高维向量搜索，为私密个性化内容创作和交互式原型设计等新机遇铺平道路。MeMemo 已在 GitHub 上发布，我们同时探讨了设备上密集检索的机遇与挑战。

> Retrieval-augmented text generation (RAG) addresses the common limitations of large language models (LLMs), such as hallucination, by retrieving information from an updatable external knowledge base. However, existing approaches often require dedicated backend servers for data storage and retrieval, thereby limiting their applicability in use cases that require strict data privacy, such as personal finance, education, and medicine. To address the pressing need for client-side dense retrieval, we introduce MeMemo, the first open-source JavaScript toolkit that adapts the state-of-the-art approximate nearest neighbor search technique HNSW to browser environments. Developed with modern and native Web technologies, such as IndexedDB and Web Workers, our toolkit leverages client-side hardware capabilities to enable researchers and developers to efficiently search through millions of high-dimensional vectors in the browser. MeMemo enables exciting new design and research opportunities, such as private and personalized content creation and interactive prototyping, as demonstrated in our example application RAG Playground. Reflecting on our work, we discuss the opportunities and challenges for on-device dense retrieval. MeMemo is available at https://github.com/poloclub/mememo.

[Arxiv](https://arxiv.org/abs/2407.01972)