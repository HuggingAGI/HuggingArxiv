# HippoRAG：神经生物学启发的 LLM 长期记忆机制

发布时间：2024年05月23日

`RAG

理由：这篇论文介绍了一种名为HippoRAG的新型检索框架，该框架受人类长期记忆中海马体索引理论的启发，旨在通过新经验实现更深层次和更高效的知识整合。它结合了大型语言模型（LLMs）、知识图谱和个人化PageRank算法，并在多跳问答任务上展示了显著的性能提升。这表明论文主要关注的是检索增强生成（RAG）技术的发展和应用，因此归类为RAG。` `人工智能` `问答系统`

> HippoRAG: Neurobiologically Inspired Long-Term Memory for Large Language Models

# 摘要

> 为了在多变的自然环境中蓬勃发展，哺乳动物的大脑进化出了存储大量世界知识并持续吸收新信息的能力，同时避免灾难性遗忘。尽管大型语言模型（LLMs）取得了显著成就，即使在检索增强生成（RAG）的帮助下，它们在预训练后仍难以高效有效地整合大量新经验。为此，我们提出了HippoRAG，这是一种受人类长期记忆中海马体索引理论启发的新型检索框架，旨在通过新经验实现更深层次和更高效的知识整合。HippoRAG巧妙地结合了LLMs、知识图谱和个人化PageRank算法，模拟了人类记忆中新皮质和海马体的不同功能。在多跳问答任务上，HippoRAG显著优于现有RAG方法，性能提升高达20%。使用HippoRAG的单步检索不仅在性能上与迭代检索如IRCoT相当或更优，而且成本降低10-30倍，速度快6-13倍。将HippoRAG整合到IRCoT中进一步带来了显著的性能提升。此外，我们的方法还能处理现有方法无法触及的新类型场景。代码和数据可在https://github.com/OSU-NLP-Group/HippoRAG获取。

> In order to thrive in hostile and ever-changing natural environments, mammalian brains evolved to store large amounts of knowledge about the world and continually integrate new information while avoiding catastrophic forgetting. Despite the impressive accomplishments, large language models (LLMs), even with retrieval-augmented generation (RAG), still struggle to efficiently and effectively integrate a large amount of new experiences after pre-training. In this work, we introduce HippoRAG, a novel retrieval framework inspired by the hippocampal indexing theory of human long-term memory to enable deeper and more efficient knowledge integration over new experiences. HippoRAG synergistically orchestrates LLMs, knowledge graphs, and the Personalized PageRank algorithm to mimic the different roles of neocortex and hippocampus in human memory. We compare HippoRAG with existing RAG methods on multi-hop question answering and show that our method outperforms the state-of-the-art methods remarkably, by up to 20%. Single-step retrieval with HippoRAG achieves comparable or better performance than iterative retrieval like IRCoT while being 10-30 times cheaper and 6-13 times faster, and integrating HippoRAG into IRCoT brings further substantial gains. Finally, we show that our method can tackle new types of scenarios that are out of reach of existing methods. Code and data are available at https://github.com/OSU-NLP-Group/HippoRAG.

[Arxiv](https://arxiv.org/abs/2405.14831)