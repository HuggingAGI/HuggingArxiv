# 在长上下文语言模型盛行的当下，我们为 RAG 正名。

发布时间：2024年09月03日

`RAG` `问答系统` `人工智能`

> In Defense of RAG in the Era of Long-Context Language Models

# 摘要

> 尽管长上下文大型语言模型在处理长文本序列时表现出色，但我们认为其极长的上下文可能导致信息聚焦不足，从而影响答案质量。为此，我们重新探索了 RAG 在长上下文问答中的应用，并提出了一种创新的 OP-RAG 机制。该机制通过优化检索过程，确保在增加信息量的同时，答案质量呈现先升后降的倒 U 形曲线，找到最佳平衡点。实验结果显示，OP-RAG 在保持较低输入量的前提下，实现了比长上下文大型语言模型更高的答案质量，展现了其显著优势。

> Overcoming the limited context limitations in early-generation LLMs, retrieval-augmented generation (RAG) has been a reliable solution for context-based answer generation in the past. Recently, the emergence of long-context LLMs allows the models to incorporate much longer text sequences, making RAG less attractive. Recent studies show that long-context LLMs significantly outperform RAG in long-context applications. Unlike the existing works favoring the long-context LLM over RAG, we argue that the extremely long context in LLMs suffers from a diminished focus on relevant information and leads to potential degradation in answer quality. This paper revisits the RAG in long-context answer generation. We propose an order-preserve retrieval-augmented generation (OP-RAG) mechanism, which significantly improves the performance of RAG for long-context question-answer applications. With OP-RAG, as the number of retrieved chunks increases, the answer quality initially rises, and then declines, forming an inverted U-shaped curve. There exist sweet points where OP-RAG could achieve higher answer quality with much less tokens than long-context LLM taking the whole context as input. Extensive experiments on public benchmark demonstrate the superiority of our OP-RAG.

[Arxiv](https://arxiv.org/abs/2409.01666)