# 越南法律问答系统中的信息检索

发布时间：2024年09月04日

`RAG` `问答系统`

> Vietnamese Legal Information Retrieval in Question-Answering System

# 摘要

> 在数据爆炸的时代，准确检索和推荐相关文档对提升问答系统可靠性至关重要。检索增强生成（RAG）通过解决QA系统中的幻觉问题，显著提升了大型语言模型（LLM）的能力，尤其在法律领域。尽管有多种方法如密集向量嵌入的语义搜索，但这些方法在处理越南语时因数据处理效率低和集成技术简单而效果不佳。此外，相关文档的排序问题常被忽视。为此，我们采取了三项主要改进：探索实用数据处理方法、增强互惠排名融合、使用主动检索重新排序源信息。这些改进不仅提升了用户体验，还可能开创一种新的重新排序方法。最终，这些技术被整合进一个综合QA系统，大幅提升了其性能和可靠性。

> In the modern era of rapidly increasing data volumes, accurately retrieving and recommending relevant documents has become crucial in enhancing the reliability of Question Answering (QA) systems. Recently, Retrieval Augmented Generation (RAG) has gained significant recognition for enhancing the capabilities of large language models (LLMs) by mitigating hallucination issues in QA systems, which is particularly beneficial in the legal domain. Various methods, such as semantic search using dense vector embeddings or a combination of multiple techniques to improve results before feeding them to LLMs, have been proposed. However, these methods often fall short when applied to the Vietnamese language due to several challenges, namely inefficient Vietnamese data processing leading to excessive token length or overly simplistic ensemble techniques that lead to instability and limited improvement. Moreover, a critical issue often overlooked is the ordering of final relevant documents which are used as reference to ensure the accuracy of the answers provided by LLMs. In this report, we introduce our three main modifications taken to address these challenges. First, we explore various practical approaches to data processing to overcome the limitations of the embedding model. Additionally, we enhance Reciprocal Rank Fusion by normalizing order to combine results from keyword and vector searches effectively. We also meticulously re-rank the source pieces of information used by LLMs with Active Retrieval to improve user experience when refining the information generated. In our opinion, this technique can also be considered as a new re-ranking method that might be used in place of the traditional cross encoder. Finally, we integrate these techniques into a comprehensive QA system, significantly improving its performance and reliability

[Arxiv](https://arxiv.org/abs/2409.13699)