# MultiTok：源自 LZW 压缩、适用于高效 LLM 的可变长度标记化

发布时间：2024年10月28日

`LLM应用` `人工智能`

> MultiTok: Variable-Length Tokenization for Efficient LLMs Adapted from LZW Compression

# 摘要

> 大型语言模型凭借引入更复杂的自然语言处理技术，大幅改变了人工智能的发展前景。但当下训练这类大型语言模型的方式需要诸多资源，比如大量数据、昂贵的设备以及漫长的训练时长。为解决此难题，本文提出一种受通用 Lempel-Ziv-Welch 数据压缩启发的新标记化方法，把重复的短语压缩成多词标记。以 MultiTok 作为新的标记化工具，我们发现语言模型能够更高效地训练，而且在更精简和压缩的训练数据上能达到近似的准确率。实际上，我们的结果显示，MultiTok 作为标记器的表现与 BERT 标准相当，同时训练速度快近 2.5 倍，所需训练数据减少 30% 以上。

> Large language models have drastically changed the prospects of AI by introducing technologies for more complex natural language processing. However, current methodologies to train such LLMs require extensive resources including but not limited to large amounts of data, expensive machinery, and lengthy training. To solve this problem, this paper proposes a new tokenization method inspired by universal Lempel-Ziv-Welch data compression that compresses repetitive phrases into multi-word tokens. With MultiTok as a new tokenizing tool, we show that language models are able to be trained notably more efficiently while offering a similar accuracy on more succinct and compressed training data. In fact, our results demonstrate that MultiTok achieves a comparable performance to the BERT standard as a tokenizer while also providing close to 2.5x faster training with more than 30% less training data.

[Arxiv](https://arxiv.org/abs/2410.21548)