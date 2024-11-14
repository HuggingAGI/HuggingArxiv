# 字节对编码的理论分析

发布时间：2024年11月13日

`LLM理论` `机器翻译`

> Theoretical Analysis of Byte-Pair Encoding

# 摘要

> 字节对编码（BPE）是一种广泛用于子词标记化的方法，起源于基于语法的文本压缩。它被用于各种语言处理任务，如机器翻译或大型语言模型（LLM）预训练，以创建规定大小的标记字典。到目前为止，对 BPE 的大多数评估都是经验性的，其良好实际性能的原因尚未得到很好的理解。

在本文中，我们关注 BPE 背后的优化问题：找到实现最佳压缩效用的对编码。我们表明这个问题是 APX 完全的，这表明它不太可能承认多项式时间近似方案。这以更有力的形式回答了 Zouhar 等人最近提出的一个问题。

从积极的方面来看，我们表明 BPE 将最优对编码的压缩效用近似到最坏情况因子在 0.333 和 0.625 之间。我们的结果旨在解释 BPE 持续的成功，据我们所知，这是对其压缩效用适用于所有输入的第一个严格保证。

> Byte-Pair Encoding (BPE) is a widely used method for subword tokenization, with origins in grammar-based text compression. It is employed in a variety of language processing tasks such as machine translation or large language model (LLM) pretraining, to create a token dictionary of a prescribed size. Most evaluations of BPE to date are empirical, and the reasons for its good practical performance are not well understood.
  In this paper we focus on the optimization problem underlying BPE: finding a pair encoding that achieves optimal compression utility. We show that this problem is APX-complete, indicating that it is unlikely to admit a polynomial-time approximation scheme. This answers, in a stronger form, a question recently raised by Zouhar et al.
  On the positive side, we show that BPE approximates the compression utility of the optimal pair encoding to a worst-case factor between $0.333$ and $0.625$. Our results aim to explain the ongoing success of BPE and are, to our knowledge, the first rigorous guarantees on its compression utility that hold for all inputs.

[Arxiv](https://arxiv.org/abs/2411.08671)