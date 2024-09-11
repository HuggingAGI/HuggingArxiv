# 通过多任务方式，深入挖掘意大利语句子嵌入的特性

发布时间：2024年09月10日

`LLM应用` `语言学`

> Exploring Italian sentence embeddings properties through multi-tasking

# 摘要

> 我们探索了现有LLM在多任务环境下意大利语中抽象语言信息的编码程度。通过使用大规模的意大利语BLM问题合成数据，我们研究了预训练语言模型构建的句子表示如何编码特定句法和语义信息。采用两层架构，我们分别压缩句子嵌入以包含任务相关信息，并进行BLM任务。我们进一步探讨是否能获得编码多任务相关句法和语义信息的压缩表示。尽管预期句子结构和块属性可在任务间共享，但性能与错误分析表明，不同任务的线索在句子嵌入中以不同方式编码，暗示抽象语言概念如成分或主题角色可能未被预训练嵌入所捕捉。

> We investigate to what degree existing LLMs encode abstract linguistic information in Italian in a multi-task setting. We exploit curated synthetic data on a large scale -- several Blackbird Language Matrices (BLMs) problems in Italian -- and use them to study how sentence representations built using pre-trained language models encode specific syntactic and semantic information. We use a two-level architecture to model separately a compression of the sentence embeddings into a representation that contains relevant information for a task, and a BLM task. We then investigate whether we can obtain compressed sentence representations that encode syntactic and semantic information relevant to several BLM tasks. While we expected that the sentence structure -- in terms of sequence of phrases/chunks -- and chunk properties could be shared across tasks, performance and error analysis show that the clues for the different tasks are encoded in different manners in the sentence embeddings, suggesting that abstract linguistic notions such as constituents or thematic roles does not seem to be present in the pretrained sentence embeddings.

[Arxiv](https://arxiv.org/abs/2409.06622)