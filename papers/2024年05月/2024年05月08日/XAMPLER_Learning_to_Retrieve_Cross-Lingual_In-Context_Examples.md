# XAMPLER：掌握跨语言上下文示例的检索艺术

发布时间：2024年05月08日

`RAG

这篇论文介绍了一种名为XAMPLER的跨语言示例检索方法，旨在解决资源匮乏语言的上下文学习问题。它通过利用多语言大型语言模型的预测结果来训练检索器，并使用该检索器检索英语示例以支持目标语言的上下文学习。这种方法属于检索增强生成（RAG）的范畴，因为它涉及检索过程来增强语言模型的性能。因此，我将这篇论文分类为RAG。` `跨语言学习`

> XAMPLER: Learning to Retrieve Cross-Lingual In-Context Examples

# 摘要

> 最新研究表明，利用经过微调的检索器来获取高质量的上下文示例，极大地提升了英语的上下文学习效果。然而，将此类方法应用于其他语言，尤其是资源匮乏的语言，却因缺乏跨语言检索器和标注数据而面临挑战。本文推出的XAMPLER，即跨语言示例检索，专为解决这一难题而生，它仅依赖标注的英语数据进行跨语言上下文学习。XAMPLER首先通过多语言大型语言模型的预测结果构建正负英语样本，以此训练检索器。随后，该检索器被用于直接检索英语示例，作为目标语言上下文学习的少量示例。在SIB200多语言文本分类基准上，对176种语言的实验结果显示，XAMPLER在跨语言上下文学习方面取得了显著进步，相关代码已公开于https://github.com/cisnlp/XAMPLER。

> Recent studies have shown that leveraging off-the-shelf or fine-tuned retrievers, capable of retrieving high-quality in-context examples, significantly improves in-context learning of English. However, adapting these methods to other languages, especially low-resource ones, presents challenges due to the scarcity of available cross-lingual retrievers and annotated data. In this paper, we introduce XAMPLER: Cross-Lingual Example Retrieval, a method tailored to tackle the challenge of cross-lingual in-context learning using only annotated English data. XAMPLER first trains a retriever with positive/negative English samples, which are constructed based on the predictions of the multilingual large language model for in-context learning. Then, the trained retriever is directly employed to retrieve English examples as few-shot examples for in-context learning of target languages. Experiments on the massively multilingual text classification benchmark of SIB200 with 176 languages demonstrate that XAMPLER substantially improves the in-context learning performance across languages. Our code is available at https://github.com/cisnlp/XAMPLER.

[Arxiv](https://arxiv.org/abs/2405.05116)