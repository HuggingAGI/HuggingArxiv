# LBPE：长标记优先标记化以改进大型语言模型

发布时间：2024年11月08日

`LLM理论` `语言模型`

> LBPE: Long-token-first Tokenization to Improve Large Language Models

# 摘要

> 在大型语言模型（LLM）中普遍使用的字节对编码（BPE）有助于对子词单元进行稳健处理，并避免了词汇外单词的问题。尽管它取得了成功，但一个关键挑战仍然存在：在标记化的数据集中，语义信息丰富的长标记与短标记相比出现的次数较少，这可能导致不同标记之间的学习不平衡问题。为了解决这个问题，我们提出了 LBPE，它在编码过程中优先考虑长标记。LBPE 根据标记长度的反向排名而不是词汇中的排名生成标记，在编码过程中给予长标记更高的优先级。因此，LBPE 平滑了短标记和长标记之间的频率差异，从而减轻了学习不平衡。在各种语言建模任务中的大量实验表明，LBPE 始终优于原始的 BPE，很好地证明了其有效性。

> The prevalent use of Byte Pair Encoding (BPE) in Large Language Models (LLMs) facilitates robust handling of subword units and avoids issues of out-of-vocabulary words. Despite its success, a critical challenge persists: long tokens, rich in semantic information, have fewer occurrences in tokenized datasets compared to short tokens, which can result in imbalanced learning issue across different tokens. To address that, we propose LBPE, which prioritizes long tokens during the encoding process. LBPE generates tokens according to their reverse ranks of token length rather than their ranks in the vocabulary, granting longer tokens higher priority during the encoding process. Consequently, LBPE smooths the frequency differences between short and long tokens, and thus mitigates the learning imbalance. Extensive experiments across diverse language modeling tasks demonstrate that LBPE consistently outperforms the original BPE, well demonstrating its effectiveness.

[Arxiv](https://arxiv.org/abs/2411.05504)