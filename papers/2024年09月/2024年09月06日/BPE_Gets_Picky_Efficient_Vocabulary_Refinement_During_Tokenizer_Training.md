# BPE 训练中，词汇细化更高效，分词更挑剔。

发布时间：2024年09月06日

`LLM理论` `机器学习`

> BPE Gets Picky: Efficient Vocabulary Refinement During Tokenizer Training

# 摘要

> 语言模型能从高效的标记化中获益匪浅，但目前仍依赖于经典的 BPE 算法。这种简单可靠的方法却可能导致训练不足的标记和次优压缩，进而影响下游性能。为此，我们推出了 Picky BPE，一种在训练过程中进行词汇细化的改进算法。它不仅提升了词汇效率，消除了训练不足的标记，还保持了文本压缩的优势。实验结果显示，Picky BPE 不仅未削弱下游性能，反而在多方面有所提升。

> Language models can largely benefit from efficient tokenization. However, they still mostly utilize the classical BPE algorithm, a simple and reliable method. This has been shown to cause such issues as under-trained tokens and sub-optimal compression that may affect the downstream performance. We introduce Picky BPE, a modified BPE algorithm that carries out vocabulary refinement during tokenizer training. Our method improves vocabulary efficiency, eliminates under-trained tokens, and does not compromise text compression. Our experiments show that our method does not reduce the downstream performance, and in several cases improves it.

[Arxiv](https://arxiv.org/abs/2409.04599)