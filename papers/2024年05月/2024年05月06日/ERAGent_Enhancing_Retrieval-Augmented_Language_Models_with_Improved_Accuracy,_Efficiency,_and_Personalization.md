# ERAGent：提升语言模型的检索增强能力，实现更精准、高效且个性化的语言处理

发布时间：2024年05月06日

`RAG

这篇论文介绍了一种名为ERAGent的新型框架，它专注于检索增强生成（RAG）技术，旨在解决现有RAG系统面临的挑战，如检索质量、知识重检索效率和个性化响应等问题。ERAGent通过引入增强问题重写器和知识过滤器来提升检索质量，并通过检索触发器减少不必要的外部知识检索。此外，它还通过学习用户配置文件来实现个性化响应。这些特点表明该论文属于RAG分类，因为它专注于改进和扩展RAG技术的功能和性能。` `人工智能助手` `问答系统`

> ERAGent: Enhancing Retrieval-Augmented Language Models with Improved Accuracy, Efficiency, and Personalization

# 摘要

> 检索增强生成（RAG）技术极大地提升了语言模型的理解能力。从最初的检索后阅读流程，到如今因集成多种组件而形成的复杂循环结构，RAG的发展历程令人瞩目。尽管在提升响应准确性方面取得了显著成就，但仍面临诸如复杂问题检索质量不佳、长期服务中知识重检索效率低下、个性化响应缺失等挑战。为此，我们推出了ERAGent，这一前沿框架在RAG领域迈出了重要一步。我们的创新在于引入了协同工作的增强问题重写器和知识过滤器，以提升检索质量。同时，检索触发器的加入有效减少了不必要的外部知识检索，确保了响应质量。ERAGent还通过学习用户配置文件来实现个性化响应。经验学习者模块的支持使得ERAGent在效率和个性化方面表现出色，AI助手能够不断扩展知识并逐步建模用户配置文件。在六个数据集和三个问答任务上的严格评估显示，ERAGent在准确性、效率和个性化方面均表现卓越，预示着其在推动RAG领域发展及实际应用中的巨大潜力。

> Retrieval-augmented generation (RAG) for language models significantly improves language understanding systems. The basic retrieval-then-read pipeline of response generation has evolved into a more extended process due to the integration of various components, sometimes even forming loop structures. Despite its advancements in improving response accuracy, challenges like poor retrieval quality for complex questions that require the search of multifaceted semantic information, inefficiencies in knowledge re-retrieval during long-term serving, and lack of personalized responses persist. Motivated by transcending these limitations, we introduce ERAGent, a cutting-edge framework that embodies an advancement in the RAG area. Our contribution is the introduction of the synergistically operated module: Enhanced Question Rewriter and Knowledge Filter, for better retrieval quality. Retrieval Trigger is incorporated to curtail extraneous external knowledge retrieval without sacrificing response quality. ERAGent also personalizes responses by incorporating a learned user profile. The efficiency and personalization characteristics of ERAGent are supported by the Experiential Learner module which makes the AI assistant being capable of expanding its knowledge and modeling user profile incrementally. Rigorous evaluations across six datasets and three question-answering tasks prove ERAGent's superior accuracy, efficiency, and personalization, emphasizing its potential to advance the RAG field and its applicability in practical systems.

[Arxiv](https://arxiv.org/abs/2405.06683)