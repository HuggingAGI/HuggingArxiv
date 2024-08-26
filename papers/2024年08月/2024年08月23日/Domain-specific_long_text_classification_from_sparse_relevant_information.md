# 从稀疏信息中提取特定领域长文本分类

发布时间：2024年08月23日

`LLM应用`

> Domain-specific long text classification from sparse relevant information

# 摘要

> 大型语言模型已经彻底改变了自然语言处理领域，但当相关信息稀疏或信号微弱时，这些模型的统计机制难以有效利用这些信息。例如，在医疗领域，确定报告是否包含关键患者信息至关重要，而这些信息往往依赖于少数特定术语。为此，我们提出了一种分层模型，通过利用潜在目标术语的短列表来检索和表示候选句子，最终通过术语嵌入的池化来分类文档。实验表明，在特定领域上下文中，我们的分层模型在检索相关长文档方面优于大型语言模型。

> Large Language Models have undoubtedly revolutionized the Natural Language Processing field, the current trend being to promote one-model-for-all tasks (sentiment analysis, translation, etc.). However, the statistical mechanisms at work in the larger language models struggle to exploit the relevant information when it is very sparse, when it is a weak signal. This is the case, for example, for the classification of long domain-specific documents, when the relevance relies on a single relevant word or on very few relevant words from technical jargon. In the medical domain, it is essential to determine whether a given report contains critical information about a patient's condition. This critical information is often based on one or few specific isolated terms. In this paper, we propose a hierarchical model which exploits a short list of potential target terms to retrieve candidate sentences and represent them into the contextualized embedding of the target term(s) they contain. A pooling of the term(s) embedding(s) entails the document representation to be classified. We evaluate our model on one public medical document benchmark in English and on one private French medical dataset. We show that our narrower hierarchical model is better than larger language models for retrieving relevant long documents in a domain-specific context.

[Arxiv](https://arxiv.org/abs/2408.13253)