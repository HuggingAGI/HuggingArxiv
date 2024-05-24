# IM-RAG：借助内心独白学习，实现多轮检索增强生成

发布时间：2024年05月15日

`RAG

这篇论文主要探讨了RAG（Retrieval-Augmented Generation）范式在大型语言模型（LLMs）中的应用，特别是在提升检索系统的性能和解释性方面。论文提出了IM-RAG方法，这是一种集成检索系统的新方法，通过学习内部独白（IM）来实现多轮RAG。这种方法的核心是利用LLM作为推理者，通过强化学习和监督微调来优化整个过程。因此，这篇论文更偏向于RAG范式的改进和应用，而不是Agent、LLM应用或LLM理论。` `问答系统`

> IM-RAG: Multi-Round Retrieval-Augmented Generation Through Learning Inner Monologues

# 摘要

> 尽管RAG范式能利用外部知识提升LLMs的输出，减轻生成幻觉和知识库静态问题，但在采用不同能力的检索系统、多轮检索的解释性以及端到端优化方面仍显不足。为此，我们提出了IM-RAG，一种以LLM为核心的集成检索系统的新方法，通过学习内部独白（IM）来实现多轮RAG。在此过程中，LLM作为核心推理者，或提出查询以获取更多信息，或基于对话上下文给出答案。我们还引入了精炼器，优化检索器输出，促进推理者与不同检索模块间的多轮交流。整个过程通过强化学习优化，引入进度跟踪器提供中间奖励，答案预测则通过监督微调单独优化。在HotPotQA数据集上的实验表明，我们的方法不仅达到了SOTA性能，还展现了集成检索模块的高灵活性和内部独白的强解释性。

> Although the Retrieval-Augmented Generation (RAG) paradigms can use external knowledge to enhance and ground the outputs of Large Language Models (LLMs) to mitigate generative hallucinations and static knowledge base problems, they still suffer from limited flexibility in adopting Information Retrieval (IR) systems with varying capabilities, constrained interpretability during the multi-round retrieval process, and a lack of end-to-end optimization. To address these challenges, we propose a novel LLM-centric approach, IM-RAG, that integrates IR systems with LLMs to support multi-round RAG through learning Inner Monologues (IM, i.e., the human inner voice that narrates one's thoughts). During the IM process, the LLM serves as the core reasoning model (i.e., Reasoner) to either propose queries to collect more information via the Retriever or to provide a final answer based on the conversational context. We also introduce a Refiner that improves the outputs from the Retriever, effectively bridging the gap between the Reasoner and IR modules with varying capabilities and fostering multi-round communications. The entire IM process is optimized via Reinforcement Learning (RL) where a Progress Tracker is incorporated to provide mid-step rewards, and the answer prediction is further separately optimized via Supervised Fine-Tuning (SFT). We conduct extensive experiments with the HotPotQA dataset, a popular benchmark for retrieval-based, multi-step question-answering. The results show that our approach achieves state-of-the-art (SOTA) performance while providing high flexibility in integrating IR modules as well as strong interpretability exhibited in the learned inner monologues.

[Arxiv](https://arxiv.org/abs/2405.13021)