# 学习识别关键信息：上下文位置编码的探索

发布时间：2024年05月28日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLM）中的位置编码问题，并提出了一种新的上下文位置编码（CoPE）方法。这种研究关注的是LLM内部机制的改进和优化，特别是位置编码的改进，这属于LLM理论的范畴。论文中提出的CoPE方法旨在提高模型在处理特定位置（如单词、名词或句子）时的灵活性和准确性，这是对LLM理论的深入探讨和创新，而非直接的应用或Agent、RAG相关的研究。` `机器学习`

> Contextual Position Encoding: Learning to Count What's Important

# 摘要

> 注意力机制虽使大型语言模型中的标记能相互作用，却缺乏顺序性。位置编码的引入，让我们能按位置关注，如关注序列中的第i个标记。但现有方法依赖标记计数确定位置，难以应用于更高层次的抽象，例如关注第i个句子。为此，我们提出了一种创新的上下文位置编码（CoPE）方法，它根据模型确定的特定标记来调整位置，从而实现更灵活的位置寻址，如关注特定的第i个单词、名词或句子。实验证明，CoPE在解决传统位置嵌入难以应对的选择复制、计数和翻转任务上表现出色，并在语言建模和编码任务中降低了困惑度。

> The attention mechanism is a critical component of Large Language Models (LLMs) that allows tokens in a sequence to interact with each other, but is order-invariant. Incorporating position encoding (PE) makes it possible to address by position, such as attending to the i-th token. However, current PE methods use token counts to derive position, and thus cannot generalize to higher levels of abstraction, such as attending to the i-th sentence. In this paper, we propose a new position encoding method, Contextual Position Encoding (CoPE), that allows positions to be conditioned on context by incrementing position only on certain tokens determined by the model. This allows more general position addressing such as attending to the $i$-th particular word, noun, or sentence. We show that CoPE can solve the selective copy, counting and Flip-Flop tasks where popular position embeddings fail, and improves perplexity on language modeling and coding tasks.

![学习识别关键信息：上下文位置编码的探索](../../../paper_images/2405.18719/x1.png)

![学习识别关键信息：上下文位置编码的探索](../../../paper_images/2405.18719/x2.png)

![学习识别关键信息：上下文位置编码的探索](../../../paper_images/2405.18719/x3.png)

![学习识别关键信息：上下文位置编码的探索](../../../paper_images/2405.18719/x4.png)

![学习识别关键信息：上下文位置编码的探索](../../../paper_images/2405.18719/x5.png)

![学习识别关键信息：上下文位置编码的探索](../../../paper_images/2405.18719/flipflop.png)

![学习识别关键信息：上下文位置编码的探索](../../../paper_images/2405.18719/x6.png)

![学习识别关键信息：上下文位置编码的探索](../../../paper_images/2405.18719/x7.png)

[Arxiv](https://arxiv.org/abs/2405.18719)