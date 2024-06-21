# 词汇基础的子词划分

发布时间：2024年06月19日

`RAG

理由：这篇论文主要关注的是分词和子词分割的创新方法，这些方法涉及使用无监督形态分析工具Morfessor进行预分词，以及开发新的代数方法和算法来处理子词嵌入和分割。这些技术主要用于改进自然语言处理（NLP）中的分词过程，这是RAG（Retrieval-Augmented Generation）模型中的一个关键组成部分，尤其是在处理词汇和子词级别的表示时。虽然这些方法可能对LLM（大型语言模型）的某些方面有所贡献，但它们的主要贡献在于分词和子词分割的改进，这是RAG模型中的一个特定技术领域。因此，将这篇论文分类为RAG更为合适。` `机器翻译`

> Lexically Grounded Subword Segmentation

# 摘要

> 我们提出了三项创新，涉及分词和子词分割。首先，我们采用无监督形态分析工具Morfessor进行预分词。其次，我们开发了一种代数方法，用于在词嵌入空间中获取子词嵌入，并据此设计了一种考虑词汇意义的子词分割算法。第三，我们推出了一种高效的基于子词二元模型的分割算法，该算法在推理时无需Morfessor和大型嵌入表，而是利用了具有词汇意识的分割方法。我们通过两个内在指标评估了这些方法，并在词性标注和机器翻译两个下游任务上测试了它们的性能。实验结果表明，在分割精度和Rényi效率方面，我们的方法在8种语言中均取得了显著提升。虽然这些分词方法对机器翻译质量的影响有限，但在词性标注这一形态学任务上，我们观察到了持续的性能提升。

> We present three innovations in tokenization and subword segmentation. First, we propose to use unsupervised morphological analysis with Morfessor as pre-tokenization. Second, we present an algebraic method for obtaining subword embeddings grounded in a word embedding space. Based on that, we design a novel subword segmentation algorithm that uses the embeddings, ensuring that the procedure considers lexical meaning. Third, we introduce an efficient segmentation algorithm based on a subword bigram model that can be initialized with the lexically aware segmentation method to avoid using Morfessor and large embedding tables at inference time. We evaluate the proposed approaches using two intrinsic metrics and measure their performance on two downstream tasks: part-of-speech tagging and machine translation. Our experiments show significant improvements in the morphological plausibility of the segmentation when evaluated using segmentation precision on morpheme boundaries and improved Rényi efficiency in 8 languages. Although the proposed tokenization methods do not have a large impact on automatic translation quality, we observe consistent performance gains in the arguably more morphological task of part-of-speech tagging.

[Arxiv](https://arxiv.org/abs/2406.13560)