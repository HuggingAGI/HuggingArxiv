# 通过两阶段一致性学习压缩技术，提升检索增强语言模型的性能

发布时间：2024年06月04日

`RAG

这篇论文主要探讨了检索增强型语言模型（RALMs）与检索机制的结合问题，并提出了一种两阶段一致性学习方法来提升这些模型的性能。这种方法特别关注于通过压缩检索信息来提高模型生成内容的一致性和准确性。由于论文的核心在于改进检索增强生成（RAG）方法，因此将其归类为RAG。` `问答系统` `文档检索`

> Enhancing Retrieval-Augmented LMs with a Two-stage Consistency Learning Compressor

# 摘要

> 尽管检索增强型语言模型（RALMs）广泛应用，但如何将这些模型与检索机制完美结合，以提升文档相关任务的性能，仍是一大挑战。虽然某些检索增强生成（RAG）方法在检索后处理方面取得了成功，但大多数方法仍难以区分相关与无关信息，导致生成的内容可能出现不一致，降低了准确性，进而影响语言模型回答的真实性。为此，本研究提出了一种创新的两阶段一致性学习方法，旨在通过压缩检索信息来提升检索增强型语言模型的性能。该方法通过一致性学习，旨在生成与教师模型的预期语义表示保持一致和同步的摘要，同时增强对原始检索文档的忠实度。在多个数据集上的实证验证表明，该方法在问答任务中显著提高了精度和效率，超越了现有基准，并展示了在检索增强生成框架内结合对比和一致性学习范式的协同效应。

> Despite the prevalence of retrieval-augmented language models (RALMs), the seamless integration of these models with retrieval mechanisms to enhance performance in document-based tasks remains challenging. While some post-retrieval processing Retrieval-Augmented Generation (RAG) methods have achieved success, most still lack the ability to distinguish pertinent from extraneous information, leading to potential inconsistencies and reduced precision in the generated output, which subsequently affects the truthfulness of the language model's responses. To address these limitations, this work proposes a novel two-stage consistency learning approach for retrieved information compression in retrieval-augmented language models to enhance performance. By incorporating consistency learning, the aim is to generate summaries that maintain coherence and alignment with the intended semantic representations of a teacher model while improving faithfulness to the original retrieved documents. The proposed method is empirically validated across multiple datasets, demonstrating notable enhancements in precision and efficiency for question-answering tasks. It outperforms existing baselines and showcases the synergistic effects of combining contrastive and consistency learning paradigms within the retrieval-augmented generation framework.

[Arxiv](https://arxiv.org/abs/2406.02266)