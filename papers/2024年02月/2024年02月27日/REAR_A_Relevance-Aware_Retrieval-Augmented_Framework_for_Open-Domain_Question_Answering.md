# [REAR 是一个专为解决开放领域问题而设计的智能框架，它融合了相关性感知检索技术以增强其功能。这个新颖的框架通过利用相关性意识提升信息检索能力，在开放领域问题回答任务中展现出卓越性能。](https://arxiv.org/abs/2402.17497)

发布时间：2024年02月27日

`RAG`

> REAR: A Relevance-Aware Retrieval-Augmented Framework for Open-Domain Question Answering

> 考虑到LLMs内在参数知识有限，RAG技术被广泛应用于拓宽其知识视野。然而，在当前方法中，LLMs难以精准衡量检索到的文档相关性，这可能导致对外部知识的误用。因此，本论文提出了名为REAR的开放领域问答（QA）解决方案，它是一种基于相关性感知的检索增强方法。核心目标在于提升LLMs对于源信息相关性的自认知能力，使其在RAG系统中能更灵活地运用外部知识。为此，我们创新设计了一种包含特制排名头的LLM-RAG新架构，以精确评估检索文档的相关性。同时，我们引入了基于双粒度相关性融合和抗噪训练的优化训练方法。得益于架构与训练方式的双重改进，REAR能够更高效地识别并利用检索文档的相关性，从而实现对外部知识的更好利用。实验证明，在四个开放领域的QA任务中，REAR相较于先前多款竞争激烈的RAG方法取得了显著优势。我们的代码和数据已发布在https://github.com/RUCAIBox/REAR平台上。

> Considering the limited internal parametric knowledge, retrieval-augmented generation (RAG) has been widely used to extend the knowledge scope of large language models (LLMs). Despite the extensive efforts on RAG research, in existing methods, LLMs cannot precisely assess the relevance of retrieved documents, thus likely leading to misleading or even incorrect utilization of external knowledge (i.e., retrieved documents). To address this issue, in this paper, we propose REAR, a RElevance-Aware Retrieval-augmented approach for open-domain question answering (QA). As the key motivation, we aim to enhance the self-awareness of source relevance for LLMs, so as to adaptively utilize external knowledge in RAG systems. Specially, we develop a new architecture for LLM based RAG system, by incorporating a specially designed rank head that precisely assesses the relevance of retrieved documents. Furthermore, we propose an improved training method based on bi-granularity relevance fusion and noise-resistant training. By combining the improvements in both architecture and training, our proposed REAR can better utilize external knowledge by effectively perceiving the relevance of retrieved documents. Experiments on four open-domain QA tasks show that REAR significantly outperforms previous a number of competitive RAG approaches. Our code and data can be accessed at https://github.com/RUCAIBox/REAR.

[Arxiv](https://arxiv.org/abs/2402.17497)