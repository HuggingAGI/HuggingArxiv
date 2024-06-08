# 通过两阶段一致性学习压缩器提升检索增强型语言模型的性能

发布时间：2024年06月04日

`RAG

这篇论文主要关注的是检索增强型语言模型（RALMs）的性能提升，特别是通过一种创新的两阶段一致性学习方法来改进检索增强生成（RAG）的过程。这种方法旨在通过压缩检索信息来提高模型在文档相关任务上的性能，确保生成的摘要与教师模型的语义意图保持一致，并且忠实于原始检索文档。因此，这篇论文的内容与RAG框架紧密相关，属于RAG分类。` `问答系统` `文档检索`

> Enhancing Retrieval-Augmented LMs with a Two-stage Consistency Learning Compressor

# 摘要

> 尽管检索增强型语言模型（RALMs）广泛应用，但如何将这些模型与检索机制完美结合，以提升文档相关任务的性能，仍是一大挑战。虽然检索增强生成（RAG）等后处理方法取得了一定成功，但多数方法在区分信息相关性上仍显不足，导致输出可能出现不一致，降低精度，进而影响语言模型回答的真实性。为此，本研究提出了一种创新的两阶段一致性学习方法，旨在通过压缩检索信息来提升检索增强型语言模型的性能。该方法通过一致性学习，确保生成的摘要既与教师模型的语义意图保持一致，又忠实于原始检索文档。经过多个数据集的实证检验，该方法在问答任务上显著提升了精度和效率，超越了现有基准，并展示了对比学习与一致性学习在检索增强生成框架中的协同效应。

> Despite the prevalence of retrieval-augmented language models (RALMs), the seamless integration of these models with retrieval mechanisms to enhance performance in document-based tasks remains challenging. While some post-retrieval processing Retrieval-Augmented Generation (RAG) methods have achieved success, most still lack the ability to distinguish pertinent from extraneous information, leading to potential inconsistencies and reduced precision in the generated output, which subsequently affects the truthfulness of the language model's responses. To address these limitations, this work proposes a novel two-stage consistency learning approach for retrieved information compression in retrieval-augmented language models to enhance performance. By incorporating consistency learning, the aim is to generate summaries that maintain coherence and alignment with the intended semantic representations of a teacher model while improving faithfulness to the original retrieved documents. The proposed method is empirically validated across multiple datasets, demonstrating notable enhancements in precision and efficiency for question-answering tasks. It outperforms existing baselines and showcases the synergistic effects of combining contrastive and consistency learning paradigms within the retrieval-augmented generation framework.

[Arxiv](https://arxiv.org/abs/2406.02266)