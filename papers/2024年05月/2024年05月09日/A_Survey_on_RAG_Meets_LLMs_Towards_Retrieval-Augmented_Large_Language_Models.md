# 《RAG与大型语言模型：探索检索增强型LLM之路》调研报告

发布时间：2024年05月09日

`RAG

这篇论文摘要主要讨论了检索增强生成（RAG）技术在大型语言模型（LLMs）中的应用，以及它如何通过利用外部知识库来提升生成质量。它涵盖了RAG的架构、训练策略和应用，并对当前研究进行了综述，分析了挑战和应对能力，同时提出了未来研究的方向。因此，它属于RAG分类。` `人工智能` `内容生成`

> A Survey on RAG Meets LLMs: Towards Retrieval-Augmented Large Language Models

# 摘要

> 检索增强生成（RAG）技术，作为AI领域的尖端技术，能够提供可靠且最新的外部知识，极大地便利了各种任务。在AI内容生成的浪潮中，RAG通过其强大的检索能力为生成式AI提供了额外的知识，助力其产出高质量内容。尽管大型语言模型（LLMs）在语言处理上展现了突破性的能力，但仍受限于内部知识的幻觉和过时。因此，检索增强的LLMs应运而生，它们利用外部权威知识库，而非仅依赖内部知识，以提升生成质量。本综述全面审视了RA-LLMs的研究现状，从架构、训练策略到应用三个技术层面进行探讨。我们首先概述了LLMs的基础和进展，随后根据应用领域对相关研究进行了分类，并深入分析了每个领域的挑战及RA-LLMs的应对能力。最后，我们探讨了当前研究的局限，并展望了未来研究的可能方向。

> As one of the most advanced techniques in AI, Retrieval-Augmented Generation (RAG) techniques can offer reliable and up-to-date external knowledge, providing huge convenience for numerous tasks. Particularly in the era of AI-generated content (AIGC), the powerful capacity of retrieval in RAG in providing additional knowledge enables retrieval-augmented generation to assist existing generative AI in producing high-quality outputs. Recently, large Language Models (LLMs) have demonstrated revolutionary abilities in language understanding and generation, while still facing inherent limitations, such as hallucinations and out-of-date internal knowledge. Given the powerful abilities of RAG in providing the latest and helpful auxiliary information, retrieval-augmented large language models have emerged to harness external and authoritative knowledge bases, rather than solely relying on the model's internal knowledge, to augment the generation quality of LLMs. In this survey, we comprehensively review existing research studies in retrieval-augmented large language models (RA-LLMs), covering three primary technical perspectives: architectures, training strategies, and applications. As the preliminary knowledge, we briefly introduce the foundations and recent advances of LLMs. Then, to illustrate the practical significance of RAG for LLMs, we categorize mainstream relevant work by application areas, detailing specifically the challenges of each and the corresponding capabilities of RA-LLMs. Finally, to deliver deeper insights, we discuss current limitations and several promising directions for future research.

[Arxiv](https://arxiv.org/abs/2405.06211)