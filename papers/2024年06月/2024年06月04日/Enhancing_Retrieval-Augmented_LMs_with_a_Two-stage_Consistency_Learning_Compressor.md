# 利用两阶段一致性学习压缩技术，提升检索增强语言模型的性能

发布时间：2024年06月04日

`RAG

理由：这篇论文主要关注的是检索增强型语言模型（RALMs）的性能优化，特别是通过一种创新的两阶段一致性学习方法来改进检索增强生成（RAG）的过程。论文的核心贡献在于提出了一种新的方法来优化RAG的性能，确保生成的摘要与教师模型的语义意图保持一致，同时忠实于原始文档。这与RAG的分类最为吻合，因为它直接涉及到了检索增强生成的方法和应用。` `问答系统` `文档处理`

> Enhancing Retrieval-Augmented LMs with a Two-stage Consistency Learning Compressor

# 摘要

> 尽管检索增强型语言模型（RALMs）广泛应用，但如何将这些模型与检索机制完美结合，以提升文档相关任务的性能，仍是一大挑战。虽然检索增强生成（RAG）等后处理方法取得了一定成功，但多数方法仍难以区分信息的相关性，导致输出可能出现不一致，降低了精度，进而影响语言模型回答的真实性。为此，本研究提出了一种创新的两阶段一致性学习方法，旨在通过压缩检索信息来优化RALMs的性能。该方法通过一致性学习，确保生成的摘要既与教师模型的语义意图保持一致，又忠实于原始文档。经过多数据集的实证检验，该方法在问答任务中显著提升了精度和效率，超越了现有技术，并展示了对比学习与一致性学习在检索增强生成框架中的协同效应。

> Despite the prevalence of retrieval-augmented language models (RALMs), the seamless integration of these models with retrieval mechanisms to enhance performance in document-based tasks remains challenging. While some post-retrieval processing Retrieval-Augmented Generation (RAG) methods have achieved success, most still lack the ability to distinguish pertinent from extraneous information, leading to potential inconsistencies and reduced precision in the generated output, which subsequently affects the truthfulness of the language model's responses. To address these limitations, this work proposes a novel two-stage consistency learning approach for retrieved information compression in retrieval-augmented language models to enhance performance. By incorporating consistency learning, the aim is to generate summaries that maintain coherence and alignment with the intended semantic representations of a teacher model while improving faithfulness to the original retrieved documents. The proposed method is empirically validated across multiple datasets, demonstrating notable enhancements in precision and efficiency for question-answering tasks. It outperforms existing baselines and showcases the synergistic effects of combining contrastive and consistency learning paradigms within the retrieval-augmented generation framework.

[Arxiv](https://arxiv.org/abs/2406.02266)