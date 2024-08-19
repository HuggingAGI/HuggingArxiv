# 分词空间中的信号藏于何处？

发布时间：2024年08月16日

`LLM理论` `人工智能`

> Where is the signal in tokenization space?

# 摘要

> 大型语言模型 (LLM) 通常使用确定性标记器将文本编码为规范令牌序列，并为其分配概率。然而，字符串的标记化并非唯一，例如 Llama2 标记器可能将 "Tokens" 编码为 [Tok,ens] 或 [Tok,en,s]。本文探讨非规范标记化，证明找到最可能的标记化及计算边际概率在计算上具有挑战性。尽管如此，边际概率与规范概率在多数情况下难以区分。实证研究发现，标记化空间中隐藏着丰富信号。通过聚合非规范标记化概率，我们在多种架构的 LLM 评估基准上取得了显著改进。

> Large Language Models (LLMs) are typically shipped with tokenizers that deterministically encode text into so-called canonical token sequences, to which the LLMs assign probability values. One common assumption is that the probability of a piece of text is the probability of its canonical token sequence. However, the tokenization of a string is not unique: e.g., the Llama2 tokenizer encodes Tokens as [Tok,ens], but [Tok,en,s] also represents the same text. In this paper, we study non-canonical tokenizations. We prove that, given a string, it is computationally hard to find the most likely tokenization for an autoregressive LLM, as well as to compute the marginal probability over all possible tokenizations. We then show how the marginal is, in most cases, indistinguishable from the canonical probability. Surprisingly, we then empirically demonstrate the existence of a significant amount of signal hidden within tokenization space. Notably, by simply aggregating the probabilities of non-canonical tokenizations, we achieve improvements across a range of LLM evaluation benchmarks for a variety of architectures, including transformers and state space models.

[Arxiv](https://arxiv.org/abs/2408.08541)