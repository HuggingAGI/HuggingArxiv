# 词汇基础的子词划分

发布时间：2024年06月19日

`RAG

理由：这篇论文主要关注的是分词与子词分割技术，提出了三种创新方法，并评估了它们在词性标注和机器翻译任务中的性能。这些技术与RAG（Retrieval-Augmented Generation）模型中的分词和子词处理相关，因为RAG模型在处理文本时也需要有效的分词策略来提高生成文本的质量和效率。虽然论文没有直接提及大型语言模型（LLM）的应用或理论，但其研究内容与RAG模型中的技术问题紧密相关，因此归类为RAG。` `机器翻译`

> Lexically Grounded Subword Segmentation

# 摘要

> 我们提出了三项创新，涉及分词与子词分割技术。首先，我们采用无监督形态分析工具Morfessor进行预分词处理。其次，我们开发了一种代数方法，用于在词嵌入空间中获取子词嵌入，并据此设计了一种考虑词汇意义的子词分割新算法。第三，我们推出了一种高效的基于子词二元模型的分割算法，该算法在推理阶段可利用具有词汇意识的分割方法进行初始化，从而无需依赖Morfessor和庞大的嵌入表。通过两种内在度量标准，我们评估了这些方法，并在词性标注和机器翻译两个下游任务上测试了它们的性能。实验结果表明，在分割精度评估中，形态合理性显著提升，并在8种语言中实现了Rényi效率的改进。虽然这些分词方法对自动翻译质量的影响有限，但在词性标注这一形态学特征更为显著的任务中，我们观察到了持续的性能提升。

> We present three innovations in tokenization and subword segmentation. First, we propose to use unsupervised morphological analysis with Morfessor as pre-tokenization. Second, we present an algebraic method for obtaining subword embeddings grounded in a word embedding space. Based on that, we design a novel subword segmentation algorithm that uses the embeddings, ensuring that the procedure considers lexical meaning. Third, we introduce an efficient segmentation algorithm based on a subword bigram model that can be initialized with the lexically aware segmentation method to avoid using Morfessor and large embedding tables at inference time. We evaluate the proposed approaches using two intrinsic metrics and measure their performance on two downstream tasks: part-of-speech tagging and machine translation. Our experiments show significant improvements in the morphological plausibility of the segmentation when evaluated using segmentation precision on morpheme boundaries and improved Rényi efficiency in 8 languages. Although the proposed tokenization methods do not have a large impact on automatic translation quality, we observe consistent performance gains in the arguably more morphological task of part-of-speech tagging.

[Arxiv](https://arxiv.org/abs/2406.13560)