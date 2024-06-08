# 采用两阶段一致性学习压缩器优化检索增强型语言模型

发布时间：2024年06月04日

`RAG

这篇论文主要探讨了检索增强型语言模型（RALMs）与检索机制的结合问题，并提出了一种两阶段一致性学习策略来优化这些模型的性能。这种方法特别关注于提升检索后信息的处理，以改善语言模型在文档相关任务中的表现。由于论文的核心内容是关于检索增强生成（RAG）方法的改进和优化，因此将其归类为RAG。` `问答系统` `文档检索`

> Enhancing Retrieval-Augmented LMs with a Two-stage Consistency Learning Compressor

# 摘要

> 尽管检索增强型语言模型（RALMs）广泛应用，但如何将这些模型与检索机制完美结合，以提升文档相关任务的性能，仍是一大挑战。虽然某些检索增强生成（RAG）方法在处理检索后信息方面取得了进展，但多数方法仍难以区分信息的相关性，导致输出结果可能出现不一致和精度下降，进而影响语言模型回答的真实性。为此，本研究提出了一种创新的两阶段一致性学习策略，旨在通过压缩检索信息来优化RALMs的性能。该策略通过一致性学习，旨在生成既与教师模型的语义意图保持一致，又忠实于原始检索文档的摘要。经过多数据集的实证检验，该方法在问答任务中显著提升了精度和效率，超越了现有基准，并展示了在检索增强生成框架内融合对比与一致性学习范式的协同效应。

> Despite the prevalence of retrieval-augmented language models (RALMs), the seamless integration of these models with retrieval mechanisms to enhance performance in document-based tasks remains challenging. While some post-retrieval processing Retrieval-Augmented Generation (RAG) methods have achieved success, most still lack the ability to distinguish pertinent from extraneous information, leading to potential inconsistencies and reduced precision in the generated output, which subsequently affects the truthfulness of the language model's responses. To address these limitations, this work proposes a novel two-stage consistency learning approach for retrieved information compression in retrieval-augmented language models to enhance performance. By incorporating consistency learning, the aim is to generate summaries that maintain coherence and alignment with the intended semantic representations of a teacher model while improving faithfulness to the original retrieved documents. The proposed method is empirically validated across multiple datasets, demonstrating notable enhancements in precision and efficiency for question-answering tasks. It outperforms existing baselines and showcases the synergistic effects of combining contrastive and consistency learning paradigms within the retrieval-augmented generation framework.

[Arxiv](https://arxiv.org/abs/2406.02266)